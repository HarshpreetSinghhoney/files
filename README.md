Step 1: Download the zip file named "files" 
        Now Extract this files in one folder
Step 2: Load the Extension in Chrome
1: Open Google Chrome
2: Type chrome://extensions/ in the address bar and press Enter
3: In the top-right corner, enable "Developer mode" (toggle the switch)
4: Click the "Load unpacked" button that appears
5: Navigate to and select your extention folder which you just extract from the zip file

Step 3: Verify Installation
1: You should see your extension "Video Source Finder" appear in the extensions list
2: The extension icon should appear in your Chrome toolbar (if not, click the puzzle piece icon to see all extensions and pin it)
3: Step 4: Using the Extension
4: Navigate to a webpage with videos
5: Click the extension icon in your toolbar
6: The green "Find High Quality Video" button should appear in the top-right corner of the webpage
7: Click the button to search for video sources If a video source is found, it will open in a new tab,Click the extension icon again to remove the button Troubleshooting

If the extension doesn't work:

1: Check the extension page (chrome://extensions/) for any error messages
2: Right-click the extension icon and select "Inspect popup" to see console errors
3: Open Chrome DevTools (F12) to check for any JavaScript errors

Updating the Extension

1:If you make changes to the code:
2:Go back to chrome://extensions/
3:Find your extension
4:Click the refresh icon to reload it
5:Refresh any tabs where you want to use the updated extension
Remember that this extension is specifically looking for videos that use the pattern html5player.setVideoUrlHigh. You might need to modify the regex in content.js if you're trying to find videos with a different format.
