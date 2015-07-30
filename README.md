# video2frames
A python script for converting videos to series of frames for NN training

Run by typing <code>python video2image.py path -o output_dir --skip n --mirror </code>

The path leads to a video or a directory with <b>only</b> videos.

The optional output folder specifies the directory where to save the images. Can be called with -o or --output.
The optional skip parameter specifies every nth frame that should be saved.
When running with the optional <code>--mirror</code> parameter, every second image saved is flipped.
