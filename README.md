This Nerfstudio project takes in different viewpoint images of a focused object and converts it into a nerfstudio implementable 3d model view. 
Preprocessing of the images include compressing the images and reconstruction of points and observation point of views (camera poses) in colmap into transformers.json, cameras.bin and points3D.bin files.
The generated model is trained under nerf engine to initialize the scene and camera parameters for training the neural radiance field (NeRF). NeRFStudio will start training on the images and camera data, learning to represent the scene as a continuous volume.
After the scene has been trained, you can render high-quality views of the 3D scene from any perspective.

This project is highly motivated by https://github.com/nerfstudio-project/nerfstudio and acknowledges their efforts in creating and open sourcing such a revolutionary software suite.
It is advised to have all the prerequisities mentioned in https://github.com/nerfstudio-project/nerfstudio to be able to run this project successfully.
