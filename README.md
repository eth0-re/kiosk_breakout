# Kiosk Breakout
Goal of the project is to implement an open-source, portable and offline-capable kiosk breakout toolkit.

## Features
Current features include:
### Common Dialogs
* [x] File upload
* [x] Print
* [x] Save Password
* [x] Popup blocker
* [x] Share Content
### File Downloads
* [x] Download arbitrary extensions
* [x] Open inline PDF
### Copyable Links
* [x] Linux Root
* [x] Windows C:\
### Trigger User Media
* [x] Camera
* [x] Screen Share
### Cickable URIs
* [x] Generated list based on flamebarke's list
* [x] Disable button after click
### Public links
* [x] Google
* [x] Firefox/Chrome/Edge Addons
* [x] Invalid Certs
* [x] EICAR

## Usage
Host the file on any plaintext webserver. There's no dynamic content, so plain nginx/apache or python3 -m http.server will do.

## Todo
* [ ] Built-in file editor & downloader using Monaco
* [ ] Built-in hex editor & downloader, possibly using https://github.com/michbil/hex-works or similar
* [ ] On-screen keyboard for touchscreens
* [ ] Categorise/popularity of URIs
* [ ] More tracking of which breakouts have been attempted
* [ ] List of deprecated breakouts for testing old browsers (Like pre-2017 "self.close() & pre-2019 fingerprinting installed apps based on cache-response times")
* [ ] Attempt to crash browser (open large number of While(true) tabs)
* [ ] WebRTC Port Scanner
* [ ] Identify legitimate browser plugins that would be useful for breakouts
* [ ] Server-side receiver for file exfiltration (to avoid needing a separate channel for exfil)
* [ ] Server-side receiver for webcam/microphone/screen share exfil

## Maybe
* [ ] Implement Java Applet breakouts
* [ ] Implement Flash breakouts
