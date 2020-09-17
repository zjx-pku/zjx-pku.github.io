# aframe-vive-controls

A-Frame module for HTC Vive featuring several navigation modes.

# Usage

```
<a-entity id="cameraRig" position="300 200 300" vive-control-rig>
  <a-camera id="viewpoint"></a-camera>
</a-entity>
```

## Menu (left hand)

| Button | Action |
| ------------- |:-------|
| Trigger | switch through modes |
| Trackpad | activate mode |

## Navigation mode: Laser

| Button | Action |
| -------|:-------|
| Trigger | Teleport |
| Grip Button | move up |
| Trackpad | move down |

## Navigation mode: fly-head

| Button | Action |
|--------|--------|
| Trigger | move in viewing direction |
| Trigger + Trackpad | move in viewing direction backwards |
| Trackpad | turn left |
| Grip | turn right |


## Navigation mode: fly-hand

| Button | Action |
|--------|--------|
| Trigger | move in direction of laser |
| Trigger + Trackpad | move in direction of laser backwards |
| Trackpad | turn left |
| Grip Button | turn right |

