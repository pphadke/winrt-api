---
-api-id: P:Windows.Perception.Spatial.Surfaces.SpatialSurfaceMeshOptions.SupportedVertexPositionFormats
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVectorView<Windows.Graphics.DirectX.DirectXPixelFormat> SupportedVertexPositionFormats { get; }
-->

# Windows.Perception.Spatial.Surfaces.SpatialSurfaceMeshOptions.SupportedVertexPositionFormats

## -description
Gets a list of the vertex position formats that the system can generate a vertex buffer in.

## -property-value
The supported vertex buffer formats.

## -remarks
Supply a value from this list to the SpatialSurfacesMeshOptions.VertexPositionFormat property when calling SpatialSurfaceInfo.TryComputeLatestMeshAsync to request vertex buffers in that format.

## -examples

## -see-also
