jquery.lightbox
===============

A lightbox plugin for jQuery

<h2>Examples</h2>
<ul>
	<li><a href="lightbox_api.php">API</a></li>
	<li><a href="lightbox.php">Lightbox (Modal)</a></li>
	<li><a href="lightbox_onload.php">Lightbox (Modal) on page load</a></li>
	<li><a href="lightbox_modeless.php">Lightbox (Modeless)</a></li>
	<li><a href="lightbox_modeless_with_curtain.php">Lightbox (Modeless with curtain)</a></li>
	<li><a href="lightbox_fixed.php">Fixed position</a></li>
</ul>

<p>Popup's z-index should be set higher than all other element's z-index, otherwise those elements will not be covered by overlay curtain. Curtain's z-index is automatically set by js by deducting one from popup's z-index.</p>
<table class="api">
	<tr><th>Properties</th><th>Values: default [optional]</th><th>Description</th></tr>
	<tr><td>modal</td><td>false [true]</td><td></td></tr>
	<tr><td>has_curtain</td><td>true [false]</td><td></td></tr>
	<tr><td>relative_to</td><td>'window', ['parent']</td><td></td></tr>
	<tr><td>top</td><td>center, [any integer value]</td><td></td></tr>
	<tr><td>left</td><td>center, [any integer value]</td><td></td></tr>
	<tr><td>onClosed</td><td>callback function</td><td></td></tr>
	<tr><td>hide_browser_scrollbar</td><td>false, [true]</td><td></td></tr>
	<tr><td>curtain.color</td><td>'#000' [color value in hexadecimal]</td><td></td></tr>
	<tr><td>curtain.opacity</td><td>0.6 [number between 0 and 1]</td><td></td></tr>				
</table>
