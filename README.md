# Video to frames

Script for exporting frames from video.
Script accept path to video file or folder with video files.

## Installation

* git clone this repo
* `python3 -m venv venv`
* `./venv/bin/pip3 install -r requirements.txt`

## Usage

* Single file: `python3 video_to_frames.py --video_path file.mp4`
* Single file in folder: `python3 video_to_frames.py --video_path folder/file.mp4`
* All files in folder: `python3 video_to_frames.py --video_path folder-with-videos-inside`

Other arguments:

* `--skip_first` - how much frames to skip
    * `--skip_first 5` - will take only every fifth frame
* `--rotate` - need to rotate frame image
    * `None` - no rotation
    * `0` - clockwise
    * `1` - counterclockwise

## License

* MIT
* NeuroCore Team, 2020
