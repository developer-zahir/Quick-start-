<div style="text-align:center; margin:10px auto;">
    <img style="margin-left:200px ;" src="./assets/img/download.png" alt="">
    <br><br>
</div>
<p>
    যেকোনো প্রজেক্ট দ্রুত শুরু করার জন্য এই ফাইলটি আমি তৈরি করেছি। প্রতিবার নতুন কোনো প্রজেক্ট শুরু করার সময় এটা আমার কাজটাকে অনেকটা সহজ করে দেয়। একটা বেসিক লেভেল প্রজেক্ট শুরু করার জন্য যা যা দরকার তা সবকিছু এই ফাইলে আছে।
</p>
<p>
    প্রতিবাদ প্রজেক্ট শুরু করার সময় এই ফাইলটি ডাউনলোড করে আমি আমার প্রজেক্ট শুরু করে দেই এতে করে আমার অনেকটা সময় বেঁচে যায়। এই ফাইলে যে সকল ফাইলস লিংক করানো আছে তার একটা লিস্ট নিচে দেয়া হল, আপনারা চাইলে আপনাদের প্রয়োজনে ফাইলটি ডাউনলোড করে নিতে পারেন এতে করে প্রজেক্ট শুরু করার সময় আরেকটা সময় বেচে যাবে
</p>


<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Bootstrap</li>
    <li>JS</li>
    <li>Font Awesome</li>
</ul>

## File structure -

<ul>
    <li>assets
        <ul>
            <li>img</li>
            <li>css
                <ul>
                    <li>style.css (main style file)</li>
                    <li>responsive.css</li>
                    <li>all.min.css (font-awesome)</li>
                    <li>bootstrap.min.css (bootstrap)</li>
                </ul>
            </li>
            <li>sass
                <li>style.scss (main scss file)</li>
                <li>_variable.scss </li>
            </li>
            <li>js
                <ul>
                    <li>bootstrap.min.js (bootstrap)</li>
                    <li>jquery.min.js (jQuery v3.6.0)</li>
                    <li>popper.min.js (bootstrap popper js)</li>
                    <li>script.js (main js file)</li>
                </ul>
            </li>
            <li>fonts</li>
            <li>icon</li>
            <li>font-awesome</li>
        </ul>
    </li>
    <li>index.html</li>
    <li>style.css</li>
</ul>


## Scss file path change - 

<a href="https://github.com/glenn2223/vscode-live-sass-compiler" target="_blank">Live Sass Compiler - Github Repository</a> <br> 
<a href="https://www.w3schools.com/sass/default.php" target="_blank">Learn scss</a>
<pre>
<code>
    "liveSassCompile.settings.formats": [{
        "format": "expanded",
        "extensionName": ".css",
        "savePath": "~/../css"
    }
],
"liveSassCompile.settings.generateMap": false,
</code>
</pre>




## VS Code Basic Setup --

<pre>
    <code>
        {
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "vscode-icons",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.autoSave": "afterDelay",
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.mouseWheelZoom": true,
  "editor.codeLensFontFamily": "Fira Code",
  "workbench.colorTheme": "Night Owl (No Italics)",
  "editor.tabCompletion": "on",
  "editor.formatOnSave": true,
  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "security.workspace.trust.untrustedFiles": "open",
  "window.commandCenter": false,
  "prettier.printWidth": 160,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "explorer.confirmDragAndDrop": false,

  // live sass compiler setting ---
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "~/../css"
    }
  ],
  "liveSassCompile.settings.generateMap": false
}

    </code>
</pre>

<a href="https://fonts.google.com/specimen/Fira+Code" target="_blank">👉 Fira Code Font Download link </a> <br>
<a href="https://github.com/developer-zahir/vs-code-font" target="_blank">👉 OperatorMono </a>


## Extensions -

<ol>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag" target="_blank">Auto Rename Tag</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=wangkechun.html-less-class-completion" target="_blank">HTML-LESS-Class-Completion</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode" target="_blank">Prettier - Code formatter</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme" target="_blank">Material Icon Theme</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer" target="_blank">Live Server</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass" target="_blank">Live Sass Compiler</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion" target="_blank">IntelliSense for CSS class names in HTML</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=solnurkarim.html-to-css-autocompletion" target="_blank">HTML to CSS autocompletion</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula" target="_blank">Dracula Official</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker" target="_blank">Code Spell Checker</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=robertz.code-snapshot" target="_blank">Code Snapshot</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner" target="_blank">Code Runner</a></li>
    <li><a href="https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode" target="_blank">Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets</a></li>
</ol>

## for javascript
<ol>
   <li>Auto Import</li> 
   <li>Code Runner </li> 
   <li>Code Snapshot </li> 
   <li>ES7+ React/Redux/ React-Native snipit </li> 
   <li>ESLint </li> 
   <li>vscode-icons</li> 
   <li>Night Owl ( Theme )</li> 
</ol>


## Essential software for me --- 
<ol>
    <li><a href="http://www.nattyware.com/qwertick.php" target="_blank">Qwertick ( keyboard type effect sound software )</a></li>
     <li><a href="https://www.google.com/search?sxsrf=APwXEdd90EgQv0mW5vtYw1bMSiJsmpej1g:1687609238170&q=desktop+pin&sa=X&ved=2ahUKEwjyoaSp8tv_AhVHS2wGHbG_AukQ7xYoAHoECA0QAQ&biw=1920&bih=890&dpr=1" target="_blank">DeskPins </a></li>
</ol>






## Follow me - 

<div style=" display: flex; gap: 30px;">
    <span style="display:inline-block; margin:15px;"><a href="https://www.facebook.com/developerzahir/" target="_blank">Facebook </a></span>
    <span style="display:inline-block; margin:15px;"><a href="https://twitter.com/developerzahir" target="_blank">Twitter </a></span>
    <span style="display:inline-block; margin:15px;"><a href="https://www.instagram.com/developer_zahir" target="_blank">Instagram </a></span>
    <span style="display:inline-block; margin:15px;"><a href="https://www.linkedin.com/in/developer-zahir/" target="_blank">Linkedin </a></span>
</div>
