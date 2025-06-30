#  YOLOv5 Object Detection on Video

This project demonstrates object detection using the YOLOv5 model on images and videos.  
It includes an example of real-time person detection from a video, with results saved as both `.mp4` and `.gif`.

---

##  Project Structure

YOLOv5_Object_Detection/
├── yolov5/ # YOLOv5 source code (from official repo)
├── results/ # Output results
│ └── people.gif # GIF version of the detection video
├── requirements.txt # Required Python packages
├── README.md

---

## Run Detection on Video
python3 detect.py --weights yolov5s.pt --source data/images/people.mp4 --conf 0.4

---

## Result Preview
![Detection Result](results/people.gif)

---
## Requirements
- Python 3.8+
- Required packages listed in `requirements.txt`
- YOLOv5 model weights (e.g., `yolov5s.pt`)
- PyTorch
- OpenCV
- ffmpeg (for GIF conversion)

---

---

## Future Improvements

- Add webcam live detection with OpenCV
- Support for video stream input from IP camera
- Integrate with ROS2 node for real-time robot deployment
- Export detection results as JSON or CSV
- Add object tracking module (e.g., DeepSORT)

---

## License

This project is licensed under the MIT License.

---

## Author

- GitHub: [Gyuhyeok001](https://github.com/Gyuhyeok001)