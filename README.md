# Vision Apps on Nvidia Jetson Nano

## Native Compilation of Sample Applications and Demos
```bash
git clone https://github.com/Rajsoni03/vision_apps_jetson.git
cd vision_apps_jetson
make -j # add dbg=1 to make debug build
```

## Running Samples and Demos

Go to the samples directory:
```bash
cd ./bin/aarch64/linux/release
```

Run each sample of interest by using the name of the sample. 
Availiable samples are:
```bash
./nvx_demo_feature_tracker
./nvx_demo_feature_tracker_nvxcu
./nvx_demo_hough_transform
./nvx_demo_motion_estimation
./nvx_demo_stereo_matching
./nvx_demo_video_stabilizer

./nvx_sample_nvgstcamera_capture
./nvx_sample_object_tracker_nvxcu
./nvx_sample_opencv_npp_interop
./nvx_sample_opengl_interop
./nvx_sample_player

./nvx_custom_color_conversion
./nvx_custom_quad_video_player
./nvx_custom_quad_video_player_threaded 
```

## Docs

[VisionWorks 1.5.3 Documentation](https://developer.nvidia.com/embedded/dlc/visionworks-1-5-3-documentation-for-l4t-24-1) (As VisionWorks 1.6 docs not Availiable)