<h1>JavaScript Dynamic File Explorer</h1>
<i>This repository contains JavaScript for a dynamically generated file explorer for any GitHub repository.</i>

<h2>Description</h2>
Essentially, this script produces an unordered list of all folders and files in a given GitHub repository. Files automatically have their GitHub blob links attached to them. Folders support different icons for being 'open' (displaying their contents) and 'closed'. Adding specific icons for any file extensions is supported through CSS without the need for modifying the script itself.

<h2>Usage</h2>
Import the <a href="https://github.com/wyndchyme/js-fileexplorer/blob/main/explorer.js">script</a> using the standard <code><script></code> method. Add the contents of the <a href="https://github.com/wyndchyme/js-fileexplorer/blob/main/style.css">stylesheet</a> to your <code>style.css</code> file or import it externally.<br>
Add specific icons for certain file extensions by adding this to your <code>style.css</code>:<br>
  
```
.file-extension a::before {
    background-image: url(/your/image/path/here);
}
```

A sample of this script can be found in the <code>index.html</code> file that uses this repository as an example. You can view this example as a website <a href="https://wyndchyme.github.io/js-fileexplorer/">here.</a>

<h2>Legal</h2>
© wyndchyme 2025. Licensed under the <a href="https://www.apache.org/licenses/LICENSE-2.0">Apache License 2.0</a>.
