# Good Luck

## Downloader (Downwell mod loader)

- **Stack:** GML, C#, C++

- Downwell is a pretty cool rougelike game
- Roguelikes are generally pretty great for getting extended gameplay through modding
- There is like one large Downwell mod that isn't just simply making some additions to palettes
- Due to Downwell being developed in GameMaker, modding it requires some annoying work with UndertaleModmaker
- GML code can't benefit from dynamically linking code like C# or C++
- Essentially figure out some modding api
- Maybe decompile into C# or C++, and then mod from there
- Maybe use the mobile version as a starting point and get it working on a computer (preferably all platforms), then work on creating a modding API

## Get Terraria versions before Mojo working on macOS and Linux(without Wine)

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
