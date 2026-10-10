# Achievement Hub game database

Achievement definitions for PC games that never had achievements (or lost
them), used by the Achievement Hub overlay and desktop app.

- `index.json` lists every game with its file name and SHA-256; the app
  downloads a definition when its hash changes.
- `definitions/<game>.toml` is one game: which exe builds it applies to,
  its achievements (names, descriptions, points, many taken from the game's
  console release), and the conditions that unlock them (game memory or
  engine data).

Contributions of new games or mapped conditions are welcome.
