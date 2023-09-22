A bookmark extension for your videos
Title: YouTube Bookmarker - Effortlessly Bookmark and Annotate YouTube Videos

Introduction:
YouTube Bookmarker is a powerful Chrome extension that enhances your YouTube viewing experience by providing a seamless way to bookmark and annotate important moments in videos. With this intuitive tool, you can easily save personal timestamp annotations for future reference, edit them as needed, and export all your video timestamp information as JSON. Never lose track of your favorite video moments again with YouTube Bookmarker!

Key Features:

1. Bookmark and Annotate:
YouTube Bookmarker allows you to add personalized timestamp annotations to any YouTube video. Simply click the "B+" button or the Ctrl+B shortcut to add a bookmark timestamp. You can edit the description within the popup. 

2. Seamless Integration:
Once installed, YouTube Bookmarker seamlessly integrates into your YouTube interface, where you can see all your timestamps by clicking on the popup. 

3. Edit and Organize:
The extension provides a comprehensive annotation management system, allowing you to easily edit and organize your saved timestamps. You can update the descriptions of existing annotations and delete any unnecessary ones. 

4. Export and Backup:
Never worry about losing your valuable timestamps again. YouTube Bookmarker enables you to export all your video timestamp information as JSON with just a few clicks. This feature serves as a reliable backup, ensuring your annotations are securely stored and can be easily imported or shared across different devices.

5. Intuitive User Interface:
The extension boasts a user-friendly interface that is both visually appealing and easy to navigate.

Troubleshooting issues: 

- If you don't see a popup notification, just refresh the page and try again. If anything goes wrong, just refresh the web page or even the extension. Your data will still stay intact.
- Keep in mind there is a 100 kilobyte limit for timestamp storage, since timestamps should sync across google accounts. That's about 200 timestamps across all videos, So make sure to copy any bookmarks you have using the "Export JSON" button, and visit the bookmark table website I created to ensure you never lose your bookmarks even when you run out of storage. Then you can delete the bookmarks, now that you've saved them, and free up some more storage for more bookmarking. Here is the site: https://ytbookmarkertable.netlify.app/


Conclusion:
YouTube Bookmarker is a game-changing Chrome extension that empowers YouTube users to take control of their video-watching experience. By providing an effortless way to bookmark and annotate YouTube videos, this extension allows you to save, edit, and organize personalized timestamps. YouTube Bookmarker is the ultimate companion for anyone seeking to enhance their YouTube journey. Install YouTube Bookmarker today and elevate your video-watching experience to new heights!


-  1.0.1 : bug fix. where ctrl + b shortcut would not activate normally on other websites, preventing bolding. Moved ctrl + b shortcut to only content script and removed global keyboard shortcut. 
- 1.0.2 : bug fix. Seek to timestamp functionality was not working, only the modal opened up, so prevented DOM propagation and fixed it
- 1.0.3 : bug fix. Moved over from sync storage to local storage. 
- 1.0.4 : bug fix. No longer have to refresh for things to work. I moved all url and video getting logic to content script only.# ChromeExtensionForYoutubeBookmark
ChromeExtensionForYoutubeBookmark
