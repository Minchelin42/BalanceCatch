# 👊🏻 밸런스캐치 : 대중의 심리는 내 손안에!
<img src="밸런스캐치 앱 아이콘.png" alt="IMG_5119" width="100" height="100">


### 사람들과 함께 의견을 나누고 대중들의 선택도 맞춰보며 더 재밌는 방식으로 밸런스게임을 즐길 수 있도록 기획한 앱 [AppStore](https://apps.apple.com/kr/app/balancecatch-%EB%8C%80%EC%A4%91%EC%9D%98-%EC%8B%AC%EB%A6%AC%EB%8A%94-%EB%82%B4-%EC%86%90%EC%95%88%EC%97%90/id6450379412)  
- iOS 4인 협업
- 최소 버전 iOS 17.0 
- 개발 기간 2023.03.09 ~ 2023.06.23 (3개월)


## 📝 주요 기능
- 플레이어 입력
- 질문 직접 • 랜덤 선택
- 토론 타이머
- 플레이한 질문에 대한 선호도 평가
- 대중들의 선택 결과 발표
- 벌칙자 발표

## ⚒️ 사용 기술 및 라이브러리 
`SwiftUI` `Alamofire` `Singleton`
`Firebase` `MVVM` `Combine`

## ⚒️ 기술 적용

- **Combine**을 통해 반응형 타이머 구현
- **Generic Function**을 통해 네트워크 관련 코드에 대한 중복성을 낮춤
- **extension**을 통해 중복되는 코드를 줄임
- **CustomView**를 통해 코드의 중복을 줄이고 뷰의 재사용성을 높임

|인원 수 설정|질문 선택(랜덤)|질문 선택(직접)|
|:---:|:---:|:---:|
|<img src="" width="200" height="390"/>|<img src="" width="200" height="390"/>|<img src="" width="200" height="390"/>|

|질문에 대한 답 선택|질문별 타이머|대중선택 비율 발표|
|:---:|:---:|:---:|
|<img src="" width="200" height="390"/>|<img src="" width="200" height="390"/>|<img src="" width="200" height="390"/>|
