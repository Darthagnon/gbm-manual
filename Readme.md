# Offline Manual for [Game Backup Monitor](http://mikemaximus.github.io/gbm-web/)

### Last updated: GBM v1.2.4, Manual: November 27, 2020

PC games have an annoying habit of saving your countless hours of progress anywhere and everywhere on your system. A lot of them also only keep one copy of your gamesave.

Game Backup Monitor is the solution: an excellent tool to backup and restore gamesaves for games on your PC.

It has grown in features over the years, and I saw a need for offline documentation and instructions on how to use this powerful tool.

**Note:** Newer versions of Windows 10 might not like the unsigned CHM (Windows Help) file. To fix this, ```Right Click```>>```Properties```>>```General```>>```Security: Unblock``` 

## Building and updating this manual

1. I used M$ Edgium Dev (any browser should do) to ```Ctrl```+```S``` Save the following official GBM webpages as split HTML:
 - Rendered [Readme.md from the GitHub](https://github.com/MikeMaximus/gbm)
 - [About](http://mikemaximus.github.io/gbm-web/about.html)
 - [Contribute](http://mikemaximus.github.io/gbm-web/contribute.html)
 - [Manual](http://mikemaximus.github.io/gbm-web/manual.html), split into pages
	 - [Using Task Scheduler to start Game Backup Monitor as Administrator](http://mikemaximus.github.io/gbm-web/gbm_task_scheduler.html)
 - [F.A.Q](http://mikemaximus.github.io/gbm-web/faq.html)
	- [Game Launcher F.A.Q](http://mikemaximus.github.io/gbm-web/launcher.html)
	-  [Translation F.A.Q](http://mikemaximus.github.io/gbm-web/translations.html)
	-  [Linux F.A.Q](http://mikemaximus.github.io/gbm-web/linux.html)
	-  [Wine F.A.Q](http://mikemaximus.github.io/gbm-web/wine.html)

2. I used [WinCHM Pro](http://www.softany.com/winchm/) to reconstruct the HTML. Mirror available here (Base64):
``` 
aHR0cHM6Ly9scmVwYWNrcy5ydS9yZXBha2ktcmF6bnloLXByb2dyYW1tLzQ4MC13aW5jaG0tcHJvLXJlcGFjay1hbXAtcG9ydGFibGUuaHRtbA==
```

3. All image resources were saved to ```\GBM_files\```
4. All page HTML starting with ```<div class="pageSection">``` and ending with ```</div><!--Include the Footer-->``` (or for the Manual, ```</div>``` before the next ```<div class="pageSection">```) were copied from the HTML source pages and pasted between WinCHM's ```<body> </body>``` tags.
5. The theme was started by copying a built-in WinCHM theme, then removing everything and replacin.g it with CSS and asset references from the ```<head> </head>``` and header graphics/text in the Manual page.
6. WinCHM can then render CHM Windows help files, and nicely formatted PDFs from the project. Project file is **Game_Backup_Monitor_v1.2.4_Help.wcp**

### The manual will need updating periodically, with [releases of Game Backup Monitor](https://github.com/MikeMaximus/gbm/releases).

## Author
[MikeMaximus](https://github.com/MikeMaximus) is the author of Game Backup Monitor and its website. I, Darthagnon, copied the website content, and made as few changes as possible, preserving the original layout. I only added and edited some hyperlinks, and collated all useful information regarding GBM that I thought should be in a manual and I would need for offline reference. I don't intend copyright infringement, just to help the GBM project.