# O2 D3 for Angular2 by TypeScript


"o2d3ng2" is a chart library using d3.js for Angular2 written by TypeScript.

**Overview**
   - "o2d3ng2" is a wrapper library of d3.js for Angular2
   - 11 main charts are supported

    (Line,Bar,Pie,ScatterPlot,Histogram,Stack Bar, Geo Map, Geo Orthographic, Tree Map, Pack Layout, Choropleth)
    
   - Axis

    You can include axis automatically by the configuration file.
   
   - Legend 

    You can include legend automatically by the configuration file.

   - Animation

    You can animate such charts as Bar, Pie, Histogram, Stack Bar,Geo Orthographic and Pack Layout charts by the configuration file.

    *Sample program is using Tab Pages of "Bootstrap" to display all the charts. If you want to check the animation, please change the source file a bit as follows.
    
    In "app.components.ts", the current default chart is set "geoOrthographicTypeName". So please change it to your favourite chart type and the chart type own data. 
    
**Prerequisite**

   - node.js
   - concurrently
   - live-server
   - bootstrap
   - typescript


**Install**

Download or clone all the source files. 

   - Change directory into "prg" in your downloaded directory.
    
    You will find directories and files as follows.

        [data]        
        [node_modules]        
        [src]        
        index.html        
        package.json        
        tsconfig.json
       
    
   - input "npm install" in the command prompt.
   
     Then all the filles will be installed in your local directory.
     
**How to run** 

  - input "npm start" in the same directory.
  
     Then local http server will start and your default browser will be shown.  

**Chart Data**

 There are two types of data:"configData","graphData".
 
 - configData
 
 This is a common setting data of all charts. In this file, you can set info as follows.
 
 -Class name defined by "html" file
 
 -Title Name
 
 -Legend (display or not, position, size)
 
 -Color (Auto color number: 10 or 20, Opacity) 
 
 -Line (interpolate)
 
 -Grid (display or not, position, size)
 
 -Margin (top, left, right,bottom,between)
 
 -Axis (left margin, bottom mergin)
 
 -Animation (enable or not, duration)
 
 In more details, please refer to the sample "this.configData" in app.components.ts.
 
 
 - graphData

 Each chart needs its own data in Jason format. You can understand the format easily by referencing to the Json Data. For example, if you want to know Line chart data format, please refer to "this.lineDataJson" in app.components.ts.

**Version**

   - o2d3ng2    : 1.0
   - Angular2   : 2.0.0-beta.0
   - TypeScript : 1.7.3
   - d3.js      : latest
   

- Visual Studio 2015 version 14.023107.0 D14REL


**Reference**

- "データビジュアライゼーションのためのD3.js徹底入門 Webで魅せるグラフ&チャートの作り方",2014/6/6,by 古籏 一浩, 
<https://http://www.amazon.co.jp/s/ref=nb_sb_noss?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&url=search-alias%3Daps&field-keywords=ISBN978-4-7973-6886-4&rh=i%3Aaps%2Ck%3AISBN978-4-7973-6886-4>

- "D3.js by Example",2015/12/29,by Michael Heydt
<http://www.amazon.co.jp/s/ref=nb_sb_noss?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&url=search-alias%3Daps&field-keywords=ISBN978-1-78528-008-5&rh=i%3Aaps%2Ck%3AISBN978-1-78528-008-5>

- "Mastering D3.js",2014/8/25,by Pablo Navarro,
<http://www.amazon.co.jp/s/ref=nb_sb_noss?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&url=search-alias%3Daps&field-keywords=ISBN978-1-78328-627-0&rh=i%3Aaps%2Ck%3AISBN978-1-78328-627-0>

- "Data Visualization With D3 and Angularjs",2015/4/27,by Christoph Korner,
<http://www.amazon.co.jp/s/ref=nb_sb_noss?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&url=search-alias%3Daps&field-keywords=ISBN978-1-78439-848-4&rh=i%3Aaps%2Ck%3AISBN978-1-78439-848-4>

- "Mastering TypeScript",2015/4/23,by Nathan Rozentals,
<http://www.amazon.co.jp/s/ref=nb_sb_noss?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&url=search-alias%3Daps&field-keywords=ISBN978-1-78439-966-5&rh=i%3Aaps%2Ck%3AISBN978-1-78439-966-5>

**Change Log**

 - 2016.3.11 version 1.0 uploaded

**Copy right**

copy right 2016 by Shuichi Ohtsu (DigiPub Japan)

