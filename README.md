# Account Management :: 계좌 관리 시스템 입니다.

* gradle JVM : SDK 11

* 현재 계좌번호 생성은 순차 증가 방식으로 구현 되어있습니다.
* 계좌 번호 생성에 있어 랜덤 생성 구현은 랜덤 생성 기준 및 예외처리의 이슈로 인하여, 미완성이며 주석 처리 되어있습니다. 

* ERROR_CODE CHANCE 
  * 환불 금액이 원 결제 금액과 같지 않은 경우 안내 문구가 변경되었습니다. 
  * CANCEL_MUST_FULLY("부분 취소는 허용 되지 않습니다.") -> CANCEL_AMOUNT_NOT_MATCHED("결제 금액과 취소 금액이 동일하지 않습니다.")
