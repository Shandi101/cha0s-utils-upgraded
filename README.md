  app.js 

    Node.js: const http = require('http');

     const hostname = '127.0.0.1';
     const port = 3000;

     const server = http.createServer((req, res) => {
       res.statusCode = 200;
       res.setHeader('Content-Type', 'text/plain');
       res.end('Hello World\n');
     });

     server.listen(port, hostname, () => {
       console.log(`Server running at http://${hostname}:${port}/`);
     });# ChA0S Utils [Upgraded]
Upgraded version of my [mod](https://github.com/Passive1st/ChA0S-Utils), but for newer versions and using Fabric instead of Forge modloader

## Commands
|          Command (+ syntax)           |            Description            | Is Added |
|:-------------------------------------:|:---------------------------------:|:--------:|
|            /heal [player]             |            Heal player            |    ❌     |
|            /feed [player]             |            Feed player            |    ❌     |
|           /repair [player]            |   Repair item in player's hand    |    ✅     |
|             /god [player]             |             God mode              |    ❌     |
|           /invsee <player>            |      See player's inventory       |    ❌     |
|                 /fly                  |             Fly mode              |    ❌     |
| /gm <0&#124;1&#124;2&#124;3> [player] |          Change gamemode          |    ❌     |
|                 /day                  |           Set time day            |    ✅     |
|                /night                 |          Set time night           |    ✅     |
|           /tospawn <player>           |       TP to player's spawn        |    ❌     |
|           /vanish [player]            |          Invisible mode           |    ❌     |
|            /thor [entity]             |            Thor player            |    ❌     |
|                 /rain                 |         Set weather rain          |    ✅     |
|                 /sun                  |          Set weather sun          |    ✅     |
|               /thunder                |        Set weather thunder        |    ✅     |
|                /return                |    Return to previous position    |    ❌     |
|       /sudo <player> <command>        | Execute command as another player |    ❌     |
|            /sedo <command>            |    Execute command as console     |    ❌     |

## Items
|     Item     |                      Description                      | Is Added |
|:------------:|:-----------------------------------------------------:|:--------:|
| Death Stick  |          Stick killing player/mod for 1 hit           |    ✅     |
| Drop Pickaxe | Blocks mined with this pickaxe drops in creative mode |    ❌     |
| Thorn Stick  |             Stick shooting lighting bolt              |    ❌     |

## Mechanics
|  Mechanic description   | Is Added |
|:-----------------------:|:--------:|
|   Clear dropped loot    |    ❌     |
| Kick for "bad" nickname |    ❌     |
