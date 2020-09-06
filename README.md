# PCPT-FCI
 This work is about mining frequent closed itemsets in data stream.
 
 The related paper will be published soon.

The executable file for PCPT-FCI algorithm:

PCPT-FCI.exe was compiled by Microsoft Visual Studio 2010， runable in windows.

PCPT-FCI was compiled with g++ (GCC) 4.8.5 20150623 (Red Hat 4.8.5-28)， runable in Linux.

-------------------------------------------------------------------------------

test.txt is an example for PCPT-FCI 

Format of dataset：

Line 1 only contains the number of transactions, and other lines are as follow:  

the length_of_transaction    item_id_1   ...   item_id_n
                ......
the length_of_transaction    item_id_1   ...   item_id_n

-------------------------------------------------------------------------------

Usage by commandline：

PCPT-FCI.exe WINDOW_SIZE MINSUP INPUTFILE OUTPUTFILE SLIDING_NUMBER

where:
WINDOW_SIZE ：the sliding window size 

MINSUP ：the minimum support (as integer)

INPUTFILE ：name of input file

OUTPUTFILE ：name of output file

SLIDING_NUMBER：number of sliding

example：

PCPT-FCI.exe 4 1 test.txt out.txt 2
