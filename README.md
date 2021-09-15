# PR100 PR200 Trailcam time.txt format

The cheap PR100 & PR200 trailcams from 2019-2020 use a file named time.txt
to set the time (for timestamps on the media files) and to configure the 
shooting of images and video.

Example:

2019-11-11 12:59:59 234N

The time format is pretty obvious. The third field is not.

The four characters are defined as follows:

First digit is 
  * 1 Images only
  * 2 Video only
  * 3 Images then Video

Second digit is
  * 1-5 number of images to capture
  
Third digit is length of video to record
  * 1 - 5 seconds
  * 2 - 10 seconds
  * 3 - 20 seconds
  * 4 - 30 seconds

The final letter is whether to record the timestamp in the image/video
  * Y - Yes
  * N - No

Hope this helps!

Chris.
  
