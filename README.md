# architecture_coin


## TODO

- Backend
  - CI
  - Websocket 서버인 STOMP
  - Websocket 클라이언트 upbit 연동
    - 가져온 데이터를 가공하기
      - in-memory 방법: upbit구독내용을 stomp server에서 발행하기
      - pub/sub application 사용 방법: 구독 내용 변경하여 비지니스로직 수행 후 발행
  - 자동 매매 시스템
  - AWS

- Frontend
  - CI (범인색출, 좌표)
  - React Table (Model - View)
    - upbit <> client socket connection 상태에서 받은 데이터를 테이블 화 하기 (주한이의 어깨가 무겁다...)
    - Model 설계 (김프가는 지표가 한정적이다) => 우리는 더 많은 컬럼(지표)를 만들어놓고 유저가 취사선택할 수 있도록
  - Websocket
    - 가공된 데이터를 받았다는 가정
    - Redux
  - 구글 광고 API 튜토리얼 적용하기 (개꿀)
  - 코인의 종류 (NFT, 국가별 코인, 커플링 된 것들..)
    - 각 코인별 추세 통계 정리
  - RSI 거래량추세선?
    - RSI 알림받기 (기준점을 설정하도록)
  - ICO 정보 모아보기
  - 그래프(차트)
    - 코인별 그래프 비교 (btc vs eth) 
    - 라이브러리 사용(트레이딩뷰) vs 직접 구현하기



## ROLE

- K
  - React Table
- P
  - Spring Server
- P
  - Spring Server
  - React Table


## Priority

1. MVP 사이트 띄우기 (테이블만 일단 구현)
