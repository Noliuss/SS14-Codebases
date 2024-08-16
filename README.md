
<p align="center">
	<h2 align="center">
		Graph tree of <a href="https://spacestation14.com">SS14</a> builds codebases
	</h2>
	<p align="center">
		Origin:
		<a href="https://github.com/CthulhuOnIce/SS13-Codebases">
			CthulhuOnIce/SS13-Codebases
		</a>
	</p>
</p>

<p align="center">
	<!--
		Static Badges
	-->
	<a href="https://graphviz.org/">
		<img alt="Made in Graphviz"
		src="./.github/static/Made_in-Graphviz-30638e.svg"/>
	</a>˙
	<a href="https://code.visualstudio.com/">
		<img alt="Made in VS Code"
		src="./.github/static/Made_in-VS_Code-1f425f.svg"/>
	</a>˙
	<a href="https://opensource.org/licenses/MIT">
		<img alt="MIT License"
		src="./.github/static/License-MIT-yellow.svg"/>
	</a>
	<br>
</p>

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Display graph tree](#display-graph-tree)
- [For contributors](#for-contributors)

## Description

A [DOT graph](https://en.wikipedia.org/wiki/DOT_(graph_description_language)) of the family tree of [Space Station 14](https://spacestation14.com) builds codebases.

## Display graph tree

<details>
	<summary><b>[ Show graph of builds ]</b></summary>
	<a href="./out/tree.svg?sanitize=true">
		<img alt="Graphviz graph" src="./out/tree.svg?sanitize=true">
	</a>
	<b>Compiled: Check auto-generated datetime <a href="./out/compile_datetime.txt/">here</a></b>
	<br/>
</details>

## For contributors

If you want to add repository to the roadmap, go to <a href="./src/tree.dot/">the tree file</a>, scroll down until you see a list of servers, then add your server like that:

		"Fork's upstream"           -> "Fork's name" // added by: your username

No need to build it, github makes it automatically when your PR gets merged. Please mention what you changed in the description of your PR.
