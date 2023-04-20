# 3D-Point-Cloud-Reconstruction
This repository consists of a novel implementation of 3D point cloud reconstruction

3D data is at the forefront of many upcoming technologies such as Virtual Reality, Augmented Reality, self driving cars. Point clouds are especially very useful in scientific applications and self driving cars which use LiDARs to generate point cloud data. This work we build a novel architecture to generate 3D point clouds conditioned on single 2D images. Our architecture uses a combination of preojection based and chamfer's distance based loss to train the network. This method enables us to generate a 3D point cloud which preserves the shape and the structure of the image. We train and test the model on shapenet dataset. This method helped us achieve comparitively better results than models which used solely projection based or Chamfer's distance based approaches.


<img width="327" alt="Screenshot 2022-12-10 at 2 27 06 AM" src="https://user-images.githubusercontent.com/56645758/233227578-3533890a-d3fd-48d0-88cb-8b2c38a54acb.png">
<img width="327" alt="Screenshot 2022-12-10 at 2 29 46 AM" src="https://user-images.githubusercontent.com/56645758/233227574-acc5b34d-68f8-4df8-9f4d-27061e74dfc1.png">
