# Readme - File Organizer Script

This batch script organizes files from the Downloads folder into respective directories such as Music, Videos, Pictures, Documents, Installers, Zip files, and Others.

## Features
- Creates necessary directories if they do not exist.
- Moves files based on their extensions to the appropriate folders.
- Avoids file name conflicts by appending a random number to the file name if a file with the same name already exists in the target directory.
- Provides a summary of moved files and displays it in a message box.

## Folders
- **Music**: `.mp3`, `.wav`, `.wma`, `.aac`, `.ogg`, `.flac`
- **Documents**: `.pdf`, `.txt`, `.xlsx`, `.html`, `.doc`
- **Videos**: `.mov`, `.wmv`, `.mp4`, `.avi`, `.avchd`, `.flv`, `.mkv`
- **Pictures**: `.jpg`, `.png`, `.webp`, `.jpeg`, `.ico`, `.bmp`, `.tiff`, `.tif`, `.eps`, `.gif`
- **Installers**: `.msi`, `.exe`
- **Zip files**: `.zip`
- **Others**: All other file types

## Usage
Run the `DownloadCleaner.exe` file. It will create the necessary directories if they do not exist and move files from the Downloads folder to the respective directories.

## Message Box Summary
After the script completes, it will display a message box summarizing the count and location of moved files.

## Potential Virus Detection
- **Unsigned Application**:
  - The .exe file may be detected as a virus because it is an unsigned application. Rest assured, this is a false positive.

## License
This script is provided under an MIT License.

## Authors
This script was created by [FuZeee](https://github.com/FuZeee).

## Version History
- Version 1.0: Initial release of the script.

## Support
For issues or questions, please contact via [GitHub Link](https://github.com/FuZeee/RLVideoManager/issues).

Thank you for using this script!
