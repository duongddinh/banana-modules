# 🍌 Banana Modules: The Tribe's Shared Knowledge

<img src="https://raw.githubusercontent.com/duongddinh/apelang/main/docs/apelang.png" alt="apelang" width="150"/>

Welcome to the central canopy for all official and community-contributed Apelang modules. This is where the tribe shares its tools, utilities, and wisdom. If you've built a useful .ape file that others might benefit from, this is the place to share it!

## Get apelang first!

[apelang](https://github.com/duongddinh/apelang)

```
git clone https://github.com/duongddinh/apelang
```

## What is This Repository?

This repository is the official source for the apebanana package manager. When you run a command like:

```
apebanana install math
```

The tool comes here to find the math.ape file and downloads it for you to use in your project.

## How to Use a Module

Find a module: Browse the files in this repository to see what's available.

Install it: Use the apebanana command to fetch the module. For example, to get a module named math.ape, you would run:

```
apebanana install math
```

(Note: You leave off the `.ape` extension.)

Summon it: In your own Apelang code, use the summon keyword to include the module's functions and variables.

```
# your_script.ape

summon "math.ape"
```

### Now you can use functions defined in the module

```
tree max(4,5)
```

## Available Modules

Here is a list of the tools the tribe has shared so far:

### `math.ape`

| Tribe Name | Description                              |
| ---------- | ---------------------------------------- |
| max        | Returns the max of 2 numbers             |
| min        | Returns the min of 2 numbers             |
| is\_even   | Returns true/false if the number is even |
| is\_odd    | Returns true/false if the number is odd  |
| abs        | Returns absolute value                   |
| negate     | Returns the negative value of a number   |

### `string_utils.ape`

| Tribe Name                | Description                                             | Example Usage                   |
| ------------------------- | ------------------------------------------------------- | ------------------------------- |
| `contains(h, n)`          | True if string `h` contains string `n`.                 | `contains("banana", "ana")`     |
| `sniff_trail(s, p)`       | True if string `s` starts with prefix `p`.              | `sniff_trail("jungle", "jun")`  |
| `guard_trail(s, x)`       | True if string `s` ends with suffix `x`.                | `guard_trail("canopy", "opy")`  |
| `replant(s, o, n)`        | Replaces all occurrences of `o` with `n` in string `s`. | `replant("ooh-aah", "-", " ")`  |
| `echo(s, c)`              | Repeats string `s`, `c` times.                          | `echo("aah ", 3)`               |
| `reverse_chant(s)`        | Reverses the characters in string `s`.                  | `reverse_chant("danger")`       |
| `to_uppercase_shout(s)`   | Converts all letters in string `s` to uppercase.        | `to_uppercase_shout("whisper")` |
| `to_lowercase_whisper(s)` | Converts all letters in string `s` to lowercase.        | `to_lowercase_whisper("SHOUT")` |
| `capitalize_shout(s)`     | Capitalizes only the first letter of string `s`.        | `capitalize_shout("ape")`       |

### `random.ape`

| Tribe Name             | Description                                                   | Example Usage       |
| ---------------------- | ------------------------------------------------------------- | ------------------- |
| `srand(seed)`          | Seed the random number generator                              | `srand(42)`         |
| `rand()`               | Generates a raw random number                                 | `rand()`            |
| `rand_range(min, max)` | Generates a random number within the given range `[min, max]` | `rand_range(1, 10)` |

### `combinatorics.ape`

| Tribe Name     | Description                     | Example Usage  |
| -------------- | ------------------------------- | -------------- |
| `factorial(n)` | Computes factorial of `n`       | `factorial(5)` |
| `nPr(n, r)`    | Computes number of permutations | `nPr(5, 2)`    |
| `nCr(n, r)`    | Computes number of combinations | `nCr(5, 2)`    |

(This list will grow as more apes contribute!)

## 🦍 Installing the ApeLang VS Code Extension

### From Marketplace

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
