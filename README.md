# Read CSV file in MATLAB

Tool to read csv file containing array with n multiple columns.

Input Arguments:
input          array with n multiple columns in csv format
   
Output Arguments:
varargout      the size depends on how many columns in the csv files

Example:
1. csv file
please remove any header/title on the csv file before using this script
-------- 
0, 1, 2

1, 2, 3

2, 3, 4
--------
2. create a new script to call readcsv
--------
[t, u1, u2]        = readcsv('filename.csv')

written by Yohan Fajar Sidik (ysi) on 03.08.2018
updated on 02.10.2018: give an example how to use the script
