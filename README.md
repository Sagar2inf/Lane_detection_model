# Lane Detection Using Deep Learing
The aim is to build a machine learning model to distinguish the drivable lane road from the obstacles and background in the active road image.
### Dataset
BDD100K dataset is used as reference (BDD100K -https://bdd-data.berkeley.edu/). The levelThe label images of BDD100K dataset were modified  in
such a way that, there are only three colors (pink,blue and black) in the label representing lane area,obstacles and background respectively.
### Library Used
TensorFlow<br>
Matplotlib<br>
Numpy<br>
Pandas<br>
## Unet Model Architecture
Input: N x 3 x H x W where N is the batch size, H and W are the height and width of the input image respectively.<br>
Image Width-128<br>
Image Height-128<br>
Batch Size- 32<br>
