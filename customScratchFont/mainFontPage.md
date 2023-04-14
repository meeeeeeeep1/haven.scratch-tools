<!DOCTYPE html>
<html>
  <head>
    <style>
input[type="text"] {
    font-family : "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size : 12px;
    font-weight : 500;
    text-decoration : rgb(87, 94, 117);
    word-spacing : 0px;
    width: 200px;

}
legend {
    font-family : "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-weight: bold;
  color: #333;

}

 ::placeholder {
    font-family : "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size : 13px;
    font-weight : 500;
 }
body {
  background-color: #f2f2f2;
    font-family : "Helvetica Neue", Helvetica, Arial, sans-serif;
}
#download:hover{
    background-color: #4386e2;

}
.topnav {
                background-color: rgb(77, 151, 255);
                overflow: hidden;
            }

            /* Style the links inside the navigation bar */
            .topnav a {
                float: left;
                text-align: center;
                padding: 14px 16px;
                text-decoration: none;
                font-size: 17px;
                white-space: nowrap;
                color: #fff;
                font-size: .85rem;
                font-weight: bold;
                font-family: "Helvetica Neue","Helvetica",Arial,sans-serif;
            }
            .topnav-image {
    background-color: rgb(77, 151, 255);
    float: left;
    margin-right: 10px;
}

            /* Change the color of links on hover */
            .topnav a:hover {
                background-color: rgb(59, 119, 203);
            }
select {
    font-family: "Helvetica Neue", "Helvetica", Arial, sans-serif;
font-size : 14px;
text-decoration : rgb(87, 94, 117);
white-space : nowrap;
word-spacing : 0px;
    border-radius: 5px;
    background-color : #FAFAFA;
width: 220px;
color : #575E75;
}

label {
    font-family : "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size : 16px;
    font-weight : 700;
    text-decoration : rgb(87, 94, 117);
    word-spacing : 0px;
}
#download {
    position: absolute;
  left: 50%;
  transform: translate(-50%);
        font-family: "Helvetica Neue","Helvetica",Arial,sans-serif;
    text-align: center;
    background-color: #4D97FF;
    color:white;
    font-size: 14px;
    height: 44px;
    width: 300px;
    font-weight: 700;
    border-radius: 8px;
    border: none;
}

    </style>
  </head>
  <body>
    <div class="topnav">
        <image src="https://raw.githubusercontent.com/meeeeeeeep1/haven.scratch-tools/main/customScratchFont/images/H(1).png" alt="Tiny Logo" height="35">
        <a class="active" href="#home">Home</a>
        <a href="#news">Scratch Font Creator</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
    </div> 
        
        <!-- Form Name -->
    <svg id="svg" xmlns="http://www.w3.org/2000/svg" width="450" height="160" stroke="#000" 
        text-anchor="left" font-size="24">
      <g stroke="none">
        <text id="textElement" font-family="Roboto Condensed" x="0" y="43.42">
          ABCDEFGHIJKLMNOPQRSTUVWXYZ
        </text>
      </g>

</form>
    <br>
    <label for="fontfamilyselect">Font Family:</label>
    <select id="fontfamilyselect" onchange="updateFontFamily()">
      <option value="Arial">Arial</option>
      <option value="Arial Black">Arial Black</option>
      <option value="Arial Narrow">Arial Narrow</option>
      <option value="Arial Rounded MT Bold">Arial Rounded MT Bold</option>
      <option value="Avant Garde">Avant Garde</option>
      <option value="Calibri">Calibri</option>
      <option value="Cambria">Cambria</option>
      <option value="Candara">Candara</option>
      <option value="Century Gothic">Century Gothic</option>
      <option value="Comic Sans MS">Comic Sans MS</option>
      <option value="Consolas">Consolas</option>
      <option value="Sans-Serif">Sans-Serif</option>

      <option value="Constantia">Constantia</option>
      <option value="Corbel">Corbel</option>
      <option value="Courier New">Courier New</option>
      <option value="Droid Sans">Droid Sans</option>
      <option value="Franklin Gothic Medium">Franklin Gothic Medium</option>
      <option value="Futura">Futura</option>
      <option value="Garamond">Garamond</option>
      <option value="Geneva">Geneva</option>
      <option value="Georgia">Georgia</option>
      <option value="Gill Sans">Gill Sans</option>
      <option value="Helvetica">Helvetica</option>
      <option value="Helvetica Neue">Helvetica Neue</option>
      <option value="Hoefler Text">Hoefler Text</option>
      <option value="Impact">Impact</option>
      <option value="Lucida Grande">Lucida Grande</option>
      <option value="Lucida Sans Unicode">Lucida Sans Unicode</option>
      <option value="Merriweather">Merriweather</option>
      <option value="Monaco">Monaco</option>
      <option value="Montserrat">Montserrat</option>
      <option value="Myriad Pro">Myriad Pro</option>
      <option value="Noto Sans">Noto Sans</option>
      <option value="Open Sans">Open Sans</option>
      <option value="Optima">Optima</option>
      <option value="Oswald">Oswald</option>
      <option value="Palatino">Palatino</option>
      <option value="Papyrus">Papyrus</option>
      <option value="Segoe UI">Segoe UI</option>
      <option value="Source Sans Pro">Source Sans Pro</option>
      <option value="Tahoma">Tahoma</option>
      <option value="Times New Roman">Times New Roman</option>
      <option value="Trebuchet MS">Trebuchet MS</option>
      <option value="Ubuntu">Ubuntu</option>
      <option value="Verdana">Verdana</option>
      <option value="Webdings">Webdings</option>
      <option value="Wingdings">Wingdings</option>
      <option value="Zapf Dingbats">Zapf Dingbats</option>
      <option value="Baskerville">Baskerville</option>
      <option value="Bodoni MT">Bodoni MT</option>
      <option value="Book Antiqua">Book Antiqua</option>
      <option value="Century">Century</option>
      <option value="Clarendon">Clarendon</option>
      <option value="Didot">Didot</option>
      <option value="Engravers MT">Engravers MT</option>
      <option value="Eurostile">Eurostile</option>
      <option value="Felix Titling">Felix Titling</option>
      <option value="Footlight MT Light">Footlight MT Light</option>
      <option value="Gill Sans MT">Gill Sans MT</option>
      <option value="Harlow Solid">Harlow Solid</option>
      <option value="High Tower Text">High Tower Text</option>
      <option value="Imprint MT Shadow">Imprint MT Shadow</option>
      <option value="Jokerman">Jokerman</option>
      <option value="Lucida Bright">Lucida Bright</option>
      <option value="Mistral">Mistral</option>
      <option value="Old English Text MT">Old English Text MT</option>
      <option value="Perpetua">Perpetua</option>
      <option value="Rockwell">Rockwell</option>
      <option value="Showcard Gothic">Showcard Gothic</option>
      <option value="Stencil">Stencil</option>
      <option value="Symbol">Symbol</option>
      <option value="Times">Times</option>
      <option value="Viner Hand ITC">Viner Hand ITC</option>
      <option value="Wide Latin">Wide Latin</option>
      <option value="Algerian">Algerian</option>
      <option value="Andale Mono">Andale Mono</option>
      <option value="Bauhaus 93">Bauhaus 93</option>
      <option value="Berlin Sans FB">Berlin Sans FB</option>
      <option value="Bookman Old Style">Bookman Old Style</option>
      <option value="Bradley Hand">Bradley Hand</option>
      <option value="Brush Script MT">Brush Script MT</option>
      <option value="Castellar">Castellar</option>
      <option value="Century Schoolbook">Century Schoolbook</option>
      <option value="Colonna MT">Colonna MT</option>
      <option value="Cooper Black">Cooper Black</option>
      <option value="Copperplate Gothic Bold">Copperplate Gothic Bold</option>
      <option value="Copperplate Gothic Light">Copperplate Gothic Light</option>
      <option value="Curlz MT">Curlz MT</option>
      <option value="Futura PT">Futura PT</option>
      <option value="Gadugi">Gadugi</option>
      <option value="Gigi">Gigi</option>
      <option value="Haettenschweiler">Haettenschweiler</option>
      <option value="Harrington">Harrington</option>
      <option value="Informal Roman">Informal Roman</option>
      <option value="Kristen ITC">Kristen ITC</option>
      <option value="Leelawadee UI">Leelawadee UI</option>
      <option value="Lucida Calligraphy">Lucida Calligraphy</option>
      <option value="Magneto">Magneto</option>
      <option value="MV Boli">MV Boli</option>
      <option value="OCR A">OCR A</option>
      <option value="Onyx">Onyx</option>
      <option value="Palace Script MT">Palace Script MT</option>
      <option value="Papyrus">Papyrus</option>
      <option value="Ravie">Ravie</option>
      <option value="Segoe Print">Segoe Print</option>
      <option value="Segoe Script">Segoe Script</option>
      <option value="Segoe UI">Segoe UI</option>
      <option value="Snap ITC">Snap ITC</option>
      <option value="Tunga">Tunga</option>
      <option value="Vladimir Script">Vladimir Script</option>
      <option value="Garamond">Garamond</option>
      <option value="Georgia">Georgia</option>
      <option value="Minion Pro">Minion Pro</option>
      <option value="Open Sans">Open Sans</option>
      <option value="Roboto">Roboto</option>
      <option value="Tahoma">Tahoma</option>
      <option value="Times New Roman">Times New Roman</option>
      <option value="Arial">Arial</option>
      <option value="Helvetica">Helvetica</option>
      <option value="Impact">Impact</option>
      <option value="Comic Sans MS">Comic Sans MS</option>
    </select>
    <input type="text" id="fontfamilyinput" placeholder="Or type name of font here" oninput="updateFontFamily()">
    <br>
    <br>
    <label for="textinput">Custom Text:</label>
    <input type="text" id="textinput" placeholder="Leave box empty for default text" oninput="updateText()"> 
    <br>
    <p></p>
    <p></p>
    <button id="download" onclick="downloadSVG()">Download SVG</button>

    <script>
      function updateFontFamily() {
        var fontSelector = document.getElementById("fontfamilyselect");
        var fontInput = document.getElementById("fontfamilyinput");
        var selectedFont = fontSelector.value || fontInput.value;

        // Use selectedFont to change the font in your SVG or elsewhere
        var textElement = document.getElementById("textElement");
        textElement.setAttribute("font-family", selectedFont);
      }

      // Add event listeners to handle the font input
      var fontInput = document.getElementById("fontfamilyinput");
      fontInput.addEventListener("input", function() {
        var fontSelector = document.getElementById("fontfamilyselect");
        fontSelector.selectedIndex = -1;
      });
      fontInput.addEventListener("keydown", function(event) {
        if (event.keyCode === 13) { // Enter key
          event.preventDefault();
          updateFontFamily();
        }
      });

      function updateText() {
        var textInput = document.getElementById("textinput").value;
        if (textInput.trim() === "") {
          textInput = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        }
        var textElement = document.getElementById("textElement");
        textElement.textContent = textInput;
      }

      function downloadSVG() {
        const svg = document.getElementById('svg').outerHTML;
        const blob = new Blob([svg.toString()]);
        const element = document.createElement("a");
        element.download = "w3c.svg";
        element.href = window.URL.createObjectURL(blob);
        element.click();
        element.remove();
      }
    </script>
  </body>
</html>
