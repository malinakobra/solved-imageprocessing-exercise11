Download Link: https://assignmentchef.com/product/solved-imageprocessing-exercise11
<br>
Exercise lla. Implement the program ‘exercise_lla_flatzone’ that obtains the flat zone (piecewise-constant region) of a pixel (x,y) that will be launched as:

exercise_lla_flatzone exercise_lla_inp ut_0l.txt exercise_lla_inp ut_0l.pgm exercise_lla_o utp ut_0l.pgm

The input file ‘exercise_lla_inp ut_0l.txt’ is an input file with 4 lines of parameters:

-At line l: an integer number ‘x’ that denotes the column of the pixel. -At line 2: an integer number ‘y’ that denotes the row of the pixel. -At line 3: an integer number ‘connectivity’ that denotes the connectivity number employed (4 or 8, corresponding to 4-connectivity or 8-connectivity, respectively).

-At line 4: an integer number ‘flat zone label’ that indicates the label value that the flat zone in the output image will have.

The flat zone of pixel (x,y) will appear with value ‘flat zone label’ in the output image exercise_lla_o utp ut_0l.pgm, and the rest of the image pixels will have zero intensity value. The ‘flat zone label’ value is different from 0.

Note: 8-connectivity can be assumed (it is not necessary to consider 4-connectivity).

Note: to check imFlatZone:

-immed_gray_inv_2005l2l8_frgr4.pgm      (input image)

-immed_gray_inv_2005l2l8_frgr4_flatzone57_36.pgm       (flat zone of pixel

(column = 57, row = 36))

-gran0l_64.pgm        (input image)

-gran0l_64_flatzone0_0.pgm       (flat zone of pixel

(column = 0, row = 0))

-See the pseudocode of flat zone reconstruction.