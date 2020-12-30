
<h1>Listening Comprehention</h1>
<p><b>1. Write the vocabulary that you hear in the box provided.</b></p>

<iframe src="https://h5p.org/h5p/embed/1061799" width="922" height="376" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<br>

<p><b>2. Play the song by Rammstein "Du Hast". As the song goes on try to fill in the blanks in the lyrics.</b></p>
  
<iframe width="420" height="345" src="https://www.youtube.com/embed/W3q8Od5qJio">
</iframe>


<iframe src="https://h5p.org/h5p/embed/1078710" width="1090" height="1974" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

ppppppp


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
<p><b>Choose the best game to make the most of you language leraning experience!</b></p>
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
