# fix-for-100vh-problem-in-mobile-webkit
<p>Problem statement -</p>
<ul><li>all the browsers have a top menu when you load the page (showing the address bar for example) which slide up when you start scrolling the page.</li>
<li>100vh sometimes is calculated only on the visible part of a viewport, so when the browser bar slide up 100vh increases (in terms of pixels).</li>
<li>all layout re-paint and re-adjust since the dimensions have changed.</li><li>this gives a bad jumpy effect for user experience.</li></ul>
<p>Final output -</p>
<ul><li>this approach prevent re-paint and re-adjust of dimensions on mobile webkit 100vh.</li></ul>
