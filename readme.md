# Haven Game Engine List <img align=right src="pfp with circle.png" height=200>
This is a list of game engines, and whether or not they are "compatible" with haven, and the reasons for incompatability.

To put it short, typically the main reason for a game engine not being supported is either due to it lacking support to export to a browser, or the fact that it does not store as files on a computer and lacks built-in support for Git Version Control.

If your game engine is not on this list, that does not directly mean it is not supported. (If the site is missing any game engine, please submit an Issue or Pull Request to the sites repository on GitHub: [sometgirldotonline/haven-ge-list](https://github.com/sometgirldotonline/haven-ge-list/))
<details><summary>How to know if your game engine is supported</summary>

<ul>
  <li><b>Saves on your computer:</b> It saves files directly to your computer's hard drive.</li>
  <li><b>Uses separate files:</b> Your images, audio, and code are saved in separate files, rather than bundled into a single file (like Scratch).</li>
  <li><b>Plays in a browser:</b> It lets you export your game to run on a website (look for options like "Web", "HTML5", "WebGL", or "WASM").</li>

</ul></details>

<table>
<thead>
<tr>
<th>Game Engine / Tool</th>
<th>Web Export</th>
<th>Git Compatibility</th>
</tr>
</thead>
<tbody>
<tr supports-web="true" supports-git="true">
<td><strong>Godot</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Saves files as plain text, allowing full code tracking and team collaboration.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Unity</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Requires setting project files to text mode and excluding temporary folders.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>Unreal Engine (5+)</strong></td>
<td>
No Web Export
<details>
<summary>Note 📝</summary>
Built-in web export was dropped in UE4.24+. Requires third-party tools or community plugins.
</details>
</td>
<td>
<strong>Yes</strong><br>
Works with file tracking, but team members cannot edit the same scene at the same time.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GameMaker</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Saves files in readable text formats that track easily.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Construct 3</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Must save project as a folder instead of a single file to work properly with team tracking.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GDevelop</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Multi-file project mode allows team members to work together safely.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Defold</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Built specifically to use readable text files for easy team editing.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Ren'Py</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard text files for script and code changes.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>RPG Maker (MV / MZ)</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Saves as text data files; team members should avoid editing the exact same database file at once.
</td>
</tr>

<tr supports-web="false" supports-git="false">
<td><strong>RPG Maker (VX Ace / XP / older)</strong></td>
<td>No Web Export</td>
<td>
<strong>No</strong><br>
Saves data as locked single files that cannot be merged by teams.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>CryEngine</strong></td>
<td>No Web Export</td>
<td>
<strong>Yes</strong><br>
Tracks source files properly, though large asset files require extra storage setup.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>Flax Engine</strong></td>
<td>No Web Export</td>
<td>
<strong>Yes</strong><br>
Scene and script files are stored as text.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>Stride Engine</strong></td>
<td>No Web Export</td>
<td>
<strong>Yes</strong><br>
Uses standard folder layouts for code and project files.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>PICO-8</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Everything is saved inside a single project file.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Twine</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Entire game is saved inside one single document.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Bitsy</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Saves as a single combined file.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GB Studio</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Saves art and project settings in separate local folders.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Phaser</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard web developer folder setups.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>PlayCanvas</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Primary editor is saved online in the cloud rather than local files.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Babylon.js / Three.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard folder and script setup.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>TIC-80</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Supports multi-file project mode for tracking code changes.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>PuzzleScript</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Uses a single text file for the entire project.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>ct.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Project files are organized cleanly into folders.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>LÖVE (Love2D)</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires using a community wrapper (love.js) to convert games for the web.
</details>
</td>
<td>
<strong>Yes</strong><br>
Plain script files fit directly into team sharing setup.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>libGDX</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard code folder layout.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Bevy Engine</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard code folder layout.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>PixiJS</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard web project structure.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>DragonRuby GTK</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Script files track changes easily.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>AGS (Adventure Game Studio)</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires using the WebAGS community port to export for web browsers.
</details>
</td>
<td>
<strong>Yes</strong><br>
Scripts track easily; team members should coordinate when editing art/sound assets.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>TyranoBuilder</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Local project folder uses text scripts that track well.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Cocos Creator</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard project folder layout.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Macroquad / Raylib</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Pure code files make tracking straightforward.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Narrat</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Plain text config and script files integrate cleanly.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Clickteam Fusion 2.5</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires purchasing the separate HTML5 Exporter DLC module.
</details>
</td>
<td>
<strong>No</strong><br>
Uses a single locked project file that team members cannot edit at the same time.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Scratch / Turbowarp</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires third-party tools like TurboWarp or HTMLifier to turn projects into web files.
</details>
</td>
<td>
<strong>No</strong><br>
Projects are saved as single zipped files.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Excalibur.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Standard web code repository layout.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>bipsi / binksi</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Saves as a single combined file.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Flicksy</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Single page file layout.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Flickgame</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Single page file layout.
</td>
</tr>
</tbody>
</table>
