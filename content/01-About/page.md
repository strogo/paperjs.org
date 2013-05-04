<title>About</title>
Paper.js — The Swiss Army Knife of Vector Graphics Scripting.
<image src="paper-js.gif">
Paper.js is an open source vector graphics scripting framework that runs on top of the HTML5 Canvas. It offers a clean Scene Graph / Document Object Model and a lot of powerful functionality to create and work with vector graphics and bezier curves, all neatly wrapped up in a well designed, consistent and clean programming interface.

</image>
<image src="scriptographer.jpg" >Paper.js is based on and largely compatible with <url href="http://scriptographer.org">Scriptographer</url>, a scripting environment for Adobe Illustrator with an active community of scripters and more than 10 years of development.</image>

Paper.js is easy to learn for beginners and has lots to master for intermediate and advanced users.

Paper.js is developed by <url href="http://lehni.org">Jürg Lehni</url> & <url href="http://jonathanpuckey.com">Jonathan Puckey</url>, and distributed under the permissive <node href="/license/">MIT License</node>.
<title>Getting Started</title>

- First of all, take a look at some of our <node href="/examples/">examples</node>.
- <node href="/download/">Download</node> Paper.js or check out the latest version from our <url href="http://github.com/paperjs/paper.js">Github Repository</url>.
- Want to learn Paper.js? Why not start now with one our <node href="/tutorials/">Tutorials</node>.
- If you have any questions or comments, please join the <url href="http://groups.google.com/group/paperjs">mailing list</url>.
- To to stay up to date, <url href="http://twitter.com/paperjs">follow us on Twitter</url>.

<title>Overview</title>
Paper.js is not simply a wrapper around the Canvas, it offers much more:

- A Scene Graph / Document Object Model for vector graphics: Work with nested layers, groups, paths, compound paths, rasters, symbols etc.
- The handling and drawing of these graphic items is automatic and optimised, allowing you to construct or modify your items and styles and leave the drawing commands to Paper.js.
- A well designed and battle hardened Programming Interface.
- There is a good reason for the word Vector in Vector Graphics. Paper.js offers best of breed Vector Mathematics through its core types such as <api Point />, <api Size /> and <api Rectangle />.
- PaperScript, a simple extension of JavaScript allows the scoped execution of scripts without polluting the global scope, the execution of multiple scripts per page in their separate sand-boxed scopes while sharing the library code, and the manipulation of <api Point /> and <api Size /> objects using direct math operations as if they were plain numbers.
- Simple, yet elaborate mouse and keyboard interaction.
- Construct paths and manipulate their curves and segments in very convenient ways.
- Inspect and manipulate the precise bounding box of any item, supporting complicated stroke styles with square ends and miter limits.
- Smoothen curves, simplify path segments by fitting curves through points.
- Simulate dashed strokes which are currently lacking from the Canvas object, at near native drawing speed.
- Most blend modes known from Illustrator and Photoshop supported through emulation in JavaScript: multiply, screen, overlay, soft-light, hard-light, color-dodge, color-burn, darken, lighten, difference, exclusion, hue, saturation, luminosity, color, add, subtract, average & negation.

Read our <node href="/tutorials/">tutorials</node> to learn more about the features of Paper.js.

<title>Browser Support</title>
Paper.js is aimed at modern browsers with support for the Canvas object and EcmaScript 5. Even though in theory it is possible to write code that works in older browsers (Yes Explorer 8 and below, we are looking at you!), we currently do not support them out of the box. Let’s go forward!