# HTML 5 Skeletons Bundle for TextMate

## Install

The quickest way to install the bundle is via the command line. If you have Git installed, you'll probably want to install with Git. With or without, you can simply copy and paste each line one by one into the Terminal instructions ( lifted from [svnlto](http://github.com/svnlto/html5.tmbundle) ):

### Install with Git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/ala747/HTML5-Skeletons.tmbundle.git "HTML5 Skeletons.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

### Install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/ala747/HTML5-Skeletons.tmbundle/tarball/master
    tar zxf ala747-HTML5-Skeletons.tmbundle*.tar.gz
    rm ala747-HTML5-Skeletons.tmbundle*.tar.gz
    mv ala747-HTML5-Skeletons.tmbundle* "HTML5 Skeletons.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Download

If you'd like to avoid the command line altogether, you can download the bundle and install it:

1. download the zip from [http://github.com/ala747/HTML5-Skeletons.tmbundle/zipball/master](http://github.com/ala747/HTML5-Skeletons.tmbundle/zipball/master)
2. find the zip file on your local machine and double-click to unzip it
3. change the file name from *ala747-HTML5-Skeletons.tmbundle-really_long_alpha_numeric_sequence* to *HTML5 Skeletons.tmbundle*.
4. double-click the *HTML5 Skeletons.tmbundle* file
5. open TextMate and select the following menu item: *Bundles > Bundle Editor > Reload Bundles*
6. show the Bundle Editor (*Bundles > Bundle Editor > Show Bundle Editor*)
7. scroll through the list of bundles to confirm that the bundle has been properly installed
