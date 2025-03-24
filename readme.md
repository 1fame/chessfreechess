# Rapport de partie gratuit

<br><br>
Analyser une partie en entrant un PGN, ou en connectant son compte chess.com ou lichess.org

## Compiler localement
### Prérequis
- Node.js 20.x runtime or later.
- TypeScript package installed globally.

### Compiler
- `git clone` mon repository
- `npm i` pour installer les dépendances 
- entrer un port dans index.ts 
- 'npm.start' puis taper localhost:port en activant developper tools pour lancer l'appli web localement (j'ai testé que chrome).

### NPM Scripts
- `npm start` - Compiles TypeScript and starts the webserver.
- `npm run build` - Compiles TypeScript.
- `npm run test` - Generates reports from some sample evaluations for classification testing at `src/test/reports`.

## Running in Docker
### Prerequisites
- Docker installed on the server

