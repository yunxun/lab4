# lab4
program design 2

Question A:
type nm QA
it will show:
0000000000600e50 d _DYNAMIC
0000000000600fe8 d _GLOBAL_OFFSET_TABLE_
0000000000400608 R _IO_stdin_used
                 w _Jv_RegisterClasses
00000000004004b4 T _Z7averagePdRd
00000000004004e2 T _Z7averageif
0000000000600e30 d __CTOR_END__
0000000000600e28 d __CTOR_LIST__
0000000000600e40 D __DTOR_END__
0000000000600e38 d __DTOR_LIST__
0000000000400738 r __FRAME_END__
0000000000600e48 d __JCR_END__
0000000000600e48 d __JCR_LIST__
0000000000601018 A __bss_start
0000000000601008 D __data_start
00000000004005c0 t __do_global_ctors_aux
0000000000400420 t __do_global_dtors_aux
0000000000601010 D __dso_handle
                 w __gmon_start__
0000000000600e24 d __init_array_end
0000000000600e24 d __init_array_start
00000000004005b0 T __libc_csu_fini
0000000000400520 T __libc_csu_init
                 U __libc_start_main@@GLIBC_2.2.5
0000000000601018 A _edata
0000000000601028 A _end
00000000004005f8 T _fini
0000000000400390 T _init
00000000004003d0 T _start
00000000004003fc t call_gmon_start
0000000000601018 b completed.6531
0000000000601008 W data_start
0000000000601020 b dtor_idx.6533
0000000000400490 t frame_dummy
000000000040050a T main

其中
00000000004004b4 T _Z7averagePdRd
00000000004004e2 T _Z7averageif
這兩句是解碼辨識此兩函數的樣子

Quesion B:
type ./QB
it will show
1 8
4 8
4 8
8 8
第一直行的數字是變數型態的位元大小
char needs 1byte
int  needs 4 bytes
float needs 4 bytes
double need 8 bytes

第二直行則是指向個變數型態所存取位址的大小
而通常位址的存取大小都是8 bytes
