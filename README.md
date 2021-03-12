Instalation steps

1: Open your valheim installation folder, something like C:\Program Files (x86)\Steam\steamapps\common\Valheim

2: Backup this folder as this process might screw it up, saves and characters will be fine.

3: in the root of the installation folder run the following commands

```
git init
git remote add origin https://github.com/JaremAndersen/vigilant-chainsaw.git
git fetch
git branch master origin/master
git checkout master
```

To go back to vanilla
```
git checkout vanilla
```
