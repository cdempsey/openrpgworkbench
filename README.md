# Open RPG Workbench

[Node.js](https://nodejs.org/en/)-based web application for aiding Gamemasters (GMs) and players in
managing, running, and planning their table top role-playing games (TTRPG).

## Development

### Built With

|Component|Supported Versions|Currently|
|---------|-------|---------|
|[Node.js](https://nodejs.org/en/)|>= 14.0.0|14.16.1|
|[npm](https://www.npmjs.com/)|>= 7.0.0|7.9.0|

### Initial Setup

With [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/)
installed and [project's source code](https://github.com/cdempsey/openrpgworkbench/)
cloned locally running `npm run bootstrap`. This will install all of the
project's dependencies and the dependencies for any of the
[Lerna](https://lerna.js.org/) packages under the `./packages` directory.

### Commit Messages

The project uses
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/)
for [git](https://git-scm.com/) commit messages.
[Conventional Commits Cheat Sheet](https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index)
as a succinct guide to making a valid commit message. You an add the `.gitmessage` template
to the project's git configuration by running: `git config commit.template .gitmessage`
  