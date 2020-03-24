Data for "Sparse long-range connections in visual cortex for cost-efficient small-world networks" 
Seungdae Baek, Youngjin Park, and Se-Bum Paik*

Modified MNIST datasets

To separately examine the contribution of high and low-frequency information contained in sample images, we designed three types of modified MNIST datasets. Details are as follows:

Type 1: shape. The “shape” dataset was designed by arranging a hand-written digit of 8 x 8 pixels in the center of a 28 x 28 pixels image. The dataset consists of eight categories depending on the number in the center (1 to 8). For this dataset, only local information (shape) of the digits is required for classification.


Type 2: position. The “position” dataset was made by the following procedure. First, two digits of 8 x 8 pixels were randomly chosen. Second, these two digits were allocated in a 28 x 28 image, with one of the following position alignments: horizontal (top, middle, bottom), vertical (left, middle, right), or diagonal (45°, 135°). This dataset also consists of eight categories depending on the position only where the digits are located. Note that the shape of each number is irrelevant for classification.


Type 3: shape-position. The “shape-position” dataset was made by the following procedure. First, a 28 x 28 pixel area was divided into four 14 x 14 areas. Second, two diagonally aligned areas were selected (either 45° or 135°). Third, one of two digits, either “7” or “9”, composed of 8 x 8 pixels was inserted into each selected area. This dataset consists of eight categories depending on both the shape and position of the digits. The reason we chose “7” and “9” among ten numbers is to adjust the difficulty of the task to be similar to that of the previous tasks. Note that this dataset requires both local information (shape) and global information (position) of the digits for classification. 
