# Third-party notices

Field Photo Labeler uses the following third-party code, libraries and models.
All are loaded at runtime from a CDN unless marked *bundled*.

| Component | Used for | Licence | Source |
|---|---|---|---|
| jsPDF 2.5.1 | PDF export | MIT | https://github.com/parallax/jsPDF |
| svg2pdf.js 2.2.3 | SVG → PDF in export | MIT | https://github.com/yWorks/svg2pdf.js |
| JSZip 3.10.1 | ZIP export | MIT (dual MIT/GPLv3, used under MIT) | https://github.com/Stuk/jszip |
| MediaPipe Tasks Vision 0.10.14 | Face & person detection (Privacy Blur) | Apache-2.0 | https://github.com/google-ai-edge/mediapipe |
| BlazeFace short-range model | Face detection | Apache-2.0 | https://ai.google.dev/edge/mediapipe/solutions/vision/face_detector |
| EfficientDet-Lite2 (COCO) model | Person detection | Apache-2.0 | https://ai.google.dev/edge/mediapipe/solutions/vision/object_detector |
| ONNX Runtime Web 1.20.1 | Runs the number plate model | MIT | https://github.com/microsoft/onnxruntime |
| YOLOv9-t licence plate detector (`models/yolo-v9-t-640-license-plates-end2end.onnx`, *bundled*) | Number plate detection | MIT, Copyright (c) 2024 ankandrew — full text in [`models/LICENSE-open-image-models.txt`](models/LICENSE-open-image-models.txt) | https://github.com/ankandrew/open-image-models |
| YOLOv9 architecture (basis of the model above) | — | see upstream | https://github.com/WongKinYiu/yolov9 |
| Red Hat Display / Red Hat Text, Open Sans, Share Tech Mono | UI and label fonts | SIL Open Font License 1.1 | https://fonts.google.com |

## Reviewed but not used

- https://github.com/JaiDoshi777/AI-for-Privacy-Automated-License-Plate-Blurring —
  OpenCV Haar-cascade plate blurring. Evaluated on 8 test car photos (found about
  3/8 plates vs 8/8 for the YOLOv9 model). No code from it is included.
