## 9️⃣ TableView + Networking + SearchBar 연습을 위한 '음악 검색 앱'
- TableView
  - 받아온 데이터를 TableView에 표시

- Networking
  - 서버와의 통신을 담당하는 객체 만들기 (일반적으로 Singleton Pattern으로 구성)
  - 가져온 데이터를 구조체/클래스 등의 배열로 변환

- SearchController(SearchBar)
  - 검색 기능 구현
  - 검색어를 입력하는 동안 새로온 ViewController를 보여주는 것 구현(searchResults)

- CollectionView
  - 2가지 델리게이트 패턴(datasource, delegate) 동일하게 사용
  - 다만 CollectionView 자체의 Layout을 담당하는 객체가 따로 존재함
  - UICollectionViewFlowLayout : 셀의 크기, 셀들의 간격, 스크롤 방향 등 담당

- Nib(Xib)
  - Storyboard와 분리하여 View의 화면 구성 가능

- Name Space
  - identifier 등 문자열을 실수하지 않기 위한 패턴
