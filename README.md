## Update
-> testing out with different parameters for perfect model

-> try exporting the model, (only canb be imported to blender). 

-> Recording video of a complete room and rendering and moving inside the space.


##NEW MODEL

-> trying to explore a new model called nerfstudio

-> easy to compare between instant ngp results and nerf studio

Instant ngp sample video is given below.


## Installation

If you have Windows, download one of the following releases corresponding to your graphics card and extract it. Then, start `instant-ngp.exe`.

- [**RTX 3000 & 4000 series, RTX A4000&ndash;A6000**, and other Ampere & Ada cards](https://github.com/NVlabs/instant-ngp/releases/download/continuous/Instant-NGP-for-RTX-3000-and-4000.zip)
- [**RTX 2000 series, Titan RTX, Quadro RTX 4000&ndash;8000**, and other Turing cards](https://github.com/NVlabs/instant-ngp/releases/download/continuous/Instant-NGP-for-RTX-2000.zip)
- [**GTX 1000 series, Titan Xp, Quadro P1000&ndash;P6000**, and other Pascal cards](https://github.com/NVlabs/instant-ngp/releases/download/continuous/Instant-NGP-for-GTX-1000.zip)



##HOW TO RUN IT

instant nerf setup and execution

-download the necessory environment from the links

vscode
https://visualstudio.microsoft.com/vs/community/


cuda (to check type nvcc --version on cmd)
https://developer.nvidia.com/cuda-12-3-1-download-archive?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local


download nvida optics
https://developer.nvidia.com/designworks/optix/download




python scripts/colmap2nerf.py --colmap_matcher exhaustive --run_colmap --aabb_scale 16 -- data/test







convert the video to image

python C:\Users\Manoj D\Desktop\data>python C:\ngp\instant-ngp\scripts\colmap2nerf.py --video_in test.MP4 --video_fps 2 --run_colmap --aabb_scale 16





https://github.com/manoj4724/3d-nerf/assets/65806100/e30abdd4-2ccf-4bb2-ad60-6531ce487d23



https://github.com/manoj4724/3d-nerf/assets/65806100/efd252a4-4756-4794-82a8-7dd98913c89f



