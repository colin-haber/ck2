# Crusader Kings II mod tools
This extension provides Crusader Kings II mod support for Visual Studio Code. Right now, it&rsquo;s just syntax highlighting, but future support for more sophisticated features like IntelliSense is anticipated.

##Use
Because <abbr title="Crusader Kings II">CK2</abbr> mod files by default have <code>.txt</code> suffixes, you&rsquo;ll need to enable the features one of two ways:
1.	Rename mod files to <code>*.ck2.txt</code>. The extension will automatically work its magic on any file with this suffix. You will need to add a <code>replace_path</code> line to the <code>.mod</code> file to make sure the files you have changed are still overwriting their original counterparts. This is the preferred method.
2.	Change the language in <abbr title="Visual Studio Code">VS Code</abbr> to <b>Crusader Kings II</b> when you want syntax highlighting. You&rsquo;ll need to do this every time you open the file.

##Features
*	Syntax highlighting
*	Glorious Xwedodah?

##Contributing
This project is hosted at [dgn1nja/ck2](https://github.com/dgn1nja/ck2).

##Copying
&copy; 2016 Colin Haber  
[Licensed GPLv3](http://www.gnu.org/copyleft/gpl-3.0.html)
