# Computer-Vision-Project
Detects grape leaf diseases using machine learning and computer vision. Trained on annotated images via Roboflow, the model classifies leaves as healthy or infected and also identifies pests.

Grape Leaf Disease Detection ->
This project aims to identify and classify diseases in grape leaves using computer vision and machine learning. It helps automate early diagnosis of common grapevine diseases like Black rot, Esca (Black Measles), and Leaf Blight by analyzing images of grape leaves. Early detection enables timely intervention, reduces crop loss, and improves overall vineyard health.
Key Features ->

    Multi-class Classification: Detects multiple disease types and healthy leaves.

    Model Training: Trained on annotated images using CreateML for CoreML deployment.

    Data Pipeline: Includes preprocessing, augmentation, and labeling using Roboflow.

    Performance Metrics: Evaluated using accuracy, precision, recall, and F1-score.

    Deployment Ready: Model exported in .mlmodel format for use in iOS/macOS apps.

Tools & Technologies ->

    CreateML – for building and exporting CoreML models

    Roboflow – for dataset annotation and augmentation

    Python & Jupyter – for preprocessing and data analysis

    CoreML – for on-device machine learning integration

Dataset ->

The dataset consists of high-resolution grape leaf images categorized by disease. It was sourced and labeled using Roboflow, ensuring a clean, balanced dataset for training and evaluation.
Results

The final model demonstrates high accuracy in detecting and distinguishing between diseased and healthy grape leaves. It is optimized for real-time inference and lightweight enough for mobile deployment.
