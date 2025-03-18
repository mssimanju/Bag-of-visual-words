A practice of extracting feature from images for matching based on SIFT.

After getting all the keypoints and its descripters, a bag of visual words is created and used for macthing.

The image files I got from University of Macau are too large to upload, please put your images in './data/images' and have a try.

Matching using brute force matcher

<img width="683" alt="联想截图_20250318160636" src="https://github.com/user-attachments/assets/8c41d830-854c-44ca-b71a-75c016f1d650" />

Matching using flann

<img width="683" alt="联想截图_20250318160705" src="https://github.com/user-attachments/assets/3f0b215d-0371-4b00-9d94-39cd6da1fa27" />


The bags of words

<img width="687" alt="联想截图_20250318160724" src="https://github.com/user-attachments/assets/15258fc7-a2fa-4fdf-ad09-db00010d964b" />

Select a image for matching, it matches 100% to itself

<img width="707" alt="联想截图_20250318160740" src="https://github.com/user-attachments/assets/a7a75687-fd4b-4172-aaf0-56fc4db25e9e" />

The following are the most similar images selected after matching with 0.6684 and 0.3147 similarity 

<img width="713" alt="联想截图_20250318160748" src="https://github.com/user-attachments/assets/ca1409c9-e71b-4f20-bc92-cc7ec5a55639" />
<img width="705" alt="联想截图_20250318160756" src="https://github.com/user-attachments/assets/68474369-108a-47ed-942a-e6c000e8d713" />
