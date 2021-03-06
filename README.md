# 목차  

```

1. 변수 
                1. 메모리 미리보기
                    1.1 32 비트와 64비트의 의미 
                2. 변수의 의미
                3. 파이썬에서의 변수: 이름과 객체

        2.  정수 
                1. 컴퓨터에서 수를 표현하는 방법
                    1.1 10진수
                    1.2 2진수
                    1.3 16진수
                2. 10진수를 2진수로
                3. 2진수를 10진수로
                4. 16 진수를 10진수로 
                5. 코딩으로 확인하는 진수 변환 
                6. 양의 정수 
                7. 음의 정수
                    7.1 보수의 개념
                    7.2 2의 보수
                    7.3 음의 표현
                    7.4 2의 보수로 표현하는 이유
                8 마무리 

        3.  실수
            1. 실수 연산의 함정
            2. 부동소수점
            3. 단정도와 배정도
            4. 1 바이트 실수 자료형 설계하기
                4.1 10진수 실수를 2진수 실수로 바꾸기
                4.2 정규화
                4.3 메모리 구조
                4.4 1바이트 부동소수점의 표현 범위
                4.5 1바이트 부동소수점의 정밀도
            5. 정밀도에 대한 고찰
                5.1 엡실론
                5.2 엡실론과 정밀도
            6. 마무리

        4. 문자와 문자열
            1. 아스키코드
            2. 유니코드
            3. 유니코드 인코딩 방식
                3.1 UTF-8
                3.2 UTF-16
                3.3 UTF-32
            4.파이선 문자열의 특징
            5.마무리

        5. 함수
            1. 함수를 시작하기 전에 
                1.1 자료구조 미리 엿보기
                1.2 전역 변수와 지역 변수
            2. 인자 전달 방식에 따른 분류
                2.1 값에 의한 전달
                2.2 참조에 의한 전달
                2.3 객체 참조에 의한 전달(파이썬) - 변경 불가능 객체를 전달할 때 
                2.4 객체 참조에 의한 전달 (파이썬) - 변경 가능 객체를 전달할 때
            3. 람다 함수
            4. 마무리 

        6. 객체 지향 프로그래밍
            1.프로그래밍 패러다임
            2. 절차 지향 프로그래밍
            3. 절차 지향으로 학급 성적 평가 프로그램 만들기
                3.1 openpyxl 모듈 설치하기 
                3.2 openpyxl 모듈로 데이터 읽어 들이기
                3.3 평균 . 뷴산 . 표준편차를 함수로 만들기 
                3.4 메인 프로그램 만들기
            4. 객체 지향 프로그래밍
                4.1 캡슐화
                4.2 클래스를 사용해 객체 만들기
                4.3 파이썬의 클래스
                4.4 객체 지향으로 은행 입출금 프로그램 만들기
                4.5 정보 은닉
            5. 객체 지향으로 다시 만드는 학급 성적 평가 프로그램
                5.1 Stat 클래스 만들기
                5.2 DataHandler 클래스 만들기
                5.3 메인 프로그램 만들기 
            6. 마무리 

        7. 클래스
            1. 클래스 관계 
                1.1 IS-A: 상속
                1.2 HAS-A: 합성 또는 통합
            2. 메서드 오버라이딩과 다형성
                2.1 메서드 오버라이딩 
                2.2 다형성
            3. 클래스 설계 예제 
                3.1 Character 클래스 만들기
                3.2 Player 클래스 만들기
                3.3 Monster, IceMonster, FireMonster 클래스 만들기
            4. 연산자 모버로딩
            5. 마무리

        8. CPU
            1. 트랜지스터와 논리 게이트
                1.1 전압, 전류, 저항
                1.2 논리 게이트
            2. 조합 논리 회로와 가산기
                2.1 CPU의 구성
                2.2 가산기
            3. 순차 논리 회로와 레지스터
            4. 클록
            5. 시스템 버스
                5.1 시스템 버스의 구성과 특징
            6. 인스트럭션 세트
                6.1 명령어 종류 
                6.2 덧셈과 뺄셈 명령어
                6.3 곱샘과 나눗셈 명령어
                6.4 메모리 접근 명령어
                6.5 소스 코드에서 인스터럭션으로
            7. 마무리 

        9. 메모리 
            1. 메모리 저장방식 
            2. 메모리 계층
            3. 지역성과 캐시 히트
            4. 가상 주소 공간
                4.1 코드 세그먼트
                4.2 데이터 세그먼트
                4.3 스택  세그먼트
                4.4 힙 세그먼트
            5. 스택 프래임
                5.1 스택 프레임 할당
                5.2 스택 프레임 해제 
            6. 가상 메모리와 페이징
                6.1 가상 메모리 
                6.2 MMU
                6.3 페이징
                6.4 페이지 프레임
                6.5 페이지 테이블 
                6.6 요구 페이징
                6.7 페이지 폴트 
                6.8 변환 색인 버퍼
            7. 마무리 

        10. 프로세스와 스레드 
                1. 프로세스 
                    1.1 프로세스 상태 
                    1.2 스케줄링 
                    1.3 컨텍스트 스위칭
                2. 스레드 
                    2.1 멀티포로세스와 멀티 스레드 
                    2.2 멀티스레딩 구현  
                    2.3 경쟁 조건
                    2.4 상호 배제 
    
            11. 프로그래밍 언어
                    1. 컴파일러 언어와 인터프리터 언어 
                        1.1 C언어: 컴파일러 언어 분석
                        1.2 파이썬: 인터프리터 언어 분석
                    2. 파이썬: 소스 코드부터 실행까지
                        2.1 컴파일러 
                        2.2 추상 구문 트리 
                        2.3 심벌 테이블 
                        2.4 바이트 코드와 PVM
                    3. 마무리 

            12 .자료구조 (1)
                    1.자료구조 
                        1.1 세 가지만 알면 자료구조 끝 
                        1.2 추상 자료형 
                    2. 연결 리스트 
                        2.1 노드 
                        2.2 연결 리스트 구현 
                    3. 스택 
                        3.1 스택의 동작 
                        3.2 스택 구현 
                    4. 큐 
                        4.1 큐의 동작 
                        4.2 큐 구현 
                    5. 마무리 

            13. 자료구조(2)
                    1. 재귀함수 
                        1.1 팩토리얼 
                        1.2 피보나치 수 
                    2. 트리 
                        2.1 사이클 
                        2.2 이진 트리 
                        2.3 이진 트리의 종류 
                    3. 이진 트리 구현 
                        3.1 트리 노드 구현 
                        3.2 노드 관련 메서드 구현 
                        3.3 서브 트리 관련 메서드 구현 
                        3.4 이진 트리 구성하기 
                        3.5 트리의 순회 
                    4. 마무리 

            14. 이진 탐색 트리
                    1. 이진 탐색 트리의 특징
                    2. 이진 탐색 트리의 구현 
                        2.1 이진 탐색 트리의 추상 자료형 
                        2.2 이진 트리 관련 메서드 
                        2.3 insert() 메서드 
                        2.4 search() 메서드 
                        2.5 remove() 메서드 
                        2.6 테스트 코드 
                    3. 마무리 


            15. 알고리즘
                    1. 알고리즘 성능 분석 
                        1.1 선형 탐색 알고리즘
                        1.2 선형 탐색 알고리즘의 성능 
                        1.3 이진 탐색 알고리즘
                        1.4 이진 탐색 알고리즘의 성능
                        1.5 알고리즘 성능 분석 
                    2. 거품 정렬 
                    3. 퀵 정렬 
                    4. 마무리 


            부록 파이썬 기초 .


```


                
            
