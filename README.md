<h1 align="center">Slick-Fox</h1>

<h2 align="center">A modern theme for Firefox uses slick animations </h2>

https://user-images.githubusercontent.com/55665282/119282710-b194a080-bc08-11eb-8280-0b8ba16d0d6a.mp4

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



<h3>In Firefox 78+</h3>
<p>You have to create the "ui.prefersReducedMotion" config in about:config and give it a value of 1 to prevent some stuttering in the animation.

<h3>In Firefox 75</h3>
<p>You have to set "browser.urlbar.openViewOnFocus", and "browser.urlbar.update1" to false in about:config to fix a bug regarding a big white urlbar. </p>


