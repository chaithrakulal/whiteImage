import cv2
import numpy as np
img=np.ones((512,512,3),np.uint8)*255
cv2.imshow('white rectangle(color)',img)
cv2.waitKey(0)
cv2.destroyAllWindows()
