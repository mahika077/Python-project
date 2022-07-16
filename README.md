# Python-project
import cv2

original_image=cv2.imread('lilly.jpeg')

gray_image=cv2.cvtColor(original_image,cv2.COLOR_BGR2GRAY)

cv2.imshow('Original image',original_image)

cv2.imshow('Gray Image',gray_image)

cv2.imwrite('lilly.png',gray_image)

cv2.waitKey(0)
