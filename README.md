# VP9 T-MCU BITSTREAM PATCH 

## Description
The code patches presented in this project fix (hardcode) certain encoding characteristics in the WebM VP9 encoding SDK to construct bitstreams that are compatible for tiling. This is different individual streams can be combined on a bitstream level into one encoded frame (and frame header). 

The patches are adjunct with the following paper:
Simon N.B. Gunkel, Rick Hindriks, Yonatan Shiferaw, Sylvie Dijkstra-Soudarissanane, Omar Niamut. 2024. VP9 bitstream-based Tiled Multipoint Control Unit: Scaling simultaneous RGBD user streams in an immersive 3D communication system. In ACM Multimedia Systems Conference 2024 (MMSys ’24), April 15–18, 2024, Bari, Italy. ACM, New York, NY, USA, 11 pages.
https://doi.org/10.1145/3625468.3647608

The paper provides more details regarding the code patches.

When using the patches for further modification or your own research please reference the above paper.

Note: The patches in this project are only functional in combination with the code of the WebM VP8/VP9 Codec SDK:
https://chromium.googlesource.com/webm/libvpx/+/8874873bef4089164a697c62fbfdeeaa1cc678ac

## License
Please see the attached license file.
