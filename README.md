# Frontier

A Scythe clone written with Phaser Game Framework and served vía a Rails backend

# Development Environment

This repository is setup to use VS Code's Remote Containers extension. So first open the repository in the remote container.

### Setup Database
```shell
rails db:setup
```

### Initialize server
```shell
rails s -b 0.0.0.0 -p 3000
```

### Initialize Javascript build watcher
```shell
yarn build --watch
```

### Initialize CSS build watcher
```shell
yarn build:css --watch
```
