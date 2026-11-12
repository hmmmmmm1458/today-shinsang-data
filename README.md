# today-shinsang-data

[오늘의 신상](https://github.com/hmmmmmm1458/today-shinsang-data) Apps in Toss(앱인토스) 미니앱에 쓰는 **공개 데이터 피드**입니다.

앱은 이 저장소의 GitHub Pages에서 `items.json`을 받아 목록을 갱신합니다. 데이터만 바뀌면 앱을 다시 검수받지 않아도 됩니다.

## 주소

- 저장소: https://github.com/hmmmmmm1458/today-shinsang-data
- 데이터: https://hmmmmmm1458.github.io/today-shinsang-data/items.json

앱 쪽 CORS 허용 Origin:

- `https://today-shinsang.apps.tossmini.com`
- `https://today-shinsang.private-apps.tossmini.com`

## `items.json`

수집기(`crawler/crawl.py`)가 공식 브랜드 사이트와 확인된 수동 항목을 합쳐 만듭니다. 각 항목에는 이름, 브랜드, 카테고리(편의점·프랜차이즈·팝업스토어), 가격, 기간, 출처 링크 등이 들어 있습니다.

## 이미지 출처

이미지는 **공식 브랜드 사이트**(공식 홈페이지, 공식 보도자료, 브랜드 공식 채널)에서만 가져옵니다. 뉴스·블로그·팝업 정보 사이트·개인 SNS 사진은 쓰지 않습니다.

앱 상세 화면에는 항목의 `imageCredit`이 보입니다. 예:

- `이미지 출처: CU 공식 홈페이지`
- `이미지 출처: 파리바게뜨 공식 홈페이지`
- `이미지 출처: KC F&B 공식 홈페이지`

저작권 문제가 있으면 해당 이미지를 즉시 내립니다.
