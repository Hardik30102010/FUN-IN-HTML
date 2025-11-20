# FUN-IN-HTMLIt is like a trap , You need to come of of it ( come on starting screen) but you can't :–)



<html>
  <head>
  <title> MAGIC loop </title>
    <style>
      body{
        background-color: #eaffae;
        text-align: center;
      }
      button {
      border: 2px solid black;
      }
      hr {
      border: none; 
      border-top: 1px solid black; 
      width: 100%; 
    }
        
      
    </style>
  </head>
  <body>
    <h1 id="W">this text will change! if you click the button</h1>
    <br>
    <br>
    <br>
    <br>
    <hr>
    <br>
    <br>
    <br>
    <button onclick="ct()BUTTON</button>

    <script>
      function ct() {
        document.getElementById("W").innerHTML = "<b>see it changed</b> <br><br><br><br><hr><br> Now click the below button :—) <br> <button onclick=H()>Click</button><br>" ;
      }
      function H() {
        document.getElementById("W").innerHTML = "<b> SEE IT CHANGED AGAIN <br> click the below button again and try to restart :-) </b>";
      }
    </script>
  </body>
</html>
