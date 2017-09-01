# GameDB Plugin for Unity
Public repo for documentation and tracking issues for **GameDB (Free/Pro)**

Note: If any of the documentation is unclear or you feel detail is missing, please create an issue and I will attempt to improve it ASAP

[Usage Guide](../../wiki)

[API Reference](../../wiki/API-Reference)

[Google Sheets Usage (Pro version only)](../../wiki/Google-Sheets-Import-Export)

**GameDB (Free/Pro)** is a plugin that provides an easy to use and powerful game and meta data editor. With this asset your scripts no longer have to use hard-coded references and instead can refer to your database for lists of values, files, prefabs, and other data types. GameDB is designed to produce JSON and associated classes to load and access this data easily within a game. It supports many data types, relationships between tables and hot-reloading to make working with game data easy and intuitive.

Some examples of usages would be for data relating to things like Loot tables, NPC balancing data, Prefab lookups for procedural assets, game configuration, and much much more.</p>

Features include:

* In-editor data management.
* Support for many data types including all basic types plus enums, prefabs, and table references.
* Data saved in a portable JSON format designed to be used by game clients, servers and more.
* In-game editing while playing the game in the editor, allows for balancing of data ar runtime.
* Code generation of C# classes for easy data access in your game code.
* Google Sheets Import/Export (Pro only)
* Support for uploading to server for over the air updates (Pro only)
* Golang server based on S3/DynamoDB and a docker file providing server functionality (Pro only)
* Plus much more...

A long list of road-map features a planned to provide a full suite of tools to make managing game data easy.

[Roadmap](../../roadmap)
