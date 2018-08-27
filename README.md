# streamify
ffmpeg script to converting Videos for streaming with H264/ACC without noticeable loss in quality.

More info to come, you simply provide a input file. If nothing else is passed, file will be appended with the default TAG

run with -d to see your variables before running

You can remove text from the title with -r "text to remove"

Or you can supply your own output file with -o "/path/to/output" 

Default extension mp4 will be appended unless supplied with -e "extension"

Pass -Q 720 to downscale from 1080 to 720;
