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

Info:\
    If you paste a youtube playlist link instead of a video then it will go through all of the videos in the playlist and download them (-o does nothing when downloading playlists). Whenever selecting a resolution TubeDL will download the videos that have your selected resolution, if not, then you will be prompted to select a differint one.

Search term:\
    If using "-s" then enter your search term here, if not using "-s" then ignore this

Video type: 144p, 240p, etc or -a for audio\
    -o: Adding -o opens the file when done

Examples:\
    If you wanted to download a video at 720p: tube -d <link> 720p\
    If you wanted to download a video and open it after downloaded: tube -d <link> <resolution> -o\
    If you wanted to download audio of a video: tube -d <link> -a\
    If you wanted to show info about a video: tube -i <link>\
    If you wanted to download a video that has something to do with apples: tube -s apples
