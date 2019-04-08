# Ghidra Release Challenge:
###### Taking screenshots of the video:  
###### mplayer -vf framestep=60 -framedrop -nosound ghidra_nsa_training.mp4 -speed 100 -vo jpeg:outdir=video 
###### Running Tesseract OCR to translate the images to text:
###### cd video; ls *.jpg | xargs -t -i tesseract {} {}
$ grep -Ri "flag" *.txt
