img =imread('2'.tif');
imgd = im2double(img);
imgd = imnoise(imgd,'salt & pepper',0.02);
f = ones(3,3)/9;
img1 = filter2(f,imgd);
