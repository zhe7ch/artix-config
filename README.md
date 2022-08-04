# artix-config
my Artix Linux configs

vim 

    mkdir ~/.vim/undodir

/etc/profile 

    # fix PyCharm blank window issue
    export _JAVA_AWT_WM_NONREPARENTING=1

    # fix Telegram ibus input
    export QT_IM_MODULE=ibus



HiDPI:

In Pycharm, Help -> Edit Custom VM Options, input:
    -Dsun.java2d.uiScale.enabled=true
    -Dsun.java2d.uiScale=2  
