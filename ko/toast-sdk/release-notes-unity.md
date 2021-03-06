## TOAST > TOAST SDK 사용 가이드 > 릴리스 노트 > Unity

## 0.20.0 (2020.03.26)

### plugin version

- Android : 0.21.0
- iOS : 0.23.0

### 버그 수정

- CrashFilter관련 처리에서 Exception 이슈

## 0.19.1 (2020.01.23)

### 버그 수정

- OnHandleException 콜백 호출 이슈

## 0.19.0 (2019.12.27)

### 추가 사항

- Unity Play Services Resolver 적용

## 0.18.0 (2019.12.06)

### 공통

- iOS 0.20.1 framework 적용
- Android 0.19.4 aar 포함해서 배포
- Native Plugin (Windows, MacOS) 배포

## 0.17.0 (2019.10.02)

### TOAST IAP

- 구매 요청시 사용자 데이터 설정 기능 추가

## 0.16.0 (2019.08.28)

### TOAST IAP

#### 변경 사항

- 소비성 구독 상품 추가

## 0.15.1 (2019.07.29)

### 공통

- iOS 0.16.1 framework 적용

## 0.15.0 (2019.07.23)

### TOAST IAP

#### 변경 사항

- ActivedPurchases -> ActivatedPurchses

## 0.14.0 (2019.07.02)

### TOAST Log & Crash

#### 추가 사항

- Unity Standalone/WebGL 버전 추가
  - Logger
  - Instance Logger

### TOAST IAP

#### 추가 사항

- ActivedPurchases 추가

## 0.13.1 (2019.03.26)

### TOAST Log & Crash

#### 기능 개선

- 유니티 쓰레드가 아닌 쓰레드에서도 로그 전송 가능하도록 기능 개선
- ProjectKey가 AppKey로 명칭 변경
  - 기존 ProjectKey는 계속 사용 가능

#### 버그 수정

- 안드로이드에서 크래시 로그 전송시 빈 문자열이 있는 경우 SDK의 예외 로그가 전송되는 문제 해결

## 0.13.0 (2019.02.26)

### TOAST Log & Crash

#### 추가 사항

- 크래시 로그 필터링 기능 추가

## 0.12.0 (2019.01.08)

### TOAST IAP

#### 추가 사항

- 신규 기능 추가

## 0.11.0 (2018.12.27)

### TOAST Log & Crash

#### 추가 사항

- 유니티에서 발생한 예기치 못한 예외에 대한 로그를 자동으로 전송하는 기능 추가
- SetCrashListener API 추가

## 0.10.0 (2018.11.20)

### TOAST Log & Crash

#### 추가 사항

- SetLoggerListener API 추가
- Network Insights 지원

#### 변경 사항

- 유니티 패키지에서 mainTemplate.gradle 제거
  - mainTemplate.gradle 설정은 가이드 참고

## 0.9.0 (2018.09.04)

### TOAST Log & Crash

#### 추가 사항

- 신규 기능 추가
