# Performance & Benchmarks

These are gameplay entities, not particle effects. They steer, avoid obstacles, and could react to the player. Skinned meshes allow the C# scripts to drive the rotation and position accurately for logic and colliders.

|FPS|Fish Count|Platform|Specs|
|-|-|-|-|
|60|1700|Desktop|i7-4790k RTX-3060|
|60|600|Desktop|i5-1035G1 Intel Iris Xe Graphic|
|60|1200|Desktop|i5-4690k, GTX 1050ti 
|30|870|WebGL|i7-4790k RTX-3060|
|30|670|WebGL|i5-1035G1 Intel Iris Xe Graphic|
|30|620|WebGL|i5-4690k, GTX 1050ti 
|30|...|Android|...|

## Note on Vertex Shader Animation (not implmented)

Along with the current system, later, could be implemented Vertex Animation solution for massive groups of fish renderer far away in the background.