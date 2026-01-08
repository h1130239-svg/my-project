---
layout: course_layout
title: "CNN chapter04"
---
# 四、實驗結果 


透過抓取隨機的環境照片到MatLab中並使用下列程式碼便可以開始辨認。

I = imread("download.jpg");                         //載入一張新圖像

I = imresize(I, [227 227]);                         //調整測試影像的大小

[YPred,probs] = classify(trainedNetwork_1,I);      //對測試圖像進行分類

imshow(I)

label = YPred;

title(string(label) + ", " + num2str(100*max(probs),3) + "%");

<img width="438" height="443" alt="Annotation 2026-01-08 140719" src="https://github.com/user-attachments/assets/76581618-ad91-43ba-a873-2ca093cd9cc0" />

得出這張照片百分之99.9為雨林
