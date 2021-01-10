# artix-config
my Artix Linux configs

console keymap:

/etc/vconsole.conf

    KEYMAP=dvorak    

vim 

    mkdir ~/.vim/undodir

/etc/profile 

    # fix PyCharm blank window issue
    export _JAVA_AWT_WM_NONREPARENTING=1

    # fix Telegram ibus input
    export QT_IM_MODULE=ibus
    
   
Thinkorswim
add in thinkorswim.vmoptions
    -Dsun.java2d.uiScale=2
