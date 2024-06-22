<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>arduino@home</title>
    <meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;">
    <style type="text/css">
  body {
    /* 內文採用非襯線字體 */
    font-family:"微軟正黑體", "黑體-繁", sans-serif;
    /* 灰色背景 */
    background-color:#CCC;
  }
  
  .sw {
    /* 上下不留白，左右留白半個字體高 */
    margin:0 0.5em;
    /* 以粗體字樣式呈現 */
    font-weight:bolder;
    }
  
  .on {
    color:#F00;  /* 紅色字體 */
  }
  
  .off {
    color:#090;	/* 綠色字體 */
  }
  
  /* 設定lights區塊 */
  #lights {
    /* 邊框圓角半徑 10像素 */
    border-radius:10px;
    -moz-border-radius:10px;
    -webkit-border-radius:10px;
    /* 白色背景 */
    background-color:#FFF;
    /* 內距 1像素 */
    padding:1px;
  }
  
  /* 設定lights 區塊裡的清單樣式 */
  #lights ul {
    /* 不顯示圓點 */
    list-style-type:none;
    /* 左邊內距為 0（取消預設的清單元素縮排）*/
    padding-left:0px;
    /* 字體大小：24點 */
    font-size:24pt;
  }
  
  /* 設定lights 區塊裡的清單項目樣式 */
  #lights ul li {
    /*  上下留白10像素，左右不留白。 */
    margin:10px 0;
    /*  1像素點狀灰色底線  */
    border-bottom:1px dotted #CCC;
    /*  底部內距 5像素  */
    padding-bottom:5px;
  }
  
  /* 設定lights 區塊裡的清單超連結樣式 */
  #lights ul li a {
    /* 讓超連結感應整個區塊 */
    display:block;
    /* 消除底線 */
    text-decoration:none;
    /* 黑色字體 */
    color:#000;
  }
</style>
  </head>
  <body>
    <h1>遙控家電</h1>
    <div id="lights">
      <ul>
        <li><a href="sw?id=0"><span class='sw on'>ON</span>檯燈</a></li>
        <li><a href="sw?id=1"><span class="sw on">ON</span>壁燈</a></li>
        <li><a href="sw?id=2"><span class="sw off">OFF</span>吊燈</a></li>
        <li><a href="sw?id=3"><span class="sw off">OFF</span>落地燈</a></li>
        <li><a href="sw?id=4"><span class="sw off">OFF</span>熔岩燈</a></li>
        <li><a href="sw?id=5"><span class="sw off">OFF</span>藤球燈</a></li>
      </ul>
    </div>
 </body>
</html>
