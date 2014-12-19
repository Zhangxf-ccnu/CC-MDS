README file for Matlab source code supporting the paper "Determining minimum set of driver nodes in
protein-protein interaction networks".


Contents of this archive
------------------------
This archive contains several Matlab scripts used to determine driver proteins using the model CC-MDS presented in the above paper. 

(1) CC_MDS.m: Matlab script that determines driver proteins using the CC-MDS model.
(2) CC_MDS_demo.m: A simple Matlab script used to test CC-MDS. 

This archive also contains a folder named as "data" which includes the three PPI networks used in this study.

Please note that before performing the experiments, you need to install Matlab package "matlab-bgl" (https://github.com/dgleich/matlab-bgl) 
that will be used to compute betweenness centralities of proteins; if you would like to use library "lp_solve" (http://lpsolve.sourceforge.net/5.5/),
please ensure it has been installed correctly; if you want to use function "intlinprog" (http://www.mathworks.com/help/optim/ug/intlinprog.htm), 
please use Matlab 2014b or later.

This archive also contains the library "lp_solve" and  package "matlab-bgl" that we use on a Microsoft Windows operating system.

Please do not hesitate to contact Prof. Dao-Qing Dai at stsddq@mail.sysu.edu.cn (or Dr. Xiao-Fei Zhang at zhangxf@mail.ccnu.edu.cn) to 
seek any clarifications regarding any contents or operation of the archive.
