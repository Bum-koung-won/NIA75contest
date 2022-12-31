# NIA75contest
가축(젖소, 돼지) 발정 탐지를 위한 행동식별 AI 모델 개발 해커톤

- 2022 NIA 75 인공지능 경진대회 -

▪ 제공받은 이미지, Keypoint, 라벨 데이터 가공

   -> json to txt, 모델 요구 형식 가공
   
▪ 제공받은 Keypoint 및 라벨 이용 자세 예측 훈련

   -> RandomForest 모델
   
▪ 젖소, 돼지 Keypoint 추출

   -> Keypoint RCNN 모델
   
▪ 추출한 Keypoint를 기준으로 결과 값 예측
