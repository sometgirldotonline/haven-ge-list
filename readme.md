# Haven Game Engine List <img align=right src="pfp with circle.png" height=200>

This is a list of game engines, and whether or not they are "compatible" with Haven, and the reasons for incompatibility.

To put it short, typically the main reason for a game engine not being supported is either due to it lacking support to export to a browser, or the fact that it does not store projects as usable files on a computer and lacks suitable support for Git Version Control.

Git compatibility does not necessarily require assets to be stored in separate files. Tools such as PICO-8 are still considered Git-compatible because their project files are stored in a text-based format that Git can meaningfully track. The important distinction is whether the project can reasonably be stored and versioned in a Git repository.

If your game engine is not on this list, that does not directly mean it is not supported. (If the site is missing any game engine, please submit an Issue or Pull Request to the site's repository on GitHub: https://github.com/sometgirldotonline/haven-ge-list/)

<details><summary>How to know if your game engine is supported</summary>

<ul>
  <li><b>Saves on your computer:</b> It saves the project files directly to your computer's hard drive.</li>
  <li><b>Uses a Git-compatible project format:</b> Your project can be reasonably stored and versioned using Git. Projects do not necessarily need separate files for every asset; text-based single-file projects can still be compatible.</li>
  <li><b>Plays in a browser:</b> It lets you export your game to run on a website (look for options like "Web", "HTML5", "WebGL", or "WASM").</li>
</ul>

</details>

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
Uses a Git-friendly project structure with text-based project and scene files.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Unity</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Supports text-based project serialization, allowing project files to be tracked with Git.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>Unreal Engine (5+)</strong></td>
<td>
No Web Export
<details>
<summary>Note 📝</summary>
Built-in HTML5 export was removed from Unreal Engine. Third-party/community solutions exist, but there is no official built-in web target.
</details>
</td>
<td>
<strong>Yes</strong><br>
Project files can be tracked using Git and Unreal provides source-control support.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GameMaker</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses a Git-compatible project structure and supports source control workflows.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Construct 3</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Projects can be saved as folders containing files that can be tracked with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GDevelop</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Projects can be stored locally as files and tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Defold</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses text-based project and game files designed to work well with version control.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Ren'Py</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard text files for scripts and project data, making Git version control straightforward.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>RPG Maker (MV / MZ)</strong></td>
<td>Web Export Supported</td>
<td>
<strong>No</strong><br>
Although many project files use text-based formats, important project data is stored in large database files that are not practical for the Git workflow required by Haven.
</td>
</tr>

<tr supports-web="false" supports-git="false">
<td><strong>RPG Maker (VX Ace / XP / older)</strong></td>
<td>No Web Export</td>
<td>
<strong>No</strong><br>
Uses proprietary project and data formats that are not practical for the Git workflow required by Haven.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>CryEngine</strong></td>
<td>No Web Export</td>
<td>
<strong>Yes</strong><br>
Project and source files can be stored and tracked using Git. Large binary assets may require additional Git storage considerations.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Flax Engine</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Project, scene, and script files can be stored and tracked using Git.
</td>
</tr>

<tr supports-web="false" supports-git="true">
<td><strong>Stride Engine</strong></td>
<td>No Web Export</td>
<td>
<strong>Yes</strong><br>
Uses a standard project folder structure with project and source files that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>PICO-8</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
PICO-8 cartridges can be saved as text-based <code>.p8</code> files. Although code, graphics, maps, and music are created within PICO-8, the resulting source file can be meaningfully tracked with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Twine</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Twine projects can be stored in text-based formats such as Twee, allowing them to be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Bitsy</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Bitsy game data can be stored as text and tracked using Git, even though the game is authored within the Bitsy editor.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>GB Studio</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses a local project structure with project data and assets stored in files that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Phaser</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard web development files and folder structures that work naturally with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>PlayCanvas</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Supports version control workflows and provides tools for working with project files outside of the online editor.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Babylon.js / Three.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard web development files and folder structures that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>TIC-80</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Supports text-based cartridge files that can be stored and tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>PuzzleScript</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Games are represented as plain-text PuzzleScript source files, making them straightforward to track with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>ct.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Projects are stored locally in a folder structure that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>LÖVE (Love2D)</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires using a web port such as love.js to run LÖVE games in a browser.
</details>
</td>
<td>
<strong>Yes</strong><br>
Uses normal source code and asset files that can be stored and tracked with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>libGDX</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses a standard source-code and asset folder structure suitable for Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Bevy Engine</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses a standard Rust/Cargo project structure that works naturally with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>PixiJS</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard JavaScript/TypeScript project files and folder structures.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>DragonRuby GTK</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses source files and project assets that can be tracked using Git.
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
Project and source files can be stored and tracked using Git. Binary art and sound assets can also be tracked, although they cannot be meaningfully merged.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>TyranoBuilder</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Projects are stored locally and contain source and project files that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Cocos Creator</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses a standard local project folder structure designed to work with version control systems.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Macroquad / Raylib</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Code-based projects use standard source files and assets that can be tracked directly with Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Narrat</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard source, configuration, and asset files that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Clickteam Fusion 2.5</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Requires the separate HTML5 Exporter.
</details>
</td>
<td>
<strong>No</strong><br>
Uses a proprietary project format that is not practical for the Git workflow required by Haven.
</td>
</tr>

<tr supports-web="true" supports-git="false">
<td><strong>Scratch / TurboWarp</strong></td>
<td>
Web Export Supported
<details>
<summary>Note 📝</summary>
Scratch projects can be converted to browser-playable games using tools such as TurboWarp.
</details>
</td>
<td>
<strong>No</strong><br>
Projects are stored as <code>.sb3</code> packages containing the project and its assets together rather than as a Git-friendly project structure. Git can store the package, but it cannot meaningfully track individual project components or changes inside it.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Excalibur.js</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Uses standard JavaScript/TypeScript source files and web assets that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>bipsi / binksi</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Project data can be represented as text and stored in Git, even though the game is authored within the editor.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Flicksy</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Project data is stored in a text-based format that can be tracked using Git.
</td>
</tr>

<tr supports-web="true" supports-git="true">
<td><strong>Flickgame</strong></td>
<td>Web Export Supported</td>
<td>
<strong>Yes</strong><br>
Project data can be stored and versioned using Git.
</td>
</tr>

</tbody>
</table>
