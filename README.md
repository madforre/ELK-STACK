# ELK-STACK

## 목표

* 데이터 과학에 대한 이해
* 통계분석 프로그램 제작 및 활용

## References

* https://github.com/minsuk-heo/BigData

## ELK-STACK 업데이트 후 중요 변경 내용

* 명시정 매핑시 6.1버전 기준으로 string 타입은 에러발생! text 타입으로 대체할 것.
* curl 을 이용한 json 파일과 관련된 명령어에 -H 'Content-Type: application/json' 추가할 것.
* 6.x 에서 bulk 관련 json 데이터를 넣어줄 때, newline(엔터) 관련 에러 발생시 해당 json파일의 마지막 줄에 엔터를 넣어주면 해결

