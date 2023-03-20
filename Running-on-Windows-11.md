## Instructions on Running on Windows 11
I encountered problems when running the examples on a Windows machine because of the the `make` command. Luckily there is a way around this!

> ❗ **DO FIRST:** follow the *Instructions to Reproduce* from the README section

1. Install [Chocolatey](https://chocolatey.org/)
2. Install [Node.js](https://nodejs.org/en/download)
3. Launch PowerShell as Administrator (right-click then select *"Run as Administrator"*), and run:
```bash
choco install make
choco install wget
npm install touch-cli -g
```
***(Optional)*** make sure the paths are correctly specified in the `Makefile`. You might need to change  "/" to "\". The `Makefile` in this fork has 


