# openvino_yolov11
如何使用 Intel OpenVINO 2024 及 Ultralytics YOLOv11 完成姿態估測  
by Jack OmniXRI, 2024/10/15  

**[完整Colab範例程式（點擊後可直接執行）](https://colab.research.google.com/github/OmniXRI/openvino_yolov11/blob/main/yolov11_keypoint_detection(sample).ipynb)**

本程式主要包含下列幾大步驟。  
1. 原始 YOLOv11 推論結果
2. 轉換到 OpenVINO IR推論結果
3. 經過 NNCF 壓縮優化推論結果
4. 使用基準測試工具進行比較
5. 連續影片推論展示
如果想要在本機端上運行本範例，可參考Github提供的「安裝步驟」來完成。  

原始程式及進階說明：  
https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/yolov11-optimization/yolov11-keypoint-detection.ipynb
