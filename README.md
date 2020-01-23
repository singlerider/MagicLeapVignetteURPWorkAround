# Magic Leap Vignette Workaround Unity Package

This package will allow an application using Magic Leap on 2019.3 with the Universal Render Pipeline (or Lightweight Render Pipeline) to "fake" a vignette by rendering a shader directly onto quads in front of the main camera.

## Setup

In your application, import this Unity Package under `Assets` > `Import Package` > `Custom Package...`. This will import the assets under your `Assets` root. Organize them however you'd like.

## Usage

Drag the `Vignette` prefab onto the Magic Leap `Main Camera` prefab in your scene. Make sure the transform resembles:

`Position`: `0`, `0`, `0.39`
`Rotation`: `0`, `0`, `0`
`Scale`: `2`, `2`, `2`

The properties of the `Vignette` material can be adjusted to increase or decrease the effect as desired.

## Attribution

This workaround has been graciously provided with permission by Robin Picou of Novelab.
