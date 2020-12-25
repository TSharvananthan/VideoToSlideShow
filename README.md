# Video To Slideshow
There's this joke that I always hear when people are running something at really low frames.

**Your video looks like a slideshow being run**

So I asked myself if I can turn this to a reality. I guess I can.

## How It Works
In short...
(1) The video is split into individual frames.

(2) Each frame is put on a slideshow.

(3) The final slideshow is saved.

## Installation
(1) Clone the repo
```
git clone https://github.com/TSharvananthan/VideoToSlideShow
cd VideoToSlideShow
```

(2) Install the required libraries with `pip install -r requirements.txt`


(3) Run video_to_slideshow.py

## Command Line Arguments
| Argument         | What It Does                                                | Mandatory |
|------------------|-------------------------------------------------------------|-----------|
| --filename       | The filename that you would like to convert to a slideshow. | Yes       |
| --ffmpeg_verbose | Would you like verbose in your FFMPEG program.              | No        |
| --keep_frames    | Would you like to keep the split frames?                    | No        |
| --output         | The output name of your file.                               | No        |

## Example
`python3 video_to_slideshow.py --filename example.mp4 --ffmpeg_verbose --output output.pptx`
