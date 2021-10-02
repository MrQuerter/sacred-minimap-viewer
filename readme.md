# Sacred Minimap Viewer

![demo minimap view](https://raw.githubusercontent.com/MrQuerter/sacred-minimap-viewer/main/demo_minimap_view.png)

# Installation instructions

1. Download zip with minimap viewer files
2. Extract it to a folder of your choosing
3. Extract minimap files (MINIMAP000000.TGA and all the others) from your version of Sacred.
4. Convert them all to .png filetype with 256x256 resolution
5. Paste them to "i" folder inside minimap viewer
6. Open minimap_view.html
7. Wait for it to load all the files (it takes a long time even on ssd drive so be patient)


# Few explanations

This viewer should work with all versions of Sacred 1, but I only had the demo version and gold edition to check.

You can use Sacred Texture Extractor to easily extract minimap files, but be prepared to wait a while since it's not lightning fast and it unpacks everything which takes more space.

You must convert all minimap files to png because otherwise browser wouldn't be able to display them. I recommend using some tool which can handle this for you automatically. Keep in mind that they need to be in 256x256 resolution or else you would need to alter the html file.

In the viewer files there are also included my attempts at discovering how exactly were the minimap files placed in the game since they weren't just located next to each other like normal puzzles. You can use it to make your own version or just alter something that bothers you.

As far as I know none of the browsers allowed me to make a screenshot of whole minimap together since it is too big. The closest to succeed was firefox dev tools, but it was still cut short at 10000x10000 pixels resolution png and the full size is 50900x25235 pixels.

All of the placed minimap files have title attribute so you can hover your mouse over them and know how it is named to more quickly locate it for various reasons.

You can get Sacred from GOG, Steam or other sellers who have box versions.
