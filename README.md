# nikon_desktop_wmu

First off, this is NOT my code, this is my copy of airnef.

> Credits: Airnef Website: http://www.testcams.com/airnef/


# Key Features!

  - One-button click to download all new images and video from the camera, selected on either the camera or computer by criteria
  - Fast downloads - Airnef uses optimized `Media Transfer Protocol (MTP)` parameters for sustained throughput around 2.5 MB/s
  - Realtime download mode - images are transferred to your computer as you shoot them. For cameras without realtime WiFi shooting support an optional staged-realtime process can be used as well.
  - Extensive criteria selection makes it easy to quickly choose which images to download, including by file type (NEF, JPG, MOV, etc...), starting and/or ending capture date, specific camera folders, and media card slot - in any combination. And Airnef will automatically skip over files you've already downloaded!
  - Renaming engine allows you to customize the names of directories and files for images you download
  - Download exec feature lets you launch your favorite image viewing or editing application for each file downloaded
  - Advanced local caching of MTP metadata allows for very fast click-to-download start times
  - Lets you decide the order that files are downloaded, either oldest first or newest first. That way you can start working on the files you want right away instead of waiting for all the files to be downloaded
  - Fault-tolerant operation - Airnef will continuously retry any failed communication/transfer, resuming the download exactly where it left off, even in the middle of a file. This is important when downloading very large video files on marginal wireless connections


### Installation

`nikon_desktop_wmu` requires [Python](https://www.python.org/) v2.7 to run.

Install the dependencies and start the application.

```sh
$ sudo apt-get install python-tk
$ python airnef.pyw
```

