# 🍌 Banana Modules: The Tribe's Shared Knowledge

<img src="https://raw.githubusercontent.com/duongddinh/apelang/main/docs/apelang.png" alt="apelang" width="150"/>

Welcome to the central canopy for all official and community-contributed Apelang modules. This is where the tribe shares its tools, utilities, and wisdom. If you've built a useful .ape file that others might benefit from, this is the place to share it!

## What is This Repository?
This repository is the official source for the apebanana package manager. When you run a command like:
```
apebanana install max
```
The tool comes here to find the max.ape file and downloads it for you to use in your project.

## How to Use a Module
Find a module: Browse the files in this repository to see what's available.

Install it: Use the apebanana command to fetch the module. For example, to get a module named filehandler.ape, you would run:
```
apebanana install max
```
(Note: You leave off the ```.ape``` extension.)

Summon it: In your own Apelang code, use the summon keyword to include the module's functions and variables.
```
# your_script.ape

summon "max.ape"
```

### Now you can use functions defined in the module
```
tree max(4,5)
```

## Available Modules
Here is a list of the tools the tribe has shared so far:

|Module Name |  Description|
| ----------------------- | ----------------- |
|  math| contains min, max, power, even, odd|
|  max| returns the max of 2 numbers|
| min|returns the min of 2 numbers|

A general collection of useful helper functions.

(This list will grow as more apes contribute!)

# 🦍 Installing the ApeLang VS Code Extension

## From Marketplace

Install directly from the Visual Studio Code Marketplace:

🔗 [duongddinh.ape on Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=duongddinh.ape)

### Steps:

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for: `duongddinh.ape`
4. Click **Install**

Or via terminal:

```bash
code --install-extension duongddinh.ape
```


