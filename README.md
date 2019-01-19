### mp4 to avi (for mac OS)
Command line tool for converting .mp4 video to .avi for mac OS
#### Requirements:
- [Homebrew](https://brew.sh/)
- [ffmpeg](https://www.ffmpeg.org/)

#### Set-up:  
To install the requirements, run this in your terminal
```bash
echo "Installing Homebrew (this may require your password)"
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

echo "Installing ffmpeg package"
brew install ffmpeg
```
#### File Conversion:
```bash
echo "Running Converter (replace files with your own)"
ffmpeg -i oldFile.mp4 newFile.avi
```
