---
-api-id: P:Windows.Perception.Spatial.Surfaces.SpatialSurfaceMeshOptions.SupportedTriangleIndexFormats
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVectorView<Windows.Graphics.DirectX.DirectXPixelFormat> SupportedTriangleIndexFormats { get; }
-->

# Windows.Perception.Spatial.Surfaces.SpatialSurfaceMeshOptions.SupportedTriangleIndexFormats

## -description
Gets a list of the triangle index formats that the system can generate an index buffer in.

## -property-value
The supported index buffer formats.

## -remarks
Supply a value from this list to the SpatialSurfacesMeshOptions.TriangleIndexFormat property when calling SpatialSurfaceInfo.TryComputeLatestMeshAsync to request index buffers in that format.

## -examples

## -see-also
