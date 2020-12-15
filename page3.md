
<style>
.iframe-container {
  position: relative;
  width: 100%;
  overflow: hidden;
  padding-top: 56.25%; /* 16:9 Aspect Ratio */
}

.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 75%;
  height: 75%;
  border: none;
  margin-left: auto;
  margin-right: auto;
}


@media screen and (max-width: 800px) {
  .responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  border: none;
}
}

</style>

<h1>Embedded Language Game</h1>
<p>Use this flashcards to practise vocabulary from this website. Than you can also play games, which accompany these flashacrds for some fun learning experience!</p>
<p>You can also create you own study sets, on the <a href="https://www.cram.com/">Cram website</a></p>

<p>Select the game type from the dropdown to try it:  
  <select name="" id="list" onclick="loadFrame()">
    <option value="shooter">Phrases Shooter Game</option>
    <option value="matching">Phrases matching game</option>
  </select>
</p>

    
  <div class="iframe-container">
<iframe class="responsive-iframe" id="ifrm" src="https://www.cram.com/flashcards/games/jewel/flashcards-11858303">
  <p>Your browser does not support iframes.</p>
  </iframe>
  </div>
  
<p><a href="https://raw.githubusercontent.com/martinbarge/templatetest/main/games.md">Get the code for this page.</a></p>

<script>
function loadFrame() {
  let e = document.getElementById("list");
  let url = e.options[e.selectedIndex].value;
  
  if (url == "shooter"){
  let gameUrl = "https://www.cram.com/flashcards/games/stellar-speller/flashcards-11858303";
  document.getElementById("ifrm").src = gameUrl;
  }
  
  if (url == "matching"){
  let gameUrl = "https://www.cram.com/flashcards/games/jewel/flashcards-11858303";
  document.getElementById("ifrm").src = gameUrl;
  }
}
</script>
