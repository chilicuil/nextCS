Change your vim color scheme easily

nextCS
------

nextCS (next Color Scheme) changes your theme in one shot. It's based on some other scripts I found who didn't work with some silly color schemes. This one will load *every* theme you got. If it's incorrect, you'll see the error, but you'll able to just press "next" (F12) and you'll see the next.

- F12 Next
- F11 Previous

Simple enough :)

Installation
------------

*Pathogen*:

    $ git clone https://github.com/chilicuil/nextCS.git ~/.vim/bundle/nextCS

*Vundle*, add the following to your $HOME/.vimrc file:

    Bundle 'chilicuil/nextCS'

And run inside of vim:

    :BundleInstall

*Manual*, download the vim file from http://www.vim.org/scripts/script.php?script_id=2713 and copy it to $HOME/.vim/plugins/

    mv nextCS.vim $HOME/.vim/plugins

If you find yourself uncomfortable with the default mapping, change it by adding to your vimrc file:

    nnoremap <F12> :call NextCS()<CR>
    nnoremap <F11> :call PreviousCS()<CR>

License
-------

© 2013 WTFPL, Do What the Fuck You Want to Public License. - http://www.wtfpl.net/
