# Generating script for Chebyshev bistable surfaces

<b>Requirements</b><br />
<ul>
  <li>Uses RhinoCommon API</li>
  <li>Open with Rhinoceros 3D + Grasshoper</li>
</ul>

<b>Description</b><br />
A planar surface that can be reconfigured into several 3D target shapes is of importance in numerous fields at different length scales, e.g. aeronautical systems, buildings, and in medicine. Transformation into target shapes is typically an inverse problem solved by mapping a discretized representation of the surface to the flat plane and distorting the periodicity or the shape of each element. As this is a geometric problem, the system is not necessarily mechanically stable when reconfigured into the target shape. Here, a method is proposed for the generation of fabrication surfaces that can be reconfigured into several target shapes, each of which are statically stable. First, the target shapes are discretized as Chebyshev nets. The resulting quadrilateral elements are mapped to the fabrication surface, possibly planar for ease of manufacturing, by accounting for their defects in internal angles. These are accommodated by the lengthening or shortening of the diagonal members through the use of bistable actuators. Using a multi-material 3D printer, we fabricate a planar structure that reconfigures into two distinct and stable target shapes. The proposed method serves as a new direction for the design of material-based reconfigurable systems.

![Screen capture of the Grasshopper scipt](https://raw.githubusercontent.com/timtianchen/chebyshev-bistable-surface/main/readme-grasshopper.png)
