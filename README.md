BlackReactorSource_SGY
======================

Source for Black Reactor Source for SGY

These are just the changes ive done on the Kernel source.

The kernel source can be obtained from here:

http://opensource.samsung.com/

Type in "GT-S5360" in the search box

and download "GT-S5360_GB_Opensource_Update2.zip"

unzip this and you will get these:

GT-S5360_Kernel.tar.gz,
GT-S5360_Platform.tar.gz,
GT-S5360_Platform.txt,
GT-S5360_Kernel.txt,

Unzip "GT-S5360_Kernel.tar.gz" and patch it with this 
source, you are ready to execute "make"


NOTE: For building CM kernels, use the CM-config-file
also, use the ramdisk of the BlackReactor Kernel.
Since, CM for sgy uses ext4fs, the ramdisk needs to 
be changed.
