# .usda library archive

### Overview

Universal Scene Description (USD) is a framework for interchange of 3D computer graphics data, created by Pixar. The framework focuses on collaboration, non-destructive editing, and enabling multiple views and opinions about graphics data.

File formats used by the standard include:

.usd, which can be either ASCII or binary-encoded
.usda, ASCII encoded
.usdc, binary encoded
.usdz, a package file which is a zero-compression, unencrypted zip archive, which may contain usd, usda, usdc, png, jpeg, m4a, mp3, and wav files.

Apple support .usdz files in SceneKit & RealityKit, for 3D model interchange purposes. These USDZ files open up in Safari (AR Quick Look)  & Chrome Browser (SceneViewer) on iOS or iPadOS. 

Reality Composer a USDZ scene builder that fully supports all of USDZ capababilites including extended USD Schema  - interactive behaviours, spatial audio, physics etc 

Currently the best way to convert .usdz to .usda files created by Reality Composer is to use Apple command line utility usdz_converter 0.64 on macOS. 

usage: ./usdzconvert ./USDZ/tapBox.usdz /USDA/tapBox.usda

### List of .usda files that support different scene features


[Interactive tap fires audio file .usda format ](https://github.com/wave-electron/usda_files/blob/master/tap_audio_cube2.usda)   ||   [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5347)

[ Interactive multi scene file .usda format](https://github.com/wave-electron/usda_files/blob/master/multi_scene3.usda)    || [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5351)

[BlendShape morphed cube .usda format](https://github.com/wave-electron/usda_files/blob/master/blendshapes_test.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=4181) (*not currently supported)
