# Forever-World-Server-Mods
```
packwiz serve -p 8080
java -jar packwiz-installer-bootstrap.jar -g -s server http://localhost:8080/pack.toml
sudo rsync -a --delete --chown=minecraft:minecraft /mc/server-mods/mods/ /mc/nix-minecraft/forever-world/mods/
```
