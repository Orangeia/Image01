# Image01
カメラ画像を取得するコード


import cv2でopencvをインポート。

cap = cv2.VideoCapture(0)でVideoCaptureオブジェクトを取得。

frameに読み取った画像を格納し、imshowで表示。

cap.release()でVideoCaptureオブジェクトを解放。
