Version 1

About:
This is an extension to allow nightmode on sites that don't have an option for it, or have an option that isn't robust enough for your tastes.  I had the idea for this while using edabit to do coding exercises, with my monitor's brightness turned woefully to maximum.

Currently all it does is grab the <body> tag and all the <div> tags, and change them to darker colors.  It's still pretty janky.

Installation:  
To install this extension in chrome or brave, go to chrome://extensions (or brave://extensions); you will need to enable developer mode, which can be done by clicking on the tickbox on the upper right of the browser window.  Once you download the extension folder, select the "Load Unpacked" button on the top lefthand corner of the page and navigate to the extension folder in your file browser.  Select the folder itself; no need to navigate to a subfolder or any of the files.  From there, you should be able to simply click the extension, and it will change all <body> and <div> tags to a different background color.

Advanced:
Admittedly the default colors are a little gaudy and I'm not sure why I decided on those.  If you want to change the colors, they're in functions inside of the content.js file.  Go nuts.

Known issues:
Like I said, this code is kind of jank as heck.  It breaks on both youtube and twitch, and I'm sure many more pages, but those are the only two that I tested it on that I found it to break on.
No way to change page back to original colors without refreshing the page.
Navigating to any other page on the same domain does not retain the color changes.
No way to save themes for future use.
Probably a million other things it's literally just two little functions they can't solve all the woes of the world.

Attributions:

Attributions:  Most of the code in this extension is based on a video from a tutorial series by Coding Train on youtube; the link is enclosed below.
https://www.youtube.com/watch?v=ew9ut7ixIlI

Nightmode png drawn by me.