## How to convert video files from mp4 to avi (for mac OS)
#### Requirements:

  - Install [Homebrew](https://brew.sh/) if not already installed (might require your password)
  - In your terminal  run: `brew install ffmpeg`
  - Also in your terminal run: `ffmpeg -i oldFile.mp4 newFile.avi`

Or to complete all this in one step... try running this in your terminal

```bash
echo "Installing Homebrew (this may require your password)"
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

echo "Installing ffmpeg package"
brew install ffmpeg

echo "Running Converter (replace files with your own)"
ffmpeg -i oldFile.mp4 newFile.avi
```
