---
-api-id: T:Windows.UI.Input.Spatial.SpatialPointerPose
-api-type: winrt class
---

<!-- Class syntax.
public class SpatialPointerPose : Windows.UI.Input.Spatial.ISpatialPointerPose, Windows.UI.Input.Spatial.ISpatialPointerPose2
-->

# Windows.UI.Input.Spatial.SpatialPointerPose

## -description
Represents spatial pointing information, such as the user's head gaze, for use in targeting gestures and voice interactions.

## -remarks
Apps should intersect the user's head gaze ray with their holograms or with the spatial mapping mesh to render cursors and determine what the user is intending to interact with.

On HoloLens, interactions should generally derive their targeting from the user's gaze, rather than trying to render or interact at the hand's location directly. Once an interaction has started, relative motions of the hand may be used to control the gesture, as with the Manipulation or Navigation gesture.

## -examples

## -see-also
