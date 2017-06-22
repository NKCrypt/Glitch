# Glitch
Randomly changes binary file data in order to create glitch art.

# Usage
./glitch <infile> [percent] [outfile]

	 infile: the file to take as input
	
    percent: the percentage of the file to corrupt, by default, 0.1%
	
    outfile: the file to output, by default <filename>-glitched.<fileext>
    
Play around with different values for percent, 0.1 seems to work okay for most image formats, 0.01 worked okay for video. 
Also, try different filetypes and share your results! I noticed different image viewers sometimes perform differently with 
these glitched images. They either display the image differently or not at all. Windows Photo Viewer worked best for me.
As a result, I usually screenshot the glitches from Windows Photo Viewer so they always display "correctly".
