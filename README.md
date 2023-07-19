
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>jonessciencetutors.cf</title>

    <meta name="description" content="Name">
    <meta name="viewport" content="width=device-width,initial-scale=1.0, maximum-scale=1, user-scalable=no" />

    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body style="overflow: hidden;">
<script>
function cloak() {
var win = window.open()
var url = window.location.href

var backbutton = win.document.createElement('input')
backbutton.type = "button";
backbutton.value = "Back";
backbutton.onClick = "window.parent.main.history.back()";

var iframe = win.document.createElement('iframe')
iframe.style.width = "100%";
iframe.style.height = "100%";
iframe.style.border = "none";
iframe.src = url
win.document.body.appendChild(backbutton)
win.document.body.appendChild(iframe)
}
</script>

<div class=popup id=pop-div>
   <div id=box class=popup-box>
   <div id=popup-top-wrapper class=popup-top-wrapper>
       <button class=x-button id=popup-x>x</button>
   </div>
   <div class=popup-content-wrapper>
       <h2 class=popup-title>IMPORTANT ANNOUNCEMENT!11!!1</h2>
       <p>&emsp;Important announcement on the future of the site is out! Click the button below or check out the blog to read it.</p>
   <div class=popup-footer>
       <button class=popup-ok-button id=popup-ok>Take me there!</button>
       <button class=popup-no-button id=popup-no>Maybe Later</button>
   </div>   

</div>
   </div>
</div>


<div class="body-wrapper">
    <div class="main">
        <h1 class="text">PB9k</h1>
        <form class="bar" id="searchform">
            <input type="text" autocomplete="off" class="sinput" name="search-bar" id="search-bar" list="searchsuggestions" placeholder="Enter search query or URL.">
            <button aria-label="Submit" type="submit" id="sub">
                <strong>></strong>
            </button>
            <datalist id="searchsuggestions"></datalist>
        </form>
        <h4 class="text" id="motd"></h4>
        <script src="motd.js"></script>    
    <noscript>
            <h4>
                Sorry for the inconvenience. Your browser does not support Javascript, meaning functionality of this website is guaranteed (to not exist).
            </h4>
        </noscript>
    </div>
<script>
// Set the date we're counting down to
var countDownDate = new Date("May 24, 2024 15:35:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>    
    <div class="footer">
	
        <h4 class="text">
            <button class="readme-link" id="feedback">Feedback</button>
	    <button class="readme-link" id="discord">Discord</button>
	    <button class="readme-link" id="spotify">Spotify</button>
            <button class="readme-link" id="reddit">Reddit</button>
            <button class="readme-link" id="mathway">Mathway</button>
	    <button class="readme-link" id="chatgpt">ChatGPT</button>
            <button class="readme-link" id="blog">Blog</button>
           <!-- <button class="readme-link" id="null" onClick="cloak()">Cloak</button>-->


        </h4>
    </div>
</div>
<script src="uv/uv.bundle.js"></script>
<script src="uv/uv.config.js"></script>
<script src="index.js"></script>
<script src="pop.js"></script>
</body>
<script src="telem.js"></script>
</html>
