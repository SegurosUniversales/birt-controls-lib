<table>
<tr>
<blockquote><td valign='top'>
<h1>Installation</h1>
The first step is to insure that the plugins have been installed on your system.  If you look in the palette view you should see both the DotBar and the<br>
RotatedText control listed at the end of the ReportItems section.  (see right).</blockquote>

<blockquote>If you do not see the controls, then there is an issue in your plugin installation.  Please verify that the both the:<br>
</blockquote><ul><li>birt.controls.jar<br>
</li><li>birt.controls.ui.jar<br>
</li></ul><blockquote>Are available in the $ECLIPSE_HOME/plugins directory of your application.<br>
</td>
<td>
<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/usage.attach/palette.png' />
</td>
</tr>
</table></blockquote>

To use the RotatedText drag it into a cell in any data powered container [List, Table, Grid, CrossTab].  After dropping the RotatedText control into the cell, you will see the RotatedText editor.  You can get back to the RotatedText editor by either double clicking on the control, or by going to the General tab in the Property Editor.<p>
<ul><li>Expression will show the result of any valid BIRT Expression<br>
</li><li>Angle is the angle that the text will appear at.<br>
</li><li>Font, Size, Style, and Color apply to the text from the expression.<br>
</li><li>Wrap Point controls the point at which the text will wrap.<br>
</li><li>Link URL allows you to create a hyper link for the control.<br>
<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/rotated.attach/editor.png' /></li></ul>
