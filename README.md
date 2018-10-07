## A tool to read a csv file containing n multiple columns and to separate them into their independent variables

* Input Arguments:

input:          array with n multiple columns in csv format
   
* Output Arguments:

varargout:      the size depends on how many columns in the csv files

Example:
1. csv file

0, 1, 2

1, 2, 3

2, 3, 4

Note: please remove any header/title on the csv file before using this script

2. create a new script to call readcsv

```[t, u1, u2]        = readcsv('filename.csv')```

## Change log

1. 03.08.2018: first created by ysi
2. 02.10.2018: give an example how to use the script


