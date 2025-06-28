# DS4th-DATAThon
### 타이핑 된 감정, 분류되는 위험
> 우리의 진료실은 데이터입니다 : 우울증 예측 프로젝트

- 🔗 [Notion](https://icy-citron-b57.notion.site/DATAThon-M2-202309f028f0806f9314ff6e91b33c7b)

## DataSet
- Exploring Mental Health Data (정신 건강 데이터)
- 🔗 [Kaggle](https://www.kaggle.com/competitions/playground-series-s4e11/overview)
- 설명 : 본 데이터셋은 개인 및 환경적 특성을 바탕으로,
  정신 건강 문제 중 하나인 우울증(Depression) 위험 여부를 예측하기 위한 목적으로 구성
- 특징 :
  - 총 140,000개 이상의 샘플
  - 20개 이상 피처 포함
  - 다수의 범주형 변수 + 연속형 변수 혼합
  - 타겟: Depression 여부 (이진 분류)

## 디렉터리 구조

```

DATAThon/
│
│
├── 📁 docs/                     # 데이터 관련 폴더
│   ├── README.md            # 프로젝트 개요 및 설명
│   └── 발표자료                   # pdf
│
├── 📁 data/                # 주요 실험 노트북
│   ├── 데이터_전처리_설명.ipynb   # 데이터 전처리 
│
├── 📁 code/                     # 연습/아카이브 코드 저장소
│
├── 📁 modeling/              # 모델 학습 폴더
│   └── [CatBoost] 파라미터_최종.ipynb
│   └── [XGBoost] 파라미터_최종.ipynb
│
└── 📁 verification/        # 검증 폴더
    └── 가설_통계_검증.ipynb # 전처리 과정 검증

```


