# CBT691
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 691 is from Martin Kline and contains a program to        *   FILE 691
//*           optimize reads of a few records from a large sorted   *   FILE 691
//*           sequential file.  There are a few other tools here    *   FILE 691
//*           too, relating to SYS1.BRODCAST.                       *   FILE 691
//*                                                                 *   FILE 691
//*           email:  martin_kline@americancentury.com              *   FILE 691
//*                                                                 *   FILE 691
//*     Description of RANDSEQ program:                             *   FILE 691
//*                                                                 *   FILE 691
//*     This subroutine can be called to perform random reads       *   FILE 691
//*     against any sorted sequential disk file. Records can be     *   FILE 691
//*     read by key, in sequence, or in skip-sequential order.      *   FILE 691
//*                                                                 *   FILE 691
//*     The best use of this routine is for improving the run       *   FILE 691
//*     times of jobs which need to access only a few records       *   FILE 691
//*     out of very large files. Since the program logically        *   FILE 691
//*     finds records in the file, it is not as efficient at        *   FILE 691
//*     reading lots of records in sequence as standard QSAM.       *   FILE 691
//*                                                                 *   FILE 691
//*     The program determines all of the multi-volume extents      *   FILE 691
//*     for the file, then determines the key ranges for each       *   FILE 691
//*     extent. It performs a binary search for the requested       *   FILE 691
//*     key. It also keeps a tree structure of keys it has          *   FILE 691
//*     already found, to improve the response as additional        *   FILE 691
//*     records are read.                                           *   FILE 691
//*                                                                 *   FILE 691
```
