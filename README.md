# QAnon Block Guide

This is a quick guide on how to block access to a range of QAnon/far-right/conspiracy websites on a single Windows PC.

### 1. Open Notepad

Open the start menu and type "notepad" in the search box. Right-click the notepad icon and click "Run as administrator". This is required as the file we're about to edit is write-protected.

![](https://raw.githubusercontent.com/yui-konnu/qanon-block-guide/master/1-notepad%20admin.png)

### 2. Open File

Click on the File > Open... menu item shown in the image.

![](https://raw.githubusercontent.com/yui-konnu/qanon-block-guide/master/2-file%20open.png)

### 3. Navigate and open hosts file

In the pop-up window, change the combo-box on the bottom-right to "All Files (*.*)" as seen in the image below. Then navigate to `C:\Windows\System32\drivers\etc`. Open up the file named "hosts".

![](https://raw.githubusercontent.com/yui-konnu/qanon-block-guide/master/3-select%20file%20type.png)

### 4. Paste and save

Open up the following link in your web browser: https://raw.githubusercontent.com/rimu/no-qanon/master/etc_hosts.txt

You should see a list of websites. Copy the entire text (Ctrl+A, Ctrl+C) and paste it into the opened hosts file in notepad. Then save the file via File > Save menu item, or via Ctrl+S.

![](https://raw.githubusercontent.com/yui-konnu/qanon-block-guide/master/4-save%20file.png)

### Add additional blocked sites (Optional)

If you want to block additional websites you can do by adding new lines into the hosts file, for example:

```
0.0.0.0 facebook www.facebook.com
```

This would block facebook.com. Remember to block both www and non-www versions of a website.