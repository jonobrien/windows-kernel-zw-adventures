# windows-zw-kernel-adventures
A dive into the undocumented and "deprecated" jungle of the kernel apis

You will need a windows vm to debug using windbg

use visual studio with driver support and create a basic driver project to allow universal use from xp(maybe) to win10 with unified apis

## setup
[enable debug prints](http://www.osronline.com/article.cfm?article=295)

[script](https://gist.github.com/jonobrien/3c697f5406305d0ce1d52f410d5aeaf4)

## extracting structs
use windbg to extract structs from the kernel with symbols and verify your size and layout is same, types are less important
[eprocess ex.](https://social.msdn.microsoft.com/Forums/windowsdesktop/en-US/e18c1f8c-14e3-40b3-8764-205cdae37109/parsing-systemprocessinformation-list-?forum=windbg)

## verify your sizes
[undocumented nt](https://stackoverflow.com/q/3310992)

