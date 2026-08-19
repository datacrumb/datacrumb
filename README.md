<img width="100%" src="https://t3.ftcdn.net/jpg/20/51/12/90/360_F_2051129030_uod7m0OoRgOBN03AcYRzK9ESwAAAnXdt.jpg" alt="Banner" />

# Computer Vision Engineer

I build computer vision systems that hold up outside the lab — models that keep their accuracy when the lighting shifts, the camera drifts out of focus, or an object shows up at an angle nobody labeled. Most of my work sits at the intersection of deep learning and deployment: training detection and segmentation networks in PyTorch, then compressing and compiling them to run on the hardware that actually exists on site — Jetson boards, ARM CPUs, industrial cameras with a 30ms frame budget. I spend as much time on data pipelines, annotation quality, and failure-case mining as I do on architectures, because in vision the dataset is usually the model.

I believe a vision system is only as good as its worst lighting condition, so I evaluate on hard slices rather than headline mAP — night frames, motion blur, occlusion, small objects, underrepresented classes. I treat every model as something a teammate will have to debug at 2am, which means versioned datasets, reproducible training configs, and visual diagnostics committed next to the code. I would rather ship a smaller network that runs in real time on the customer's existing hardware than a heavyweight one that only wins on a benchmark leaderboard, and I would rather return a calibrated confidence score than a confident wrong answer.

### 🛠️ Tech Stack & Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-6366f1?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-6366f1?style=for-the-badge&logo=tensorflow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-6366f1?style=for-the-badge&logo=opencv&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit-learn-6366f1?style=for-the-badge&logo=scikit-learn&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-6366f1?style=for-the-badge&logo=linux&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-6366f1?style=for-the-badge&logo=aws&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-6366f1?style=for-the-badge&logo=jupyter&logoColor=white) 

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api?username=alexrivera-ai&show_icons=true&theme=dark" alt="GitHub Stats" />
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api/top-langs/?username=alexrivera-ai&layout=compact&theme=dark" alt="Top Languages" />
</p>

### 💡 Expertise
Object Detection & Segmentation — I train and fine-tune detection, instance segmentation, and keypoint models such as YOLO, DETR, Mask R-CNN, and SAM, using anchor tuning, hard-negative mining, and aggressive augmentation for long-tailed classes.

Edge Deployment & Inference Optimization — I move trained networks onto constrained hardware through ONNX/TensorRT conversion, INT8 quantization, structured pruning, and knowledge distillation to meet strict real-time latency budgets.

3D Vision & Camera Geometry — I work with stereo depth, intrinsic and extrinsic calibration, structure-from-motion, point-cloud registration, and multi-view pose estimation where classical geometry outperforms or stabilizes a learned model.

Data Pipelines & Annotation Quality — I design labeling workflows, active-learning loops, and synthetic data generation, then audit label noise and class balance to gain accuracy from the dataset instead of the architecture.

### 🚀 Featured Projects
EdgeDetect — Quantized a YOLOv8-s defect detector to INT8 with TensorRT, cutting inference from 84ms to 11ms per frame on a Jetson Orin Nano while losing only 0.8 mAP.

WeldSeam QC — Deployed a U-Net weld-seam segmentation model on a production line that caught 96.4% of porosity defects and reduced manual inspection labor by 22 hours per week.

StereoDepth Kit — Implemented semi-global block matching with sub-pixel refinement and Zhang calibration, achieving 4.7mm mean depth error at 2 meters on a 12cm stereo baseline.

ActiveLabel — Built an entropy plus core-set active-learning loop that reached target mAP@0.5 of 0.81 using 6,200 labeled images instead of 24,000, cutting annotation spend by roughly $31k.

TrackFlow — Combined ByteTrack with a ReID embedding head to cut identity switches by 63% across 40 hours of multi-camera retail footage at 28 FPS on a single T4.

SynthAug — Generated 45,000 domain-randomized Blender renders that lifted real-world small-object recall from 0.52 to 0.79 with no additional human annotation.

### 🌐 Connect With Me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/alex-rivera-dev) [<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://x.com/alexrivera_tech) [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:alex.rivera@techcraft.io) [<img src="https://img.shields.io/badge/Website-4338CA?style=for-the-badge&logo=googlechrome&logoColor=white" />](https://alexrivera.dev) 
