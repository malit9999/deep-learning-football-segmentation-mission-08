# Football Scene Segmentation with U-Net

> **Bootcamp Mission 08** | Semantic Segmentation

## 미션 소개
축구 경기 이미지에서 선수, 골대, 심판, 관중 등 장면 요소를 픽셀 단위로 구분하는 U-Net 기반 시맨틱 세그멘테이션 미션입니다.

## 구현 목표
- 시맨틱 세그멘테이션의 픽셀 단위 레이블 개념을 이해한다.
- U-Net 구조로 입력 이미지와 마스크를 학습한다.
- 예측 마스크를 원본 이미지와 비교한다.

## 주요 구현 내용
- 축구 경기 장면 마스크 처리
- U-Net 기반 세그멘테이션
- 원본·정답·예측 마스크 비교

## 사용 기술
- Python
- U-Net
- Deep Learning
- Computer Vision
- Jupyter Notebook

## 실행 방법
`ash
pip install -r requirements.txt
jupyter notebook notebooks/mission08.ipynb
`

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
`	ext
notebooks/
  mission08.ipynb
README.md
requirements.txt
.gitignore
`

## 학습 내용
- 분류와 세그멘테이션은 예측 단위가 다르다는 점
- 마스크 품질을 시각적으로 함께 검토해야 한다는 점

## 트러블슈팅 및 재현 시 참고 사항
학습 데이터와 마스크의 크기·채널 형식을 맞추는 과정이 핵심 점검 항목입니다.

## 결과 확인
세그멘테이션 결과는 노트북의 마스크 비교 출력으로 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Semantic Segmentation** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.