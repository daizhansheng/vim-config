＃vim-config
vimconfig.tar文件适用于Ubuntu 12.04  14.04 16.04的系统上
jeffy文件适用于Ubuntu 18.04和20.04上



在用户家目录下的.vimrc结尾加上如下语句
let Tlist_Show_One_File=0
set noswapfile
set tags+=/usr/include/tags
set tags+=./tags;                                                                                 
map ta :!ctags -R --c++-kinds=+p --fields=+iaS --extra=+q .<CR>
