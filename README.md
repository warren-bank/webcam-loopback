### [webcam-loopback](https://github.com/warren-bank/webcam-loopback)

Client-side tool to display the video stream from a local webcam

#### Overview:

* very simple script:
  * uses `WebRTC` to obtain the video stream from a local webcam
  * pipes the stream into a `video` element
  * resizes `video` element to match the resolution of the stream

#### Usage:

* visit the [static webpage](https://warren-bank.github.io/webcam-loopback/) hosted on _Github Pages_
* when prompted, grant permission to allow access to the video stream from a local webcam

#### Notes:

* offline:
  * no internet access is required when `index.html` is locally hosted
* if permission for access is denied:
  * most browsers will remember this decision and automatically deny permission on page reload
  * the user will need to manually clear this setting
    * in Chrome: `chrome://settings/content/camera`

#### Legal:

* copyright: [Warren Bank](https://github.com/warren-bank)
* license: [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
