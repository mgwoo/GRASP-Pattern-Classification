# GRASP based Layout Pattern Classification
This is binary distributation pages for GRASP based Layout Pattern Classification @ ICCAD17 [Link](http://ieeexplore.ieee.org/document/8203820/)

## Check the Usage
    $ ./patternClassify -help

will print out

    Usage:
        patternClassify -input [FileLoc] -output [FileLoc] -acc [Ratio] -ecc [nm]
                -n [num] -alpha [Ratio] -mt [num] -cwidth [nm] -cheight [nm]

    Options:
        Note: options are case-insensitive and can be shortened as long they remain unique.

        -help
            Print Manual and Exit

        -input [File Location]
            Set input GDS File locationd

        -output [File Location]
            Set Location of Output of Clustered Clip

        -acc [ACC Ratio]
            Set ACC Rate

        -ecc [ECC Length/nm]
            Set ECC Length in nm Units

        -n [Num]
            Set the trial number for GRASP
            Default trial is 100

        -alpha [Ratio]
            The alpha is used to generate the range of RCL
            Default alpha is 0.9

        -mt [Num]
            Enable Multi-Thread Mode
            Default Thread Number is 1

        -cwidth [Clip Width]
            Set Clip Width in nm units
            Default Clip Width is 200nm

        -cheight [Clip Height]
            Set Clip Height in nm units
            Default Clip Height is 200nm

## GDS Files
    [Link](http://cad-contest-2016.el.cycu.edu.tw/Problem_C/default.html)

## Example
    // testcase4 with 250 X 250, ACC 100% and 8 Threads.
    $ ./patternClassify -input ../testcase/testcase4/testcase4.gds -output ../Output/testcase4.gds -mt 8 -acc 100 -cwidth 250 -cheight 250
    
    // testcase2 with 200 X 200, ECC 2nm and 8 Threads.
    $ ./patternClassify -input ../testcase/testcase2/testcase2.gds -output ../Output/testcase2.gds -mt 8 -ecc 2 -cwidth 200 -cheight 200

## Citation
Cite this work
    Mingyu Woo, Seungwon Kim and Seokhyeong Kang, "GRASP based Metaheuristics for Layout Pattern Classification", Proc. IEEE/ACM International Conference on Computer-Aided Design, 2017, pp. 512-518.
