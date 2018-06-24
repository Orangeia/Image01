# Image01
<カメラ画像を取得するコードcamera01.py>


1行目：import cv2でopencvをインポート。

3行目：cap = cv2.VideoCapture(0)でVideoCaptureオブジェクトを取得。

7~9行目：frameに読み取った画像を格納し、imshowで表示。

13行目：cap.release()でVideoCaptureオブジェクトを解放。
