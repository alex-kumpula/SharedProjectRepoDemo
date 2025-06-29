# Group Project Example Template

The idea here is to have all the games exist in this monorepo as git submodules, meaning that each game is its own repo, and we can add those repos to this main repo.

If we specify that all game-repos must have a web build and an index.html at their root level, then we can potentially use things like Unity Webview to display these games within a launcher-type game with hopefully minimal hassle. Still need to see if this would work in practice though.
