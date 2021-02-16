# .usda library archive

### Overview

Universal Scene Description (USD) is a framework for interchange of 3D computer graphics data, created by Pixar. The framework focuses on collaboration, non-destructive editing, and enabling multiple views and opinions about graphics data.  

Introduction to USD => [https://graphics.pixar.com/usd/docs/index.html](https://graphics.pixar.com/usd/docs/index.html)

#### File formats used by the standard include:

.usd, which can be either ASCII or binary-encoded
.usda, ASCII encoded
.usdc, binary encoded
.usdz, a package file which is a zero-compression, unencrypted zip archive, which may contain usd, usda, usdc, png, jpeg, m4a, mp3, and wav files.

Apple support .usdz files in SceneKit & RealityKit, for 3D model interchange purposes. These USDZ files open up in macOS (file Preview),  Safari broswer (AR Quick Look)  & Chrome browser (SceneViewer) on iOS or iPadOS. 

Reality Composer a USDZ scene builder that fully supports all of USDZ capababilites including extended USD Schema  - interactive behaviours, spatial audio, physics etc 

Currently the best way to convert .usdz to .usda files created by Reality Composer is to use Apple command line utility usdz_converter 0.64 on macOS. 

usage: ./usdzconvert ./USDZ/tapBox.usdz /USDA/tapBox.usda

### List of .usda files that support different scene features

#### Anchor Types

1. [Horizontal anchor file .usda format](https://github.com/wave-electron/usda_files/blob/master/horizontal_anchor.usda)   ||  [.usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5383)

2. [Vertical anchor file .usda format](https://github.com/wave-electron/usda_files/blob/master/vertical_anchor.usda)   ||   [.usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5377)

3. [Image anchor file .usda format](https://github.com/wave-electron/usda_files/blob/master/image_anchor.usda)    ||    [.usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5379)

4. [Face anchor file  .usda format](https://github.com/wave-electron/usda_files/blob/master/face_anchor.usda)     ||     [.usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5381)

*Note: Object anchors are not yet supported in USDZ files (only Reality Files)

#### Material/Shader 

1. [Aluminium material setting file .usda format](https://github.com/wave-electron/usda_files/blob/master/aluminium_material_settings.usda)   || [.usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5367)

2. [Brass material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/brass_material_settings.usda)   || [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5365)

3. [Bronze material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/bronze_material_settings.usda)   || [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5363)

4. [Car paint material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/car_paint_material_settings.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5369)

5. [Glossy paint material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/glossy_paint_material_settings.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5347)

6. [Gold paint material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/gold_paint_material_settings.usda)    ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5361)

7. [Matte material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/matte_material_settings.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5373)

8. [Plastic material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/plastic_material_settings.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5371)

9. [Rubber material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/rubber_material_settings.usda)    ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5357)

10. [Steel material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/steel_material_settings.usda)    ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5359)

11. [Terracotta material settings file .usda format](https://github.com/wave-electron/usda_files/blob/master/terracotta_material_settings.usda)  ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5355)


#### Interactions

1. [Interactive tap fires audio file .usda format ](https://github.com/wave-electron/usda_files/blob/master/tap_audio_cube2.usda)   ||   [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5347)

2. [ Interactive multi scene file .usda format](https://github.com/wave-electron/usda_files/blob/master/multi_scene3.usda)    || [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5351)

#### Physics Simulations

1. [Force applied to cube - on loop](https://github.com/wave-electron/usda_files/blob/master/cube_with_force.usda)    ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=5353)


#### Unsupported Features in iOS

[BlendShape morphed cube .usda format](https://github.com/wave-electron/usda_files/blob/master/blendshapes_test.usda)   ||  [ .usdz format - viewable in browser on iOS](https://usdzshare.com/?ug-gallery=photo-detail&photo_id=4181) (*not currently supported)
