# things-i-want-done

This repository is a collection of projects and things I would like done, but I don't have the time to get them done myself and I don't see much opportunity for making money. If someone can resolve them or throw an LLM at them, I'm fine with that. It is organized into easy, medium, hard, and good luck tiers. When something is confirmed to have existed or been completed, create a PR removing it from the README.md and put it in the COMPLETED.md along with references and resources related to the task. I will review it and merge it.

## EASY

### Spice extension in Zed IDE

- **Stack:** Spice, Rust, JavaScript, Tree-sitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- Add Spice support, including all these types
  - Circuit Netlists: .cir, .sp, .spi (Standard text files listing components).
  - LTspice: .asc (Schematic), .asy (Symbol), .raw (Simulation Data).
  - Models/Libraries: .mod, .lib, .mdl.
  - NASA SPICE Kernels: .bsp (Binary SPK), .tpc (Text PCK), .tls (Leapseconds).
- Create tree-sitter-spice
- Create a language server

### SDC extension in Zed IDE

- **Stack:** SDC, Rust, JavaScript, Tree-sitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- TCL support exists; however, SDC(Synopsis Design Constraint) files don't have extension support
- Create tree-sitter-sdc or reuse tree-sitter-tcl
- Create a language server

### Bazel extension for Zed IDE

- **Stack:** Bazel, Rust, JavaScript, Treesitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- Bazel doesn't have support; add it

### Perl extension for Zed IDE

- **Stack:** Perl, Rust, JavaScript, Treesitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- Perl doesn't have support; add it

### CUDA extension for Zed IDE

- **Stack:** CUDA, Rust, JavaScript, Treesitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- CUDA doesn't have support; add it

### JSFuck extension for Zed IDE

- **Stack:** CUDA, Rust, JavaScript, Treesitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- JSFuck doesn't have support; add it

### Brainfuck extension for Zed IDE

- **Stack:** CUDA, Rust, JavaScript, Treesitter

- Zed is a newer IDE; therefore, it doesn't have as large or as developed a list of extensions
- Brainfuck doesn't have support; add it

### Terraria Mod Wiki Entries for tConfig mods

- **Stack:** TODO

- Other than Avalon mod, all mods other than Necro(Though shit wiki) don't have a wiki
- So create pages on Terraria Mod Wiki for all mods that are in the archive

### tConfig Documentation

- **Stack:** TODO

- The tConfig wiki hurts to look at, and the ads piss me off
- Set up a new wiki page, something similar to the tModloader GitHub wiki

### Terraria Mod Wiki Entries for tAPI mods

- **Stack:** TODO

- Create pages on Terraria Mod Wiki for all mods that are in the archive other than Exxo Avalon(page already exists)

### tAPI Documentation

- **Stack:** TODO

- The tConfig wiki hurts to look at, and the ads piss me off
- Set up a new wiki page, something similar to the tModloader GitHub wiki

### Terraria Standalone mods, create Wiki pages

- **Stack:** TODO

- Set up a new wiki page on Terraria mod wiki

## MEDIUM

### Terraria Version Control

- **Stack:** C#, Git

- I saw a cool hackathon project where some students were able to build a version control system for Minecraft similar to Git
- It would be nice to have one for Terraria too; it shouldn't just be a basic file difference change
- Should be able to track and revert boss defeats, enemy kills(for bestiary), and any world placement or destruction

### Terratone (Terraria Baritone)

- **Stack:** C#

- Minecraft has this cool thing called [Baritone](https://github.com/cabaletta/baritone) which is a pathfinder bot capable of quiet a lot
- Implement a similar thing into Terraria
- Maybe start with using Fighter AI, and the user can define the target?
- It would be great to see Terraria beat with a bot like this

## Hard

### Agents/MCP for Terraria

- **Stack:** C#, LLMs

- Agents in Terraria 
- Like that one with Minecraft - https://higgsfield.ai/plugins/minecraft
- Look into that guy: emergent garden for Minecraft

### Super Smash Bros. 64, Slippi-like online experience 

- Super Smash Bros. Melee sweaty autists have managed to create Slippi, which brings modern online matchmaking with rollback netcode to melee
- This is pretty cool, but Smash 64 autists should have their own version, so make something similar with matchmaking, replay files, and rollback netcode
- I believe the decompilation and recompilation are completed, so you don't have to worry about assembly that much, so there is a decent starting point

## Good Luck

### Downloader (Downwell mod loader)

- **Stack:** GML, C#, C++

- Downwell is a pretty cool rougelike game
- Roguelikes are generally pretty great for getting extended gameplay through modding
- There is like one large Downwell mod that isn't just simply making some additions to palettes
- Due to Downwell being developed in GameMaker, modding it requires some annoying work with UndertaleModmaker
- GML code can't benefit from dynamically linking code like C# or C++
- Essentially figure out some modding api
- Maybe decompile into C# or C++, and then mod from there
- Maybe use the mobile version as a starting point and get it working on a computer (preferably all platforms), then work on creating a modding API

### Get Terraria versions before Mojo working on macOS and Linux(without Wine)

- **Stack:** C#, Compilers

- Using Windows is a miserable experience, but all old Terraria versions are only on Windows
- Terraria 1.3 had some performance issues on Mac
- When trying to use the properties menu on Steam to play older versions on MacOS and Linux, you can download, but when you launch it tells you this can only be played on Windows
- Somebody managed to make a patch to make Terraria 1.3 work better on Mac, so this could be a good reference
- Possibly decompile, then recompile using Mojo?

- Extension
  - Get tConfig working
  - Get tAPI working
  - Get tModloader pre-Mojo working
