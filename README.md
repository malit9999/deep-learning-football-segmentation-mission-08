# Bootcamp Mission 08 - U-Net 기반 축구 경기 객체 분할

## 1. 개요
축구 경기 이미지에서 선수, 공, 경기장 등 다양한 객체를 픽셀 단위로 분할한 미션입니다.

## 2. 목표
U-Net 계열 모델을 구현하고 Semantic Segmentation 성능을 비교하는 것을 목표로 했습니다.

## 3. 사용 기술
- Python
- numpy
- matplotlib
- opencv-python
- Pillow
- torch
- torchvision
- optuna
- kagglehub

## 4. 주요 기능
- Segmentation 데이터 전처리
- U-Net 구현
- U-Net++ 및 Attention U-Net 실험
- IoU/Dice 기반 평가

## 5. 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission08.ipynb
```

## 6. 주요 파일
- `notebooks/mission08.ipynb`

## 7. 폴더 구조
```text
bootcamp-mission-08
  .gitignore
  notebooks/
    mission08.ipynb
  README.md
  requirements.txt
```

## 8. 학습 내용
세그멘테이션 모델 구조와 소규모 데이터에서의 과적합 제어 및 성능 비교 방법을 학습했습니다.

## 9. 트러블슈팅
미션을 진행하며 발생한 오류와 해결 과정은 노트북 또는 보고서에 정리했습니다.

## 10. 결과 화면
결과 이미지는 노트북 출력, 보고서 또는 `images/` 폴더에서 확인할 수 있습니다.

## 11. 공개 전 확인 사항
- 제출 노트북만 포함했으며, 원본 데이터와 모델 파일은 공개 범위 확인 전 포함하지 않았습니다.
