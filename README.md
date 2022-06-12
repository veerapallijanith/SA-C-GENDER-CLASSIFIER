

# SA-C-GENDER-CLASSIFIER
# Algorithm
1. First install deepface library
2. to install deepface library use the command pip install deepface
3. And also import cv2 and matplotib.pyplot
4. Then read the image,an then show the image

## Program:
```
/*
Program to implement 
Developed by   : VEERAPALLI JANITH CHOWDARY
RegisterNumber :  212220230057
*/
```

```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('NTR.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:

![out](https://user-images.githubusercontent.com/75234814/173217272-48db132c-83ae-4301-9707-bf4add9363b4.png)

YOUTUBE LINK :
https://youtu.be/oJVkApRN59k
