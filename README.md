# TubeDL
A command line tool that downloads youtube videos

YOU NEED FFMPEG FOR THIS TO WORK

Input: [Program name] [Option] [Link] [Search term] [Video type] [-o]

Options: \
-d, -i, -s, -help\
-d: Download\
-i: Show info\
-s: Search youtube and download most relevant video\
-help: Show this menu

Search term:
    If using "-s" then enter your search term here, if not using "-s" then ignore this

Video type: 144p, 240p, etc or -a for audio
-o: Adding -o opens the file when done

Examples:
    If you wanted to download a video at 720p: tube -d <link> 720p
    If you wanted to download a video and open it after downloaded: tube -d <link> <resolution> -o
    If you wanted to download audio of a video: tube -d <link> -a
    If you wanted to show info about a video: tube -i <link>
    If you wanted to download a video that has something to do with apples: tube -s apples
