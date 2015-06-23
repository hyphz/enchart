# Enchart 

__Letter finder for the Enchant Puzzle__

This is a simple JavaScript program to help with the process of finding the location of words in the Enchant Puzzle.

__What's the Enchant Puzzle?__ An Armchair Treasure Hunt devised by recording artist Emilie Autumn, and still infamously unsolved after more than ten years. While the puzzle is no longer distributed, the prize is claimed to still exist and be winnable.

__How can I get the Puzzle?__ The Enchant Puzzle itself is _not_ included in the repository because it is copyrighted. The only official way to get it is to purchase the Traitor Records recording of Enchant, which is _not_ the current printing; it may require eBay. 

__What about the music?__ The Enchant album on which the puzzle is based, which supposedly contains some clues, is available on Spotify and other streaming services.

__How do I use this?__ Once you have a good quality scan or photo of your Enchant Puzzle, simply save it in the same directory under the name _enchantall.bmp_ and then open the HTML file. If the format is not .bmp, you may need to edit the img tag at the top of the html file. This can also be edited to change the pixel offset of the image if there's fluff at the sides of your scan. Changing the size will not work, because the script will draw the letter highlights in the wrong places.

Once you've done that, type the word you want to find in the box at the top right. All the occurrences of each letter will be highlighted with a different color box based on the position of the letter in the word. Also, the script will attempt to draw lines between the letters of the word, based on the closest letter. (This may not always be the most logical choice; unfortunately, trying to make the script draw all possible paths for a word quickly makes the output unreadable.)

The "treat U and V as equal" box, if checked, will cause U and V to be treated as the same letter for the purpose of searching the puzzle; this is hinted at by the opening sonnet. The "emboss letters" box will overlay the letter at each found location on top of the graph; this may be useful if it's becoming too hard to read the scan underneath the graph.



