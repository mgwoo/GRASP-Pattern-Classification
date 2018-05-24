# GRASP based Layout Pattern Classification
This is binary distributation pages for GRASP based Layout Pattern Classification @ ICCAD17 [(Link)](http://ieeexplore.ieee.org/document/8203820/)

## Check the Usage
    $ ./patternClassify -help

will print out all usages

## GDS Files
[(Link)](http://cad-contest-2016.el.cycu.edu.tw/Problem_C/default.html)

## Usage Example 
    // testcase4 with 250 X 250, ACC 100% and 8 Threads.
    $ ./patternClassify -input ../testcase/testcase4/testcase4.gds -output ../Output/testcase4.gds -mt 8 -acc 1.00 -cwidth 250 -cheight 250
    
    // testcase4 with 250 X 250, ACC 95% and 8 Threads.
    $ ./patternClassify -input ../testcase/testcase4/testcase4.gds -output ../Output/testcase4.gds -mt 8 -acc 0.95 -cwidth 250 -cheight 250
    
    // testcase2 with 200 X 200, ECC 2nm and 8 Threads.
    $ ./patternClassify -input ../testcase/testcase2/testcase2.gds -output ../Output/testcase2.gds -mt 8 -ecc 2 -cwidth 200 -cheight 200

## Citation
Cite this work :

[1] Mingyu Woo, Seungwon Kim and Seokhyeong Kang, "GRASP based Metaheuristics for Layout Pattern Classification", Proc. IEEE/ACM International Conference on Computer-Aided Design, 2017, pp. 512-518.
