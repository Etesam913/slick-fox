<h1 align="center"> Slick-Fox</h1>

<h2 align="center">A modern theme for Firefox that has sleek curved tabs, slick animations, and a collapsable url bar. </h2>
<p align="center"><img src="screenshots/demo.gif"></img></p1>

<h3>In Firefox 75</h3>
<p>You have to set "browser.urlbar.openViewOnFocus", and "browser.urlbar.update1" to false in about:config to fix a bug regarding a big white urlbar. </p>


### Steps for applying this configuration
<ol>
  <li>Type about:profiles into your urlbar and go to the page</li>  
  <li>Open the root directory folder specified on the page</li>  
  <li>Inside this folder, create a folder named "chrome"</li>  
  <li>Put the userchrome.css file from this repo into the chrome folder</li>  
  <li>Type about:config into your urlbar and go to the page</li>
  <li>Paste "toolkit.legacyUserProfileCustomizations.stylesheets" into the bar and set its value to true</li>
  <li>Go back to about:profiles and click the restart normally buton</li>
  <li>That should be it!</li>
</ol>
