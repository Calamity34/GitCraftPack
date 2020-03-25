# GitCraftPack
A minecraft datapack made by contributors!

## Requirements
* git installed on your machine

On Linux: `sudo apt install git` (or the alternative, depending on your package manager)
On Windows and MacOS: Go to https://git-scm.com and download and install it from there

## How to contribute
1. Fork the repository
2. Open up the Terminal
3. `cd` your way into your working folder
4. Do `git clone https://github.com/YourUsername/GitCraftPack.git && cd GitCraftPack` (that will create a new folder)
5. Checkout to a new branch via `git checkout -b BranchNameHere`
6. Work on the additions...
7. Commit your changes using a command `git add . && git commit -m "Your message here" && git push`
8. When done - go back to the repository website and you will (probably) see a button that says "Compare and Pull Request". Click on it.
9. That will take you to the PRC (Pull Request Creation) page, where you input:
* Title: Short description of what you did
* Description: Additional info if needed
On the right sidebar:
* Label: Short mark of what you did (a new feature, fixed a bug, etc.)
* Linked Issues: if any happen to be that could be fixed with this request
10. After that, click the "Create Pull Request" button to create it
11. Profit! Now await for my review where I either approve your request or request additional changes!

## How to use the datapack
Well, first of all it depends where did you clone your repository fork.
If you cloned it into the `.minecraft/saves/WorldName/datapacks/` then i congratulate you, you can hop into that world and start using the datapack! If you cloned it somewhere else, well, you will need to clone my repository edition into the /datapacks/ folder using:
`cd ?/.minecraft/saves/WorldName/datapacks && git clone https://github.com/Calamity34/GitCraftPack.git`
That will make the datapack ready for usage in your world!

## File Adding Info
Please leave a comment `# just like this` if you have made a function for people to know that you have made this part. If you have made a json file, leave your mark in `credits.md` at /data/git/credits.md

### Additional info
1. USE THE DATAPACK ONLY IN VERSION 1.14.4 BECAUSE OF VARIOUS THINGS
2. If you install the datapack while the world is open, you must do `/reload` ingame to reload the datapacks.
3. Regularly do `cd [All the way to the GitCraftPack folder] && git fetch && git pull` to keep the datapack fresh
4. The pull request templates will be added soon, so keep an eye out!

Feel free to ask me any question on my Twitter `https://twitter.com/_TheCalamity_` and Discord `Calamity#6480`!