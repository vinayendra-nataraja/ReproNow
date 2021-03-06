# ReproNow
An open source tool to capture screen and network instantly helping security engineers reproduce bugs
This is a browser extension to capture Desktop and Network Traffic
- It has a responsive UI for Security Engineers to view and search requests
- Hides the traffic inside a mkv/webm video files
- Works cross browser using extensibility API (currently supports Chrome and Opera, Firefox on roadmap)
- No server interaction, everything on client
- Export requests as cURL
- Store history in Local Storage-

**Options Explained:**
 
    1. Capture network of active and navigated Tabs(Default)
       This option enables the tool to capture the network of the current tab and all the other tabs you navigate to. 
   
    2. Capture Network of most recently activated tab
       This captures the network of only the active tab at that moment. So, as you navigate across tabs, the tool captures            the network of those tabs.
    
    3. Capture Network of only current tab
       Captures the network of the current tab from which the extension was invoked. 
       
    4. Capture of all tabs
       This option enables the tool to capture network of all the tabs in the browser. 
    
__Installation:__
**Chrome**: 
Go to https://chrome.google.com/webstore/detail/repronow/bgnboagkkokloclccjpmamhfijeinnpc and install it directly from the Chrome Store

**Opera:**
We have submitted the extension for approval in the Opera store. Feel free to upload the folder in this repository for Opera.


