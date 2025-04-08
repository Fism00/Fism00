<head>
  <link rel="stylesheet" type='text/css' href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css" />
</head>
<h1>
  Bom Momento, Eu sou Heitor.
</h1>
 <style>
     .pieContainer {
          height: 100px;
     }
     .pieBackground {
          background-color: grey;
          position: absolute;
          width: 100px;
          height: 100px;
          -moz-border-radius: 50px;
          -webkit-border-radius: 50px;
          -o-border-radius: 50px;
          border-radius: 50px;
          -moz-box-shadow: -1px 1px 3px #000;
          -webkit-box-shadow: -1px 1px 3px #000;
          -o-box-shadow: -1px 1px 3px #000;
          box-shadow: -1px 1px 3px #000;
     }
     .pie {
          position: absolute;
          width: 100px;
          height: 100px;
          -moz-border-radius: 50px;
          -webkit-border-radius: 50px;
          -o-border-radius: 50px;
          border-radius: 50px;
          clip: rect(0px, 50px, 100px, 0px);
     }
     .hold {
          position: absolute;
          width: 100px;
          height: 100px;
          -moz-border-radius: 50px;
          -webkit-border-radius: 50px;
          -o-border-radius: 50px;
          border-radius: 50px;
          clip: rect(0px, 100px, 100px, 50px);
     }
     #pieSlice1 .pie {
          background-color: #1b458b;
          -webkit-transform:rotate(50deg);
          -moz-transform:rotate(50deg);
          -o-transform:rotate(50deg);
          transform:rotate(50deg);
     }

</style>

<div class="pieContainer">
     <div class="pieBackground"></div>
     <div id="pieSlice1" class="hold">
        <div class="pie"></div>
    </div>
