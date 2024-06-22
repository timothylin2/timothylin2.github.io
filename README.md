<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>arduino@home</title>
<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;">
<style type="text/css">
  body {
    /* ?扳??∠?弁蝺?擃?*/
    font-family:"敺株?甇??擃?, "暺?-蝜?, sans-serif;
    /* ?啗? */
    background-color:#CCC;
  }
  
  .sw {
    /* 銝?銝??踝?撌血???擃? */
    margin:0 0.5em;
    /* 隞亦?擃?璅??? */
    font-weight:bolder;
    }
  
  .on {
    color:#F00;  /* 蝝摮? */
  }
  
  .off {
    color:#090;	/* 蝬摮? */
  }
  
  /* 閮剖?lights?憛?*/
  #lights {
    /* ?????? 10?? */
    border-radius:10px;
    -moz-border-radius:10px;
    -webkit-border-radius:10px;
    /* ?質? */
    background-color:#FFF;
    /* ?扯? 1?? */
    padding:1px;
  }
  
  /* 閮剖?lights ?憛ㄐ???格見撘?*/
  #lights ul {
    /* 銝＊蝷箏?暺?*/
    list-style-type:none;
    /* 撌阡??扯???0嚗?瘨?閮剔?皜??蝮格?嚗?/
    padding-left:0px;
    /* 摮?憭批?嚗?4暺?*/
    font-size:24pt;
  }
  
  /* 閮剖?lights ?憛ㄐ???桅??格見撘?*/
  #lights ul li {
    /*  銝??10??嚗椰?喃????*/
    margin:10px 0;
    /*  1??暺??啗摨?  */
    border-bottom:1px dotted #CCC;
    /*  摨?扯? 5??  */
    padding-bottom:5px;
  }
  
  /* 閮剖?lights ?憛ㄐ???株????璅?? */
  #lights ul li a {
    /* 霈???????游?憛?*/
    display:block;
    /* 瘨摨? */
    text-decoration:none;
    /* 暺摮? */
    color:#000;
  }
</style>
</head>
<body>
<h1>?摰園</h1>
<div id="lights">
    <ul>
      <li><a href="sw?id=0"><span class='sw on'>ON</span> 瑼舐?</a></li>
      <li><a href="sw?id=1"><span class="sw on">ON</span> 憯?</a></li>
      <li><a href="sw?id=2"><span class="sw off">OFF</span> ??</a></li>
      <li><a href="sw?id=3"><span class="sw off">OFF</span> ?賢??/a></li>
      <li><a href="sw?id=4"><span class="sw off">OFF</span> ?痔??/a></li>
      <li><a href="sw?id=5"><span class="sw off">OFF</span> ?斤???/a></li>
    </ul>
</div>
</body>
</html>
