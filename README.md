<!DOCTYPE html>
<!-- saved from url=(0040)file:///C:/Users/User/Desktop/index.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
    <link rel="stylesheet" href="./index_files/style.css">
  </head>
  <body>
    <div class="container">
      <div>
        <h1 class="header_text">Do you wanna go out with me?</h1>
      </div>
      <p>
              </p><div class="gif_container">
        <img src="./index_files/milk-and-mocha-cute.gif" alt="Cute animated illustration">
      </div>
      <div class="buttons">
        <button class="btn" id="yesButton" onclick="nextPage()">Yes</button>
        <button class="btn" id="noButton" onmouseover="moveButton()" onclick="moveButton()">
          No
        </button>

        <script>
          function nextPage() {
            window.location.href = "yes.html";
          }

          function moveButton() {
            var x =
              Math.random() *
              (window.innerWidth -
                document.getElementById("noButton").offsetWidth);
            var y =
              Math.random() *
              (window.innerHeight -
                document.getElementById("noButton").offsetHeight);
            document.getElementById("noButton").style.left = `${x}px`;
            document.getElementById("noButton").style.top = `${y}px`;
          }
        </script>
      </div>
    </div>
  

</body></html>
