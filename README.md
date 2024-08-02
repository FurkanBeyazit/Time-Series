![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Prophet](https://img.shields.io/badge/Prophet-FB6D05?style=for-the-badge&logo=prophet&logoColor=white)
![Meteostat](https://img.shields.io/badge/Meteostat-1F77B4?style=for-the-badge&logo=weather&logoColor=white)
### 📈 Python Time Series (파이썬 시계열)

---

### Project Overview (프로젝트 개요)

This project involves the time series analysis of weather temperature data for Madrid, sourced from Meteostat. (이 프로젝트는 Meteostat에서 제공된 마드리드의 기온 데이터를 시계열 분석하는 것입니다.) The analysis includes various key aspects such as seasonal trends, anomaly detection, and model forecasting comparisons. (분석에는 계절적 추세, 이상 감지 및 모델 예측 비교와 같은 여러 중요한 측면이 포함됩니다.)

---

### Key Points (핵심 사항)

1. **Seasonal Trend and Residual Analysis (계절적 추세 및 잔차 분석):** The data was decomposed into seasonal, trend, and residual components to understand the underlying patterns. (데이터는 계절적, 추세적, 잔차적 요소로 분해되어 기본 패턴을 이해할 수 있습니다.)

2. **Anomaly Detection (이상 감지):** Techniques were applied to detect anomalies in the temperature data, identifying unusual variations. (기온 데이터에서 이상 변동을 식별하기 위해 기술이 적용되었습니다.)

3. **Stationarity Check (정상성 검사):**
   - **ADF Test (ADF 테스트):** Augmented Dickey-Fuller test was used to check for stationarity in the data. (Augmented Dickey-Fuller 테스트는 데이터의 정상성을 검사하기 위해 사용되었습니다.)
   - **KPSS Test (KPSS 테스트):** Kwiatkowski-Phillips-Schmidt-Shin test was used to confirm stationarity. (Kwiatkowski-Phillips-Schmidt-Shin 테스트는 정상성을 확인하기 위해 사용되었습니다.)

4. **Forecasting Models (예측 모델):**
   - **Prophet:** A model developed by Facebook, used for forecasting time series data with a strong seasonal component. (페이스북에서 개발한 모델로, 강력한 계절적 요소를 가진 시계열 데이터를 예측하는 데 사용됩니다.)
   - **SARIMAX:** Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors, suitable for seasonal data with external variables. (계절적 데이터 및 외부 변수에 적합한 계절적 자기회귀 누적 이동평균 모델)
   - **AutoARIMA:** An automated ARIMA model that selects the best parameters through cross-validation. (교차 검증을 통해 최적의 파라미터를 선택하는 자동화된 ARIMA 모델)

5. **Model Comparisons (모델 비교):** The models were compared based on their forecasting accuracy and performance metrics. (모델은 예측 정확도와 성능 지표를 기반으로 비교되었습니다.)

---
