# Annotation_Coordinate_Maker
This tool uses an input file that lists exon IDs and their coordinates to print a string of coordinates from the exons you select.

Why you might use this program: some genes have large or complicated isoform structures that makes collating coordinates for a given isoform time-intensive and error-prone. This program saves time by allowing the user to input a list of exons and printing out the corresponding list of coordinates.

**Contents:**
Isoform_Coordinate_Maker is a folder that will serve as your workspace.
sample_input_file.csv is a sample of what your input file should look like.
isoform_maker.py is the script that you will execute in command line

**How to use:**
Developer's Note: Please note that the windows version is in beta. I recommend running this in a unix-based system (e.g. MacOS or Ubuntu shell) until testing for Windows is complete.

1. Make sure you have python installed on your computer
2. Update the input file so that it contains your exons and coordinates, but leave the headers intact. You can rename the file however you would like. Your input file(s) should be in the same folder as your python script.
3. Go into command line/terminal
4. Navigate to your directory's location using the cd command. For example:

cd /Users/.../Apollo_Trackmaker/input

Activate your code by entering the following into command line
chmod +x gff2_to_gff3.py

Run your code by entering **one** of the following into command line:


  ./gff2_to_gff3.py


  python isoform_maker_windows.py

A succesful run with the sample input file will print the following:

🧬 Success! 🪰 Here are the coordinates for your selected exons from sample_input_file.csv:
