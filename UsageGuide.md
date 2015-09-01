# Organization #
This project generates two new ReportItem components, the RotatedTextItem and DotBar.

The project is split into two separate plugins:
  * bb-birt-controls
  * bb-birt-controls-ui

You may ask "Why two plugins for one project?"

The answer is if you put UI components into your BIRT plugin, your ReportEngine deployment will not be able to load the plugin.

The reason is that the UI portion of the plugin extension have dependencies on the core UI components.  The core UI components are not packaged in ReportEngine deployments, so if your plugin has those dependencies, it will fail on load.<p>
(one guess how we figured that out...)<br>
<br>
<table>
<tr>
<td>
<blockquote><img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/usage.attach/dotbar.jpg' />
</td>
<td>
<h2><a href='DotBarUsage.md'>DotBar Usage</a></h2>
</td>
</tr>
<tr>
<td>
<img src='http://svn.codespot.com/a/eclipselabs.org/birt-controls-lib/wiki/usage.attach/rotatedtext.jpg' />
</td>
<td>
<h2><a href='RotatedTextUsage.md'>RotatedText Usage</a></h2>
</td>
</tr>
</table>