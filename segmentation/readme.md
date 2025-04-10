Pre-AIFFELthon-main
├── README.md
└── segmentation
    ├── BisenetV2
    │   ├── bisenetv2_19클래스_사전학습.ipynb
    │   ├── bisenetv2_cityscapes2_클래스_파인튜닝.ipynb
    │   ├── bisenetv2_베이스코드.ipynb
    │   ├── bisenetv2_이면도로_22class_파인튜닝_rl01.ipynb
    │   ├── bisenetv2_이면도로_4클래스_파인튜닝.ipynb
    │   └── bisenetv2_이면도로_사전학습.ipynb
    ├── Fastscnn
    │   ├── fastScnn cityscapes 사전학습.ipynb
    │   └── fastScnn cityscapes 이미지 성능 확인하기 .ipynb
    ├── data_loader
    │   ├── __init__.py
    │   ├── cityscapes.py
    │   ├── indobohaeng.py
    │   └── indobohaeng_other.py
    ├── help code
    │   ├── z_indobohaeng 데이터셋 kaggle에서 다운받기.ipynb
    │   ├── z_miou 계산하기.ipynb
    │   ├── z_zip 압축 풀기.ipynb
    │   ├── z_가중치25_2class_파인튜닝_하영님.ipynb
    │   └── z_클래스 4개로 합치기.ipynb
    ├── model_registry.py
    ├── models
    │   ├── BiSeNet_V2.py
    │   ├── __init__.py
    │   ├── bisenetv2.py
    │   ├── fast_scnn.py
    │   ├── fastscnn.py
    │   ├── model_registry.py
    │   └── modules.py
    ├── modules.py
    ├── python 실행파일
    │   ├── demo.py
    │   ├── eval.py
    │   ├── train.py
    │   └── transform_cv2.py
    ├── readme.md
    └── utils
        ├── __init__.py
        ├── loss.py
        ├── lr_scheduler.py
        ├── metric.py
        └── visualize.py
