# Youtube Video or Audio Extractor for Android
## A bash script simplifying yt-dlp command line usage on android.
## --- Steps ---
1. Install termux on android
2. Install termux-media-scan api on android
3. Clone [yt-dlp](https://github.com/yt-dlp/yt-dlp) in desired directory
4. Add executable functionality to yt-dlp.sh in the cloned yt-dlp repository with 'chmod +x yt-dlp.sh'
5. Place the script, 'script', in bin folder at home directory or make a new directory ~/bin/scripts.
6. Add executable functionality to the script by using chmod +x script.
7. Edit .bashrc file with your favorite text editor to include a path variable pointing to the location of the script, for example 'export PATH=$PATH:~/bin/yt-dlp' and 'export PATH=$PATH:~/bin/scripts'
8. Now, go to a directory of your choice in termux, type script name, and enter, and follow the prompts.
