# Lamius

----

#### 1.12.2 [Paper](https://github.com/PaperMC/Paper) fork aimed at improving server performance for anarchy servers.

----

#### Used and trusted by:
- [6g6s.org](https://discord.gg/57GW6CKKmp)

## Contributing

*Anyone can contribute. Just follow the below steps!* 

1. [Fork Lamius](https://github.com/ImNotSoftik/Lamiuss/fork)
2. [Build Lamius](https://github.com/ImNotSoftik/Lamiuss#building)
3. [Create Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

Assistant will be given to get pull requests working correctly.

## Server Admins

Lamius uses the same paperclip jar system that Paper uses.  
You can download the latest release of Lamius [here](https://github.com/ImNotSoftik/Lamiuss/releases).   
You can also [build it yourself](https://github.com/ImNotSoftik/Lamiuss#building)

## Building

**Requirements:**

- You need `git` installed, with a configured user name and email.
  On windows you need to run from git bash.
- You need `maven` installed
- You need `jdk 1.8` to decompile and `jdk` 17+ installed to compile (and `jre` 17+ to run)
- Anything else that `paper` requires to build

**If all you want is a paperclip server jar run `./Lamius jar`**

#### Setting up `Lamius-API` and `Lamius-Server`

1. Run `./Lamius patch` in your project root.
2. Run `./Lamius build` to build the respective api and server jars.

#### Creating a patch

Patches are effectively just commits in either `Lamius-API` or `Lamius-Server`.

1. Create commit in `Lamius-API` or `Lamius-Server`.
2. Run `./Lamius rb` in your project root.`
3. Commit patch to `Lamius` repo.

*Modifying commits will also modify its corresponding patch file.*
