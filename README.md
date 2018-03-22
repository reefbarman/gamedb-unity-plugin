# GameDB Plugin for Unity
Public repo for documentation and tracking issues for **GameDB (Free/Pro)**

Note: If any of the documentation is unclear or you feel detail is missing, please create an issue and I will attempt to improve it ASAP

[Documentation](https://reefbarman.github.io/gamedb-unity-plugin/)

**GameDB (Free/Pro)** is a plugin that provides an easy to use and powerful game and meta data editor. With this asset your scripts no longer have to use hard-coded references and instead can refer to your database for lists of values, files, prefabs, and other data types. GameDB is designed to produce JSON and associated classes to load and access this data easily within a game. It supports many data types, relationships between tables and hot-reloading to make working with game data easy and intuitive.

Some examples of usages would be for data relating to things like Loot tables, NPC balancing data, Prefab lookups for procedural assets, game configuration, and much much more.</p>

Features include:

* In-editor data management.
* Support for many data types including all basic types, unity types (including prefabs) and enums and table references (Pro only).
* Data saved in a portable JSON format designed to be used by game clients, servers and more.
* In-game editing while playing the game in the editor, allows for balancing of data ar runtime.
* Code generation of C# classes for easy data access in your game code.
* Google Sheets Import/Export (Pro only)
* Support for uploading to server for over the air updates (Pro only)
* Golang server based on S3/DynamoDB and a docker file providing server functionality (Pro only)
* Plus much more...

Support platforms: The plugin should work on all platforms Unity supports! (If it doesn't please open a issue in the tracker above)

A long list of road-map features a planned to provide a full suite of tools to make managing game data easy.

[Roadmap](https://reefbarman.github.io/gamedb-unity-plugin/roadmappage.html)
