# SeedCalc
Simple seed calculator to calculate and price your seeds in your stash in Path of Exile!
Written in Python, GUI made with PySimpleGui, compiled by auto-py-to-exe

# How to use
![Screenshot](https://i.imgur.com/Z3JURAD.png)


 - Log-in to your PoE account on pathofexile.com
 - Run script (there will be a popup, that tells you, the script generated default file with seed prices in the same directory where it is)
 - In the first field type in your account name from PoE site
 - In second field type in your current character name (this is for generating message, that people could PM you in game)
 - In third field type in index of stash with seeds. **Careful! Use index, not name of the STASH!** Count it like on the screenshot below! (From top to bottom, or left to right)

![Screenshot](https://i.imgur.com/PreIV74.png)


 - Then click "Get link with data", right after that your browser should open with data. Copy all of it
 - At the end click last button and Done!

If you think that the script dont see your seed, please wait up to 1-2 minutes after you moved seed in your stash (PoE StashAPI must refresh it). If it still didnt listed your seeds, make and issue post on GitHub with pastebin of your copied data and description of problem.

# How to setup your prices of seeds
Simply edit json file "prices" which should be generated after first run of script. Make sure that you set decimal prices using dots (.) instead comma (,).
