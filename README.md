# PKU-Person-Orientation
PKU Person Orientation dataset:
This dataset contains 4 video sequences with 976, 732, 1031, 855 frames respectively. 
The video sequences are captured in the campus surveillance scenes with 25 fps 
containing eight discrete orientations. The person images, orientation labels 
and position information are all manually annotated.

Each folder contains the video sequence data of one person.
Label data is provided in the label.mat file.
Position information is provided in the pos.txt file.

label.mat file structure: 
each row contains a label for the corresponding sample, 
the label-orientation matchup is shown as follow,
1(E) 2(NE) 3(N) 4(NW) 5(W) 6(SW) 7(S) 8(SE).

pos.txt file structure: 
each row contains the position infomation for the corresponding sample, 
the four values from left to right mean [x,y,width,height] and [x,y] is
the left-top point coordinate of person image.

If you use this dataset please cite:
@inproceedings{PKU_Orientation_2015_01,
	author = {Hong Liu, Liqian Ma},
	title = {},
	booktitle = {},
	volume = {},
	number = {},
	year = 2015,
	month = Jan,
	pages = {},
	address = {},
}
