# Recursive Skeletons

## Tags

[core](../Models-core.md), [testing](../Models-testing.md), [issues](../Models-issues.md)

## Summary

Tests unusual skinning cases with reused meshes and recursive skeletons.

## Operations

* [Display](https://github.khronos.org/glTF-Sample-Viewer-Release/?model=https://raw.GithubUserContent.com/KhronosGroup/glTF-Sample-Assets/main/./Models/RecursiveSkeletons/glTF-Binary/RecursiveSkeletons.glb) in SampleViewer
* [Download GLB](https://raw.GithubUserContent.com/KhronosGroup/glTF-Sample-Assets/main/./Models/RecursiveSkeletons/glTF-Binary/RecursiveSkeletons.glb)
* [Model Directory](./)

## Screenshot

![screenshot](screenshot/screenshot.jpg)

## Description

This model demonstrates tow things:
- Reusing the same mesh multiple times by multiple skins.
- Binding multiple skins to a single skeleton.

The model has:
- 1 scene
- 1 mesh
- 4 large skeleton armatures
- 84 skin bindings.

![Bones and Skins rigging](screenshot/screenshot-skin-rigging.jpg)

Each skin attaches *the same mesh* to different lengths of the skeletons, so we have 21 skins
bound to multiple lengths of each skeleton.

Using skinning in this way might be seen by some as _abusing_ the glTF format, but it's
actually very useful in some circumstances, and can be used by game engines as a stress
test on how to handle uncommon, -but valid- skinned meshes.

## Animations

The model includes a simple animation where each of the 4 columns twists over a different axis,
propagating the affect to the attached child skeletons.

---
## License Information

Copyright 2021 SharpGLTF
CC-BY 4.0 https://creativecommons.org/licenses/by/4.0/
Model by Vicente Penades.


## Legal

&copy; 2017, Cesium. [CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode)

 - Cesium for Everything

#### Assembled by modelmetadata