# FasParser2
#### A graphical platform for batch manipulation biological sequences ####
 
A computer software package called FasParser has been developed for manipulating sequence data. It can be used on personal computers to perform a series of analyses, including counting and viewing differences between two sequences at both DNA and codon levels, identify overlapping regions between two alignments, sort sequences according to their IDs or lengths, concatenate multiple loci sequences for a particular set of samples, translate DNA to protein, construct alignments with multiple different formats, and also some extraction and filtration analyses on a particular FASTA file. Majority of these functions can be run in a batch mode that is much useful for analyzing large data sets. We hope our package will be helpful for a broad audience, particularly those without programming experience in sequence analyses. 
 
![image](https://github.com/Sun-Yanbo/FasParser/blob/master/Figures/Homepage.jpg)
 
**Sun Yan-Bo** (*sunyanbo@mail.kiz.ac.cn*)
 
**Kunming Institute of Zoology, Chinese Academy of Sciences**
 
----------
 
### [System requirement and installation]: ###
 
- The **FasParser** has been developed into a standalone Windows System Application (compiled and tested on Windows 7/10). It could be run on most Windows systems with no dependence of other programs.
 
- Download the setup program (i.e. **FasParserX.X_setup.exe** ) from https://github.com/Sun-Yanbo/FasParser to your disk, and then double click it to install the whole package. It is normally well using the default installation parameters (clicking the Next button).
 
----------
 
### [Citation]: ###
 
1. **Sun Yan-Bo** FasParser: a package for manipulating sequence data. ***Zoological Research*** 38(2): 110-112, 2017
2. **Sun Yan-Bo** FasParser2: a graphical platform for batch manipulation of biological sequences. ***Under review***
 
----------
 
### [Update history]: ###
[Version 2.3.0] 2018-1-30
1. add `AA2DNA` to obtain codon alignments based on aa alignments;
2. change all buttons 'Scan' to 'Open'; (2018-2-5)
3. add result display as well as result viewing function by double click;
4. add 'Delete' operation on selected files 
(useful for transforming one function's outputs to another function's inputs)
5. add automated gap-deletion in template DNA for primer design;
6. Clear the primer results when starting a new primer design; (2018-2-5)
7. active the scroll bar in the `Align` window;
8. improve ID preview function for `Filter`;
9. optimized codes, especially for `CMP2Seq`(2018-2-5)
 
[Version 2.2.0] 2018-01-10
1. improve interface display
2. move the `classification` function to `Filter` (Based on keywords)
3. add drag-function to selecte files into the list box [2018-1-11]
4. fix errors in selecting files when there have been files in the listbox [2018-1-11]
5. add auto-update function [2018-1-11]
6. greatly improve the `Sort & Rename` function for easy to use [2018-1-15]
7. fix UI (radiobutton) errors in `Merge` [2018-1-15]
8. fix errors in filtration based on keywords [2018-1-15]
9. improve update checking function [2018-1-15]
10. add folder-drag function to selecte multiple files [2018-1-15]
 
[Version 2.1.1] 2017-12-07
1. fix errors in `Filter` based on length;
2. improve usability of `Filter` based on similarity
3. improve global settings (tmp folder, associate suffix...)
4. add 'Merge' and 'Concatenate' functions in `Merge` function
5. improve `Sort` functions; change rename IDs by setting '=>'
6. auto fresh the view of 2 sequences after align
7. add deleting empty columns ("-" for all seqs) in alignments (20171217)
8. improve similarity estimate by considering RevCmp seq in `Filter` (20171217) 
9. improve `Filter` function based on similarity (20171218)
10. improve similarity estimate by considering indels (for `AlignSim` and `Filter`) (20171218)
11. improve `Filter` function based on ID (showing more result information; 20171220)
12. improve `Filter` function based on similarity when input sequences too long (20171221)
13. edit the user guide (20171225)
14. fix bugs of closing window when it is running (20171226)
15. improve `Filter` function based on IDs to show more running process information (20171226)
16. remove the symbol "'" in nexus output of `Format` (20180104);
17. fix errors in `Sort` when ">" present in ID (20180109)
 
[Version 2.1.0] 2017-11-16
1. add filtration based on similarity
2. optimize codes for AlignTrim
3. improve classification function (can handle large files)
 
[Version 2.0.0] 2017-10-20
1. Redesign the GUI
2. Add Text Editor for FasParser
3. Add GeneStructre drawer function
4. Add AlignTrim & AlignScore functions
5. Add batch sort & classification function
6. Add Primer designning function (with Primer3)
7. Add Positive selection detection (with PAML)
8. Add Bug report function
 
[Version 1.2.2] 2017-06-20
1. fix a small error in `MergeFas`
2. fix a UI error
3. change too long sequence (`MergeFas` output) to mul-lines 
 
[Version 1.2.1] 2017-05-23
1. add auto-update function (deleted in future version)
2. speed-up the `Filter` functions
 
[Version 1.2.0] 2017-05-17
1. add Align&Compare function in 'Cmp-2Seq': can handle 2 unaligned sequences;
2. fix bugs in dn/ds estimate when seq length not multiples of 3;
3. fix bugs in format convertion when folder name has space(s);
4. fix some UI errors;
5. improve `Sort` function with seq Length (descending or ascending);
6. improve displaying ability of some results
 
[Version 1.1.0] 2017-03-28
1. add the getORF function into this package;
2. orf can be get according to ref pep seq(s)(deleted in future version)
3. optimize some subfunctions;
5. improve the GAP-cut function in `Filter`;
 
[Version 1.0.2] 2017-03-22
1. improve the `Sort` function with user provided ID list;
2. improve the extraction function for large FASTA file;
3. add Clear buttons for convenient operation;
4. optimize codes (flexibility and simplicity);
5. fix some UI bugs and improve telling running process
6. add version check function;
7. improve `Align` function for folder with space(s)
 
[Version 1.0.1] 2017-03-11
1. add classification function in the `Sort` section;
2. add ID-rename function in `Sort` section;
3. improve the alignment cut function in `Filter` section ;
4. improve the alignment filtration based on seq length;
5. fix some UI bugs
 
[Version 1.0.0] 2017-02-28
