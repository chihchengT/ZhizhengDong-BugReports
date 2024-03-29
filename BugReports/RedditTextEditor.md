---
name: Bug report
about: A report about a bug in text editor of Reddit. 
title: 'Reddit text editor'
labels: 'Reddit'
assignees: ''

---

**Software**

Reddit

**Bug Description**

Unable to accurately enter text content in text editor using Chinese input method.

**Steps to Reproduce**
1. Open the browser and go to reddit frontpage, 'www.reddit.com'. 
2. Click on 'Create Post' in the right side panel. 
3. Click on the Text editing area.
4. Swith the input method editor (IME) of Windows OS to Microsoft Pinyin IME for simplified Chinese. 
	
	if the IME isn't installed in your OS. Please follow the steps: 
	- Press keys 'windows'+'I' to open 'Settings' of the OS.
	- Click 'Time & Language'.
	- Click 'Language & region'.
	- Click 'Add a language' in Prefered languages.
	- Find and click 'Simplified Chinese, China'.
	- Install the IME following the guide.
	
5. Make sure to turn on the Chinese mode of the IME. See Screenshot 1.
6. Type in letters whatever you like using the IME. See Screenshot 2.
7. Press 'Space' or 'Enter' to confirm the input in IME.
8. See the bug. See Screenshot 3.

**Expected behavior**
The text editor should only show what I type in the IME after confirming the input.

**Screenshots**
1. Languagesetting ![LanguageSetting](https://github.com/chihchengT/ZhizhengDong-BugReports/blob/9cdf81714a0ff005e6c27978e33128c47e3d8e0d/Image/LanguageSetting.png)
2. TypeinIME ![TypeinIME](https://github.com/chihchengT/ZhizhengDong-BugReports/blob/9cdf81714a0ff005e6c27978e33128c47e3d8e0d/Image/TypeinIME.png)
3. Bug ![Bug](https://github.com/chihchengT/ZhizhengDong-BugReports/blob/9cdf81714a0ff005e6c27978e33128c47e3d8e0d/Image/RedditBug.png)

**Desktop:**
 - OS: [Microsoft Windows 11 Home Chinese version 10.0.22631]
 - Browser: [Firefox 123.0.1]

**Additional context**
Reprot time: 2024-03-29
