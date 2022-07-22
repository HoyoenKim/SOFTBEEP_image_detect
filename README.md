1. camera on
sudo raspi-config
set camera on

2. camera test
cd rpi-object-detection
cd src
cd camear-test
python cv_camera_test.py

3. object detection
cd yolov5
python detect.py --source 0 --weights yolov5s.pt --conf 0.25