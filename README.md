This repository contains simplified and adjusted *OpenColorIO ACES* configs, to be used in the production of animation.

This flavor of the *ACES* configuration was tweaked using the original configurations from *Sony Pictures Imageworks*, where all camera-specific color profiles were removed to make things simpler when working in full animation pipelines, which don't need these profiles.

This version of the *ACES* configuration is especially suited for working with [*Blender*](http://blender.org), as Blender does not filter all the color spaces (it ignores families), making it difficult to work with too many of them. This version of the config fixes that by removing unneeded profiles.

If you need to get back specific color spaces, it should be pretty easy to grab them [from the original config](https://github.com/imageworks/OpenColorIO-Configs). Don't forget to copy corresponding LUTs too.

Note that we kept only the latest version of ACES (1.0.3).
