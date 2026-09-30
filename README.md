# License Plate Detection

This repository contains the notebook used for the license plate detection project.

## Results

### YOLOv8 Training Curves

![YOLOv8 training curves](images/training_curves.png)

### YOLOv8 Confusion Matrix

![YOLOv8 confusion matrix](images/confusion_matrix.png)

### YOLOv8 Inference Samples

![YOLOv8 test predictions](images/yolo_test_predictions.png)

### Faster R-CNN Inference Samples

![Faster R-CNN predictions](images/faster_rcnn_predictions.png)

### SSD Inference Samples

![SSD predictions](images/ssd_predictions.png)

## Notebook

- `License_plate_detection.ipynb`

## Images

The screenshots used above are stored in the `images/` folder so they render directly in GitHub.

## Notes

- Set `NGROK_AUTH_TOKEN` as an environment variable before running the Streamlit/Ngrok cell.
- The notebook includes training, evaluation, and deployment steps for YOLOv8, Faster R-CNN, and SSD.