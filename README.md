<head>
  <meta name="viewport" content="width=device-width,   intial-scale=1.0">
  <title>keyboard</title>
  <style>
  body{
       width:100%;    height:950px;                      margin:100px auto;
      padding:5px;                background-color:white;
  }
  li{
      color:white;       box-shadow: 0px 0px 4px 1px purple;
  }

 .c{
     float:left;      list-style-type:none;              border-radius:30%;          cursor:pointer;
     border:3px;        padding:5px 20px;
     margin:1px 1px;      background-color:black;
      }
 li:hover {
	background-color:grey;  }
 .unique{
     list-style-type:none;      border-radius:10%;         background-color:black;
     margin:1px 1px;                float:left;                padding:20px 14px;                cursor:pointer;
 }
 .secondTop{
     float:left;      list-style-type:none;              border-radius:30%;
     border:3px;      border:2px;                        padding:20px 24px;            cursor:pointer;
     margin:1px 1px 1px 1px;    background-color:black;    top:0px;
 }
  .thirdTop{
     float:left;      list-style-type:none;              border-radius:30%;             ;
     border:3px;      border:2px;                        padding:20px 24px;                cursor:pointer;
     margin:1px 1px 1px 1px;      background-color:black;     top:0;
  }
  .double {
  padding-top: 10px;
  padding-bottom: 10px;
  }
  .last {
      padding:10px 5px;
  }
.back{
    padding:10px 20px;   border-radius:15%
}
.mouse{  
     width: 350px; height: 200px;                           background-color:pink;padding:5px;
       border-radius:10%;                                       box-shadow: 3px 2px 8px 5px black;cursor:pointer;
}
  </style>
</head>

<body> <div style="background-color:violet;padding:5px;border:10px solid pink; box-shadow: -20px -30px 20px  black;">
<ul style="margin-left:4%">
        <li class="c">esc</li>         <li class="c">f1</li>          <li class="c">f2</li>
        <li class="c">f3</li>        <li class="c">f4</li>        <li class="c">f5</li>
        <li class="c">f6</li>          <li class="c">f7</li>          <li class="c">f8</li>
        <li class="c">f9</li>       <li class="c">f10</li>       <li class="c">f11</li>
        <li class="c">f12</li>      <li class="c">prt sc</li>              <li class="c" style="border-radius:50%;padding:14px"></li>
    </ul>
    <br>
    <ul style="margin-left:4%;">
        <li class="unique double">~<br>`</li>     <li class="secondTop double">!<br>1</li>       <li class="secondTop double">@<br>2</li>              <li class="secondTop double">#<br>3</li>
        <li class="secondTop double">$<br>4</li>  <li class="secondTop double">%<br>5</li>       <li class="secondTop double">^<br>6</li>            <li class="secondTop double">&<br>7</li>
        <li class="secondTop double">*<br>8</li>  <li class="secondTop double">(<br>9</li>      <li class="secondTop double">)<br>0</li>            <li class="secondTop double">_<br>-</li>
        <li class="secondTop double">+<br>=</li>   <li class="secondTop double back">backspace<br>&larr;</li>
    </ul>
    <br><br>
    <ul style="margin-left:4%">
        <li class="thirdTop double" style="padding:10px 30px;border-radius:20%">⇰<br>tab</li>          <li class="thirdTop">Q</li>      <li class="thirdTop">W</li>
         <li class="thirdTop">E</li>           <li class="thirdTop">R</li>       <li class="thirdTop">T</li>
         <li class="thirdTop">Y</li>        <li class="thirdTop">U</li>           <li class="thirdTop">I</li>
         <li class="thirdTop">O</li>         <li class="thirdTop">P</li>             <li class="thirdTop double">{<br>[</li>
           <li class="thirdTop double">}<br>]</li>        <li class="thirdTop double">|<br>\</li>
    </ul>
     <br><br><br>
    <ul style="margin-left:4%">
        <li class="thirdTop" style="padding:20px 16px;border-radius:20%">caps lock</li>          <li class="thirdTop">A</li>      <li class="thirdTop">S</li>
         <li class="thirdTop">D</li>           <li class="thirdTop">F</li>       <li class="thirdTop">G</li>
         <li class="thirdTop">H</li>        <li class="thirdTop">J</li>           <li class="thirdTop">K</li>
         <li class="thirdTop">L</li>         <li class="thirdTop double">:<br>;</li>             <li class="thirdTop double">"<br>'</li>
           <li class="thirdTop" style="padding:19px 30px;border-radius:20%">enter ⮨</li>
    </ul>
     <br><br><br>
    <ul style="margin-left:4%">
        <li class="thirdTop" style="padding:18px 40px;border-radius:20%">shift ⇧</li>          <li class="thirdTop">Z</li>      <li class="thirdTop">X</li>
         <li class="thirdTop">C</li>           <li class="thirdTop">V</li>       <li class="thirdTop">B</li>
         <li class="thirdTop">N</li>        <li class="thirdTop">M</li>           <li class="thirdTop double"><<br>,</li>
         <li class="thirdTop double">><br>.</li>         <li class="thirdTop double">?<br>/</li>             <li class="thirdTop" style="padding:18px 43px;border-radius:20%">shift  ⇧</li>
    </ul>
     <br><br><br>
    <ul style="margin-left:4%;">
        <li class="thirdTop ">fn</li>          <li class="thirdTop">ctrl</li>      <li class="thirdTop double last">⌥<br>option</li>
         <li class="thirdTop double last">⌘<br>command</li>           <li class="thirdTop" style="border-radius:10%"><hr style="width: 240px; height: 0.5px;"></li>       <li class="thirdTop double last">⌘<br>command</li>
         <li class="thirdTop double last">⌥<br>option</li>        <li class="thirdTop"><</li>           <li class="thirdTop double lst">^<br>˅</li>
         <li class="thirdTop">&gt;</li>
    </ul>
    <br><br><br><br> <hr><br>
    <hr class="mouse">
           </div>
</body>

</html>
