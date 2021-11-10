# Kalidoface - Become a virtual character with just your webcam!

Kalidoface is perfect for livestreaming, chatting with friends, or just having fun animating your expressions in real time ✨ !

![Kalidoface virtual webcam](https://raw.githubusercontent.com/yeemachine/kalidoface-live2d-models/main/promo/TW-Promo-short.gif)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B75DIY1)

### Use your own Live2D models

Kalidoface works with Live2D rigged characters from Cubism 2.0 and 4.0 files. Upload a <b>.zip</b> of your <b>Live2D runtime folder</b> to save your own characters for face tracking. Files are auto-saved for future visits! [Video guide here!](https://twitter.com/yeemachine/status/1352470128571473920).

![Live2D files support](https://raw.githubusercontent.com/yeemachine/kalidoface-live2d-models/main/FTUE/ftue-live2d.mp4.gif)

### Call a friend

Share your <b>6 digit code</b> with a friend to start a private <b>voice call</b> using virtual avatars!

![Peer to Peer chat](https://raw.githubusercontent.com/yeemachine/kalidoface-live2d-models/main/FTUE/ftue-call.mp4.gif)

### Upload custom background

Add <b>image/video</b> backgrounds, use the <b>color picker</b>, or select <b>chromakey</b> colors for keying in streaming software like OBS.

![Chroma Keys](https://raw.githubusercontent.com/yeemachine/kalidoface-live2d-models/main/FTUE/ftue-bg.mp4.gif)

### Add resizeable stickers

Add <b>image/gif</b> stickers that you can resize and use as props for videos or streaming.

![Chroma Keys](https://raw.githubusercontent.com/yeemachine/kalidoface-live2d-models/main/FTUE/ftue-sticker.mp4.gif)

### OBS Integration

To use Kalidoface directly in a Browser object in OBS, you need the `-use-fake-ui-for-media-stream` and `--allow-file-access-from-files` flags enabled. This is used to get access to the webcam and to allow custom This can be done through a terminal/command prompt. Below is a sample to get it running on mac. Just add the 2 prompts right after the path to your OBS application.

```
/Applications/OBS.app/Contents/MacOS/OBS -use-fake-ui-for-media-stream --allow-file-access-from-files
```

### Standalone Tracking Library

Interested in making your own Vtuber app? **[Kalidoface](https://github.com/yeemachine/kalidokit)** is a JS library that solves for face, full body, and hand tracking.

<a href="https://github.com/yeemachine/kalidokit"><img src="https://github.com/yeemachine/kalidokit/blob/main/docs/kalidokit_glitch.gif?raw=true" alt="Kalidokit Template" width="100%"/></a>

All Live2D models are redistributed under
Live2D's [Free Material License](https://www.live2d.com/eula/live2d-free-material-license-agreement_en.html).
