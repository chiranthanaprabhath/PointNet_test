# PointNet_Demo_Model
3D object classification and segmentation 
## Abstract
This is an implementation of PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation using PyTorch.

## 1 Main 3D Data operations


   ### 1.1 .off files visualize

   This dataset consists of .off files that contain meshes represented by vertices and triangular faces. Vertices are just points in a 3D space and each triangle is formed by 3 vertex indices.
   
   <img src="https://raw.githubusercontent.com/chiranthanaprabhath/PointNet_test/main/visualize_with_face.png" width="500">
    
   ### 1.2 3D-point view
   
     we get rid of faces and keep only 3D-points

   <img src="https://raw.githubusercontent.com/chiranthanaprabhath/PointNet_test/main/visualize_without_faces.png" width="500">
   
   ### 1.3 Transforms

    sample points on the surface uniformly.
    
   #### Sample points
   
    <img src="https://raw.githubusercontent.com/chiranthanaprabhath/PointNet_test/main/Transforms.png" width="500">
    
   #### Normalize
   
    <img src="https://raw.githubusercontent.com/chiranthanaprabhath/PointNet_test/main/Normalize.png" width="500">
    
   ### 1.4 Augmentations
   
     objects can have different sizes and can be placed in different parts of our coordinate system.
     
   <img src="https://raw.githubusercontent.com/chiranthanaprabhath/PointNet_test/main/Augmentations.png" width="500">
   

   
