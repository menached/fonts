Created from Google's source repository on December 1st, 2010.
http://joemaller.com/1856/download-google-fonts/

This archive includes the most recent font files pulled from Google's open 
source Web Fonts Directory. All licenses, metadata and author credits are
intact.

http://code.google.com/webfonts

The purpose of this archive is to give web designers the freedom to experiment
with these fonts offline and to use them for sketches, comps and presentations.


Technical Details

Archive is semi-automated, the commands are listed below. You should have a 
Mercurial clone of the Google Web Fonts directory as described here:

http://code.google.com/p/googlefontdirectory/source/checkout

1. hg pull -u
2. tar -zvcf googlewebfonts.tgz -X googlefontexclude.txt googlefontdirectory

To reduce the size of the archive, files matching the following patterns in
googlefontexclude.txt file will be excluded:
    .hg*
    src
    *.menu
    *.menu2
    *.png
    .DS_Store
    
This download archive is offered by Joe Maller.


