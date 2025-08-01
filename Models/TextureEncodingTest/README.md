# Texture Encoding Test

## Tags

[core](../Models-core.md), [testing](../Models-testing.md)

## Summary

This asset tests that textures are sampled with correct transfer functions.

## Operations

* [Display](https://github.khronos.org/glTF-Sample-Viewer-Release/?model=https://raw.GithubUserContent.com/KhronosGroup/glTF-Sample-Assets/main/./Models/TextureEncodingTest/glTF-Binary/TextureEncodingTest.glb) in SampleViewer
* [Download GLB](https://raw.GithubUserContent.com/KhronosGroup/glTF-Sample-Assets/main/./Models/TextureEncodingTest/glTF-Binary/TextureEncodingTest.glb)
* [Model Directory](./)

## Screenshot

![screenshot](screenshot/screenshot.png)

## Description

This asset tests that textures are sampled with correct transfer functions: base color and emissive must be decoded from sRGB while metallic-roughness values must be passed as-is.

Additionally, this asset tests that gamma values and/or ICC profiles embedded with image files are ignored as the glTF spec requires.

For each of three material slots, four sample models are provided that use different representations of the same effective material properties.

* Models from the first (leftmost) column use only JSON-stored factors to define their materials.

* Models from the second column represent the same materials using 1x1 textures with no color space metadata.

* Models from the third and fourth columns represent the same materials using 1x1 textures with custom gamma values and custom ICC profiles respectively. Stored 8-bit pixel values are the same as for the second column. An example of incorrect handling of these cases is presented on the following screenshot.

  ![non-ignored_metadata](screenshot/non-ignored_metadata.png)



## Legal

&copy; 2017, Public. [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

 - lexaknyazev for Everything

#### Assembled by modelmetadata