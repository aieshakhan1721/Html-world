<!DOCTYPE html>
<html>
    <head>
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Page one</title>
        <style>
            tr:nth-child(even){
                background-color: rgba(178, 60, 74, 0.4);
            }
            th:nth-child(even)
            {
                background-color:rgba(207, 84, 98, 0.4);
            }
            .mycontainer {
            display: flex;
            }
            .mycontainer > div {
            width:33%;
            }
          .menu {
           float: left;
           width: 20%;
          }
          #div1 {
          width: 400px;
          height: 90px;
          padding: 15px;
          border: 1px solid #aaaaaa;
          }
        </style>
    </head>
    <body style="background-color: papayawhip;">
        <u><p style="text-align: center;">	&#128508; HTML WORLD 	&#128508;</p></u>
        <h4 style="font-size:300%;">Headings</h4> 
        <h3 style="font-family:courier;">Different font sizes.</h3>
        <h1 style="background-color: white;">My first heading</h1><hr>
        <h2 style="background-color: white;">My second heading</h2><hr>
        <h3 style="background-color: white;">My third heading</h3><hr>
        <h4 style="background-color: white;">My fourth heading</h4><hr>
        <h5 style="background-color: white;">My fifth heading</h5><hr>
        <h6 style="background-color: white;">My sixth heading</h6><hr><br><br>
        <p style="color : palevioletred;">This is my first html page.</p><hr><br><br>
        <a href='https://www.w3schools.com/html/html_basic.asp'>html full course</a><hr><br>
        <img src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582748_960_720.png" alt="w3schools.com" width="100" height="100"><hr>
        <u><p style="text-align:center;"> HTML Fromatting Elements &#128587;</p></u>
        <p><b>This is a bold text.</b></p>
        <p><strong>This is a strong text.</strong></p>
        <p><i>This is a text in italic font.</i></p>
        <p><em>This is a emphasized text.</em></p>
        <p>Pari . This is a <mark>name</mark></p>
        <p><small>This is a small text.</small></p>
        <p>My fav color is <del>blue</del>no color.</p>
        <p>This is a <sub>subscript</sub>text.</p>
        <p>This is a <sup>superscript</sup>text</p>
        <p>This line is regarding<q>quotation</q></p>
        <address>
            Front house colony<br>
            B12 street,Downtown<br>
        </address>
        <hr><hr>
        <u><h3 style="text-align: center;"> Inline  , Internal , External CSS &#128493;</h3></u>
        <p style="color:purple">This is inline css.</p>
        <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools in blank mode !</a> <br>
        <a href="https://www.w3schools.com/" target="_self">Visit W3Schools in self mode !</a> <br>
        <a href="https://www.w3schools.com/" target="_parent">Visit W3Schools in parent mode !</a> <br>
        <a href="https://www.w3schools.com/" target="_top">Visit W3Schools in top mode !</a> <br>
        <a href="https://www.geeksforgeeks.org/learn-data-structures-and-algorithms-dsa-tutorial/"><img src="https://media.geeksforgeeks.org/wp-content/uploads/20230819113602/dsa-by-sandeep-jain.png" style="float:right;width:42px;height:42px;">This is a dsa link<br></a>
        <a href="mailto:aieshakhan1721@gmail.com">Send mail</a>
        <hr><hr>
       <u><h3 style="text-align:center;">Tables &#128197;</h3></u>
        <table style="width:100%">
            <th style="width:60%">First Name</th>
            <th>Last Name</th>
            <th>Age</th>
            <tr>
                <td>Ayesha Siddiq</td><td>Shaik</td><td>20</td>
            </tr>
            <tr>
                <td>Rizwana Parizad</td><td>Shaik</td><td>17</td>
            </tr>
            <tr>
                <td>Karsihma Naquie</td><td>Shaik</td><td>27</td>
            </tr>
        </table>
        <hr><hr>
       <u><h3 style="text-align: center;">LISTS &#128205;</h3></u>
         <p>Ordered Lists</p>
         <ol type="A">
            <li>List one</li>
            <li>List Two</li>
            <li>List Three</li>
         </ol>
        <p>Unordered Lists</p>
        <ul>
        <li>List one</li>
        <li>List two</li>
        <li>List Three</li></ul>
        <p>Description List</p>
         <dl>
            <dt>Coffee</dt><dd>-black hot drink</dd>
            <dt>Milk</dt><dd>-white cold drive</dd>
         </dl>
         <hr><hr>
         <u><h3 style="text-align: center;">Inline and Blockline &#128218;</h3></u>
         <div style="background-color:#eeba7c;">
            <h2>London</h2>
            <p>London is the capital city of England.</p>
            <p>London has over 13 million inhabitants.</p>
          </div>
          
          <div style="background-color:#FFC0C7;">
            <h2>Oslo</h2>
            <p>Oslo is the capital city of Norway.</p>
            <p>Oslo has over 600.000 inhabitants.</p>
          </div>
          
          <div style="background-color:#D9EEE1;">
            <h2>Rome</h2>
            <p>Rome is the capital city of Italy.</p>
            <p>Rome has almost 3 million inhabitants.</p>
          </div>
          <br><br><br>
          <div class="mycontainer">

            <div style="background-color:#eeba7c;">
              <h2>London</h2>
              <p>London is the capital city of England.</p>
              <p>London has over 13 million inhabitants.</p>
            </div>
            
            <div style="background-color:#FFC0C7;">
              <h2>Oslo</h2>
              <p>Oslo is the capital city of Norway.</p>
              <p>Oslo has over 600.000 inhabitants.</p>
            </div>
            
            <div style="background-color:#D9EEE1;">
              <h2>Rome</h2>
              <p>Rome is the capital city of Italy.</p>
              <p>Rome has almost 3 million inhabitants.</p>
            </div>
          </div>
          <hr><hr>
          <u><h3 style="text-align: center;">ID &#128387;</h3></u>
          <a href=""html_demo.html#C4">Junp to chapter 4</a>
          <h2>Chapter 1</h2><p>This is chapter 1</p>
          <h2>Chapter 2</h2><p>This is chapter 2</p>
          <h2>Chapter 3</h2><p>This is chapter 3</p>
          <h2 id="c4">Chapter 4</h2><p>This is chapter 4 with its bookmark created.</p>
          <hr><hr>
          <u><h3 style="text-align: center;">IFRAME &#128421;</h3></u>
          <h2>Iframe - Target for a Link</h2>
          <iframe src="demo_iframe.htm" name="iframe_a" height="300px" width="100%" title="Iframe Example"></iframe>
          <p><a href="https://roadmap.sh/full-stack" target="iframe_a">Slash mark</a></p>
          <p>When the target attribute of a link matches the name of an iframe, the link will open in the iframe.</p>
          <hr><hr>
          <u><h3 style="text-align: center;">RESPONSIVE WEB DESIGN &#128242;</h3></u>
          <div style="overflow:auto">
            <div class="menu">
              <div class="menuitem">The Walk</div>
              <div class="menuitem">Transport</div>
              <div class="menuitem">History</div>
              <div class="menuitem">Gallery</div>
            </div>
          
            <div class="main">
              <h2>The Walk</h2>
              <p>The walk from Monterosso to Riomaggiore will take you approximately two hours, give or take an hour depending on the weather conditions and your physical shape.</p>
              <img src="https://d1c96a4wcgziwl.cloudfront.net/9f73Monterosso02_theOldVillage.jpg" style="max-width:100%;height:auto;;">
            </div>
          <hr><hr>
         <u><h3 style="text-align: center;">Computer Code &#128389;</h3></u>
          <p>Save the document by pressing This is a keyboard input tag <kbd>Ctrl + S</kbd></p>
          <p>Message from my computer using samp tag:</p>
          <p><samp>File not found.<br>Press F1 to continue</samp></p>
          <p>Below is a code which is written in between code tag and enclosed with pre tag.</p>
          <pre>
            <code>
            x = 5;
            y = 6;
            z = x + y;
            </code>
            </pre>
            <p>Below is the line where variables are been printed in Italic using var tag.</p>
            <p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>
            <hr><hr>
            <u><h3 style="text-align: center;">Forms</h3></u>
            <p> This is an example of form.</p>
            <form autocomplete="on">
              <fieldset>
                <label>Personalize:</label>
              <label for="name">Name</label><br>
              <input type="text" id="name" name="name"><br>
              <label for="place">Place</label><br>
              <input type="text" id="place" name="place"><br>
              <label for="psw">Password</label><br>
              <input type="password" id="psw" name="psw"><br>
              <label for="favcolor">Select your favorite color:</label><br>
             <input type="color" id="favcolor" name="favcolor"><br>
             <label for="bdaymonth">Birthday (month and year):</label><br>
             <input type="month" id="bdaymonth" name="bdaymonth"><br>
             <label for="birthday">Birthday:</label><br>
              <input type="date" id="birthday" name="birthday"><br>
              <label for="email">Enter your email:</label><br>
              <input type="email" id="email" name="email"><br>
              <label for="myfile">Upload your certificates:</label><br>
              <input type="file" id="myfile" name="myfile"><br>
              <label for="phone">Enter your phone number:</label><br>
              <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br>
              <input type="submit" value="submit">
              <input type="reset" value="reset">
            </form>
          </fieldset>
            <p>This is an example of radio button.</p>
            <p>Choose your fav language</p>
            <form>
              <input type="radio" id="html" value="html">
              <label for="html">HTML</label><br>
              <input type="radio" id="css" value="css">
              <label for="css">CSS</label><br>
              <input type="radio" id="js" value="js">
              <label for="js">Java Script</label><br>
            </form>
            <p>This is an example for checkboxes along with submit button.</p>
            <p>Choose the vehicle you have.</p>
            <form>
              <input type="checkbox" id="bike" value="bike">
              <label for="bike">Bike</label><br>
              <input type="checkbox" id="car" value="car">
              <label for="car">Car</label><br>
              <input type="checkbox" id="scooty" value="scooty">
              <label for="scooty">Scooty</label><br>
              <input type="Submit" value="Submit">
            </form>
            <label for="cars">Cars</label><br>
            <select id="cars" name="cars" size="3">
              <option value="Volvo">Volvo</option>
              <option value="Ford">Ford</option>
              <option value="BMW" selected="BMW">BMW</option>
              <option value="Kia">Kia</option>
            </select><br><br>
            <button typ="button" onclick="alert('Hello World!')">Click Me!!!</button>
            <p>This is an exmaple of datalist.</p>
            <form>
              <input  list="browsers" name="browsers">
                <datalist id="browsers">
                  <option value="Chrome">Chrome</option>
                  <option value="Firefox">FireFox</option>
                  <option value="Opera">Opera</option>
                  <option value="safari">safari</option>
                </datalist>
              </inputlist>
            </form>
          <p>This is an example of output element</p>
          <form
          oninput="x.value=parseInt(a.value)+parseInt(b.value)">
            0
            <input type="range" id="a" name="a" value="50">
            100 +
            <input type="number" id="b" name="b" value="50">
            =
            <output name="x" for="a b"></output>
            <br><br>
            <input type="submit">
          </form>
          <hr><hr>
         <u><h3 style="text-align: center;">Canvas</h3></u>
         <p> This is a canvas.</p>
         <canvas id="mycan" width="500" height="100" style="border:1px solid #000000;"></canvas>
         <p>This is a canvas with a line included in it drawn by using java script.</p><br>
         <canvas id="mycanvas" width="200" heigth="100" style="border:1px solid #000000;"></canvas>
         <script>
          var c=document.getElementById("mycanvas");
          var ctx=c.getContext("2d");
          ctx.moveTo(0,0);
          ctx.lineTo(200,100);
          ctx.stroke();
         </script><br>
         <p>This is a canvas with a circle included in it drawn by using java script. </p><br>
         <canvas id="mycirc" width="200" heigth="100" style="border:1px solid #000000;"></canvas>
         <script>
          var c = document.getElementById("mycirc");
          var ctx = c.getContext("2d");
          ctx.beginPath();
          ctx.arc(95,50,40,0,2*Math.PI);
          ctx.stroke();
         </script>
         <p>This is a canvas with a text included in it drawn by using java script. </p><br>
         <canvas id="mytex" width="200" heigth="100" style="border:1px solid #000000;"></canvas>
         <script>
          var c = document.getElementById("mytex");
          var ctx = c.getContext("2d");
          ctx.font = "30px Arial";
          ctx.fillText("Hello World", 10, 50);
          </script>
          <p>This is a canvas with a gradient included in it drawn by using java script. </p><br>
          <canvas id="mygrd" width="200" heigth="100" style="border:1px solid #000000;"></canvas>
          <script>
            var c = document.getElementById("mygrd");
            var ctx = c.getContext("2d");
            var grd = ctx.createLinearGradient(0, 0, 200, 0);
            grd.addColorStop(0, "pink");
            grd.addColorStop(1, "white");
            ctx.fillStyle = grd;
            ctx.fillRect(10, 10, 150, 80);
            </script>
            <p>This is a canvas with an image included in it drawn by using java script. </p><br>
            <p>Image to use:</p>
            <img id="parrots" src="https://t3.ftcdn.net/jpg/05/78/97/60/360_F_578976007_Rt1z9536laf2dgPfnu9YkTsSzuA5svHy.jpg" alt="The Flock" width="400" height="377">
            <p>Canvas to fill:</p>
            <canvas id="myimg" width="400" height="377" style="border:1px solid #d3d3d3;"></canvas>
            <p><button onclick="myCanvas()">Try it</button></p>
            <script>
            function myCanvas() {
            var c = document.getElementById("myimg");
            var ctx = c.getContext("2d");
            var img = document.getElementById("parrots");
            ctx.drawImage(img,10,10); }
            </script>
            <u><h3 style="text-align: center;">SVG (Scalar Vector Graphics)</h3></u>       
            <p>Draw a circle.</p><br>
            <svg width="100" height="100">
              <circle cx="50" cy="50" r="40" stroke="white" stroke-width="2" fill="pink" />
            </svg>   
            <p>Draw a rectangle</p>
            <svg width="400" height="100">
              <rect width="400" height="100" style="fill:rgb(99,221,240);stroke-width:10;stroke:rgb(222, 220, 220)" />
            </svg>  
            <p>Draw a rounded rectangle.</p>
            <svg width="400" height="180">
              <rect x="50" y="20" rx="20" ry="20" width="150" height="150"
              style="fill:red;stroke:black;stroke-width:5;opacity:0.5" />
            </svg>
            <p> Draw a star</p>
            <svg width="300" height="200">
              <polygon points="100,10 40,198 190,78 10,78 160,198"
              style="fill:rgb(226, 130, 226);stroke:rgb(223, 213, 232);stroke-width:5;fill-rule:evenodd;" />
            </svg>
            <p>Create a logo</p>
            <svg height="130" width="500">
              <defs>
                <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
                  <stop offset="0%" style="stop-color:royalblue;stop-opacity:1" />
                  <stop offset="100%" style="stop-color:peachpuff;stop-opacity:1" />
                </linearGradient>
              </defs>
              <ellipse cx="100" cy="70" rx="85" ry="55" fill="url(#grad1)" />
              <text fill="#ffffff" font-size="45" font-family="Verdana" x="50" y="86">HTML</text>
            </svg>
            <hr><hr>
            <u><h3 style="text-align: center;">HTML Media</h3></u>
            <p> This is the implementation of html video in media by using the tags video,source and type mp4.</p>
            <video width="800" height="500" controls>
              <source src="C:\Users\aiesh\Downloads\avatar movie scenes.mp4" type="video/mp4">
              <source src="C:\Users\aiesh\Downloads\avatar movie scenes.mp4" type="video/mp4">
            </video>
            <p>This is the implementation of html audio by using the tags audio,source and type mp3.</p>
            <audio controls>
              <source src="C:\Users\aiesh\Downloads\Avatar_Film_Theme_Song-452252.mp3" type="audio/mp3">
              <source src="C:\Users\aiesh\Downloads\Avatar_Film_Theme_Song-452252.mp3" type="audio/mp3">
            </audio>
            <p>This is the implementationof html youtube</p>
            <iframe width="420" height="345" src="https://www.youtube.com/embed/tgbNymZ7vqY">
            </iframe>
            <hr><hr>
            <u><h3 style="text-align: center;"> HTML GEOLOCATION API</h3></u>
            <p>Click the button to get your coordinates.</p>
            <button onclick="getLocation()">Try It</button>
            <p id="demo"></p>
            <script>
              const x = document.getElementById("demo");
              function getLocation() {
                if (navigator.geolocation) {
                  navigator.geolocation.getCurrentPosition(showPosition, showError);
                } else { 
                  x.innerHTML = "Geolocation is not supported by this browser.";
                }
              }              
              function showPosition(position) {
                x.innerHTML = "Latitude: " + position.coords.latitude + 
                "<br>Longitude: " + position.coords.longitude;
              }
              function showError(error) {
                switch(error.code) {
                  case error.PERMISSION_DENIED:
                    x.innerHTML = "User denied the request for Geolocation."
                    break;
                  case error.POSITION_UNAVAILABLE:
                    x.innerHTML = "Location information is unavailable."
                    break;
                  case error.TIMEOUT:
                    x.innerHTML = "The request to get user location timed out."
                    break;
                  case error.UNKNOWN_ERROR:
                    x.innerHTML = "An unknown error occurred."
                    break;
                }
              }
              </script>
              <script>
                function allowDrop(ev) {
                  ev.preventDefault();
                }
                function drag(ev) {
                  ev.dataTransfer.setData("text", ev.target.id);
                }
                function drop(ev) {
                  ev.preventDefault();
                  var data = ev.dataTransfer.getData("text");
                  ev.target.appendChild(document.getElementById(data));
                }
                </script>
                <p>Drag the W3Schools image into the rectangle:</p>
                 <div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
                <br>
                <img id="drag1" src="https://data.textstudio.com/output/sample/animated/5/9/4/7/html-3-17495.gif" draggable="true" ondragstart="drag(event)" width="500" height="90">
                <p>Count numbers: <output id="result"></output></p>
                <button onclick="startWorker()">Start Worker</button> 
                <button onclick="stopWorker()">Stop Worker</button>
                
                <p><strong>Note:</strong> Internet Explorer 9 and earlier versions do not support Web Workers.</p>
                
                <script>
                var w;
                
                function startWorker() {
                  if(typeof(Worker) !== "undefined") {
                    if(typeof(w) == "undefined") {
                      w = new Worker("demo_workers.js");
                    }
                    w.onmessage = function(event) {
                      document.getElementById("result").innerHTML = event.data;
                    };
                  } else {
                    document.getElementById("result").innerHTML = "Sorry, your browser does not support Web Workers...";
                  }
                }
                
                function stopWorker() { 
                  w.terminate();
                  w = undefined;
                }
                </script> 
</html>
