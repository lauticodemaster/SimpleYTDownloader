# SimpleYTDownloader

SimpleYTDownloader is a lightweight and easy-to-use YouTube downloader for Windows.  
It was created to allow anyone to download videos or music from YouTube without using commands or having technical knowledge.

The program works through a simple menu and automates the entire process.



## Features

- Download YouTube videos in MP4 format  
- Download YouTube audio in MP3 format  
- Multiple quality options for both audio and video  
- Batch download support (multiple URLs at once)  
- Automatic folder organization  
- Basic error handling to prevent common issues  



## How It Works

1. Open the file `lista.txt`
2. Paste the YouTube URLs **one per line**
https://youtu.be/example1
https://youtu.be/example2

yaml
Copiar código
3. Save and close the file
4. Double-click `DESCARGAR_YOUTUBE_MENU.bat`
5. Choose an option from the menu by typing the number and pressing Enter

No command line usage is required.



## Available Download Options

### Audio (MP3)

- Low quality  
- Medium quality  
- High quality  

### Video (MP4)

- 360p  
- 480p  
- 720p  



## File Organization

- Audio files are saved in:
Descargas musica

css
Copiar código

- Video files are saved in:
Descarga videos

yaml
Copiar código

If any folder does not exist, it will be created automatically.



## Error Handling

The program automatically:

- Creates `lista.txt` if it does not exist  
- Warns the user if `lista.txt` is empty  
- Creates required folders if missing  
- Prevents crashes caused by common user mistakes  



## Requirements

- Windows  
- yt-dlp  
- ffmpeg  

The following files must be located in the same folder as the menu:

yt-dlp.exe
ffmpeg.exe
ffprobe.exe

yaml
Copiar código

## Target Audience

This project is intended for:

- Users with no technical experience  
- People who prefer menus instead of commands  
- Anyone who wants a fast and simple way to download YouTube content  


## Disclaimer

This project is provided for educational and personal use only.  
Users are responsible for complying with YouTube's terms of service and local laws.


## License

This project is licensed under the MIT License.
