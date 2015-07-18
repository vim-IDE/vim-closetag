closetag.vim
============

Auto close tag, support xml files. In addition to the [alvan version](https://github.com/alvan/vim-closetag), a line feed is added and the cursor is set with the appropriate indentation.

Demo with [MatchTagAlways](https://github.com/vim-IDE/MatchTagAlways) activated.

![alt tag](gif/example.gif)

Just set this in your vimrc:

    # filenames like *.xml, *.html, *.xhtml, ...
    let g:closetag_filenames = "*.html,*.xhtml,*.phtml"

Then after you click &gt; in those files, this plugin will try to close the current tag for you.

#### Usage

For example, below is the current content:

    <table|

Now you press &gt;, the content will be:

    <table>|</table>

And now if you press &gt; again, the content will be:

    <table>
        |
    </table>


#### Install Detail

Just put the files into ~/.vim/ or &lt;HOMEDIR&gt;\vimfiles\ (for Windows).
