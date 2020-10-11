# LiNos
## My re-write of the linux OS 0.11-version

## All the files
- /boot   *all the flies that controls the bootup*
- /fs   *all the files that related to the filesystem*
- /include  *xx.h files*
- /init *init the OS and run main.c*
- /kernel   *all the system_call*
- /lib  *lib files*
- /mm   *all the files to manage memory*
- /tools    
- Makefile


## Note
    Makefile calls up all the makefile in the directories and make them together to get the LiNOS

## [TO DO LIST]
    [] implement buddy system
    [] fix the xv6 & ucore together
    [] rewrite the file system
    [] add GUI
    [] add Network Protocol Stack
    [] maybe rewrite it in Rust
    
## Now I have read the source code of the Linux Kernel v0.11 
* And I'm going to start the OS Writing *

* If I have enough time, I will write a detailed turtorials to talk about the way to write a personal toy system

## LiNos Design Target
# ![Target](MyOS设计目标.png)


## Kernel Structure
# ![Kernel](Kernel Architecture.png)

## Boot
# ![boot](system.s(bootimage).png)

## TSS
# ![TSS](TSS任务切换.png)

## Mode Transformation
# ![Mode](实模式与保护模式的寻秩不同.png)

## Process
# ![Process](进程状态转换图.png)

## Memory Management
# ![Memory Management](VA_to_PA.png)

## Device
# ![blk](blk_drv.png)
# ![chr](chr_drv.png)

