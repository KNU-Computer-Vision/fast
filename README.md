# fast-opencv
Implementation of feature from accelerated segment test algorithm, coupled with filtering against noise

This code is a good corner detector which uses FAST algorithm
(features from accelerated segment test), coupled with orientation filtering.

I used openCV2.4.9 for the pixel access.

The orientation filtering idea was proposed in:
http://www.vision.cs.chubu.ac.jp/flabresearcharchive/bachelor/B12/Abstract/hasegawa.pdf

COMPILATION & EXECUTION:
do "make" at directory where code is saved
openCV is required for compilation

for execution
./main 'file'.jpg or png or any format
