# HTTP_downloader
program in c language  that takes in input (on the command line) the URL of an object to be downloaded via HTTPS (using HTTP v1.1), and the number of connections through which different parts of the object will be retrieved using the "Range" option. 
The program will put the parts together and write the output into a file called image.gif. The name  of the files containing the parts of downloaded content are named as part_i, where i is an index. along with the reconstructed output file. The part_i files are remained in the system after recomposing the original file.
