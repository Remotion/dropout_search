﻿
SETTINGS
To override the default settings use Dropout.ini, it should be place in the same directory as Dropout.exe, setting below:

[Location]
; The directories you want to search, default is the directory where the Dropout.exe is. 
; You can also specify a semicolon-separated list, i.e C:\Users\admin\Documents\Pictures;C:\Users\admin\Documents\Videos etc...
; Relative paths can also be used, they are relative to Dropout.exe, i.e. Documents;Pictures or ..\Documents
Search Directory=C:\Users\admin\Documents\
; Where to store the lucene index, default is the SearchIndex directory where the Dropout.exe is
Search Index=C:\TMP\Index
; If you want  the indexer to skip certain paths. The list must be semicolon-separated.
Paths To Skip=c:\$Recycle.Bin
; Search patterns separated by semicolons, the default is *.*
Search Patterns=*.doc;*.docx

[Index]
; The maximum file size to index in megabytes, default is 20mb
Max Size=20
; The maximum zip file to index in megabytes, default is 5mb
Zip Max Size=5

[Results]
; The maximum results to display, default is 200
Max Result=200

[Options]
; If you would prefer the Windows Explorer Shell menu on right click set this to true, the default is false
Explorer Menu=True
; By default the indexes don't have full paths to ensure portability on USB's and in Dropboxes
; If you have multiple search paths each path will be searched to see if the file exists before opening
; To have full paths, i.e. C:\Users\Admin\Documents, set this to False
Portable Paths=False




LICENSE

Apache v2.0: http://www.apache.org/licenses/LICENSE-2.0.html

CREDITS

Application based on Dan Letecky's Desktop Search
  http://www.codeproject.com/KB/office/desktopsearch1.aspx
  License: Apache v2.0: http://www.apache.org/licenses/LICENSE-2.0.html

IFilter implementation from alex_zero\
  http://www.codeproject.com/KB/cs/IFilterReader.aspx
  License: Eclipse v1.0: http://www.opensource.org/licenses/eclipse-1.0.php

iTextSharp (4.1.6) by Bruno Lowagie
  http://sourceforge.net/projects/itextsharp/
  License: GPL or LGPL (Version 5+ is AGPL)

Explorer ShellContextMenu by "Jon Likes to Code"
  http://www.codeproject.com/KB/cs/shellContextMenu.aspx
  License: The Code Project Open License (CPOL): http://www.codeproject.com/info/cpol10.aspx
