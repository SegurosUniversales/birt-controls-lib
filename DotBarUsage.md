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

To use the DotBar drag it into a cell in any data powered container [List, Table, Grid, CrossTab].  After dropping the DotBar control into the cell, you will see the DotBar editor.  You can get back to the DotBar editor by either double clicking on the control, or by going to the General tab in the Property Editor.
![http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/dotbar.attach/editor.png](http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/dotbar.attach/editor.png)

Controlling the DotBar is fairly easy, there are just three basic sections.  The general section is first and controls the data and how it will be displayed.<p>
<ul><li>Expression is any expression that evaluates to an Integer.<br>
</li><li>Orientation controls whether the dots will go left to right first or up and down.<br>
</li><li>Wrap Point will control how many dots are on a row or column before they wrap. <p>
<blockquote>(Typically you will use either 5 or 10, numbers that make it easier to compare at a  glance.)<br>
</blockquote></li><li>Designer Display Value only works at design time and controls how many dots show up in your layout view.</li></ul>

<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/dotbar.attach/general.png' />

The shape, color, and size of the symbol can be controlled through the Dot section of the editor.<p>
<ul><li>Spacing controls how much white space exists between each dot<br>
</li><li>Shape controls whether you see a circle, rectangles or triangles.<br>
</li><li>Height & Width control the size of each dot<br>
</li><li>You can also control the fill color and the background color of the dots</li></ul>

<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/dotbar.attach/dot.png' />

By default the DotBar does not display the numeric value.  The number can be shown using the number section.<p>
<ul><li>Position controls whether the number shows up and if it is before or after the dots.<br>
</li><li>Font, Bold, Italic and Color all control the look of the number.<br>
</li><li>Width and Height control how much space will be reserved for the number.<br>
</li><li>Size controls the font size.<br>
You may say why do I have to control Width/Height and Size.  Height/Width are a reservation for how much space you are reserving for the number.<br>
The size is how the number will be.  Future editions of the DotBar may scan ahead through the list of all values to dynamically calculate the Height/Width,<br>
but they are not in this revision of the control.</li></ul>

<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/dotbar.attach/number.png' />