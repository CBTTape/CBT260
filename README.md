# CBT260
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 260 IS A VERY QUICK MAPPING PROGRAM.  IT WILL PRODUCE     *   FILE 260
//*      A LISTING OF EVERY DATA SET ON A VOLUME PLUS CALCULATE     *   FILE 260
//*      THE FREE SPACE, FREE DSCBS, ETC.  OPTIONALLY VIA PARM      *   FILE 260
//*      INFORMATION IT WILL PRODUCE THE FOLLOWING:                 *   FILE 260
//*                                                                 *   FILE 260
//*      Updated July 2000 by Charles Wells of the Georgia Dept.    *   FILE 260
//*      of Labor, to add support for 3390-9 disk drives.           *   FILE 260
//*                                                                 *   FILE 260
//*      Updated November 2002 by Alan Buschmann of Kohl's          *   FILE 260
//*      Department Stores, to fix a bug.                           *   FILE 260
//*                                                                 *   FILE 260
//*      Updated again February 2005 by Alan Buschmann of Kohl's    *   FILE 260
//*      Department Stores, to correct the UCB display.             *   FILE 260
//*                                                                 *   FILE 260
//*         Al Buschmann                                            *   FILE 260
//*         Kohl's Department Stores                                *   FILE 260
//*         (262) 703-6103                                          *   FILE 260
//*         email:  Alan.Buschmann@kohls.com                        *   FILE 260
//*                                                                 *   FILE 260
//*         Charles Wells                                           *   FILE 260
//*         Georgia Dept. of Labor                                  *   FILE 260
//*         Suite 352                                               *   FILE 260
//*         148 International Blvd                                  *   FILE 260
//*         Atlanta, GA 30303-1751                                  *   FILE 260
//*                                                                 *   FILE 260
//*         Voice: 404-656-5944                                     *   FILE 260
//*         Email: Charles.Wells@dol.state.ga.us                    *   FILE 260
//*                                                                 *   FILE 260
//*         PARM=MAP     PRODUCES A TRACK MAP OF THE VOLUME         *   FILE 260
//*         PARM=PDS     LIST ALL PDS DIRECTORIES ON THE VOLUME     *   FILE 260
//*         PARM=ISAM    LIST ISAM REORG INFORMATION FOR DATASETS   *   FILE 260
//*         PARM=EXT     LIST THE EXTENTS OF THE DATASETS           *   FILE 260
//*         PARM=DUMP    LIST IN HEX ALL DSCBS ON THE VOLUME        *   FILE 260
//*         PARM=EMPTY   LIST ONLY DATASETS THAT ARE EMPTY          *   FILE 260
//*         PARM=MODEL   LIST ONLY MODEL DSCBS                      *   FILE 260
//*         PARM=SDUMP   LIST IN HEX FORMAT 4 AND 5 DSCBS           *   FILE 260
//*         PARM=VOLS    ONLY USE DDNAMES OF VOLUMEXX               *   FILE 260
//*         PARM=JDATE   LIST CREATION/EXPIRATION DATES IN JULIAN   *   FILE 260
//*                                                                 *   FILE 260
//*      THIS CODE WILL SUPPORT 3380'S                              *   FILE 260
//*      THIS CODE WILL SUPPORT INDEXED VTOCS                       *   FILE 260
//*                                                                 *   FILE 260
//*      ADDITIONAL COMMENTS ARE DOCUMENTED IN THE SOURCE           *   FILE 260
//*      THIS PROGRAM MUST BE LINKED AS AC=1.                       *   FILE 260
//*                                                                 *   FILE 260
//*******************************************************************   FILE 260
//*** CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT ***   FILE 260
//***                                                             ***   FILE 260
//***  A USER OF THIS CODE DECIDED TO USE A PARM OF RESET, WHICH  ***   FILE 260
//***  WILL RESET THE HIGH WATER MARK IN THE VTOC.  IT DID IT,    ***   FILE 260
//***  ALL RIGHT, BUT IT SET IT TO 512 (ON A 3350) AND THE ARM    ***   FILE 260
//***  BOUNCED ALL OVER THE PLACE. BE CAREFUL !!!!!!!             ***   FILE 260
//***                                                             ***   FILE 260
//*** CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT CBT ***   FILE 260
//*******************************************************************   FILE 260
//*                                                                 *   FILE 260
```
