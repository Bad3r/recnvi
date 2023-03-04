
# recnvi

`recnvi` is a shell script that uses ffmpeg and NVENC to record the screen and save it as an MP4 video file. This script requires an Nvidia graphics card with NVENC support. The repository includes the script and a `dict` folder that contains dictionaries of adjectives, nouns, and verbs for generating random filenames.

## Usage

1. Clone the repository:
```sh
$ git clone https://github.com/bad3r/recnvi.git
```
2. Navigate to the `recnvi` directory:
```sh
$ cd recnvi
```
3. Make the `recnvi` script executable:
```sh
$ chmod +x recnvi.sh
```
4. Run the script:
```sh
./recnvi
```

5. Press `Ctrl+C` to stop recording. You will be prompted to upload the video to R2.

## Dependencies

* X11
* [ffmpeg](https://ffmpeg.org/)
* [NVIDIA Video Codec SDK](https://developer.nvidia.com/nvidia-video-codec-sdk)
* rclone - for upload to S3 or S3-like bucket. I use CF R2.

## License

`recnvi` is licensed under the [MIT License](LICENSE).


