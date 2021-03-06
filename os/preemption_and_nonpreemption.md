### 비선점형 OS

> 특정 프로세스가 CPU를 독점할 수 있다 (다른 프로세스가 강제로 뺏을 수 없다)

- 어떤 프로세스가 CPU를 할당받으면 그 프로세스가 종료되거나 입출력 요구가 발생해 자발적으로 중지될 때까지 계속 실행되도록 보장
- 순서대로 처리되며 응답 시간을 예상할 수 있다
- 스케줄러 호출 빈도가 낮고 문맥 교환 오버헤드가 적다
- 일괄처리 시스템에 적합
- CPU 사용시간이 긴 프로세스가 CPU사용시간이 적은 여러 프로세스를 대기시킬 수 있어 처리율이 떨어질 수 있다

### 선점형 OS

> 특정 프로세스가 CPU를 독점할 수 없다

- 다른 프로세스가 실행 중인 프로세스를 중지하고 CPU를 강제로 점유할 수 있다
- 모든 프로세스에게 CPU사용시간을 동일하게 부여(ROUND ROBIN)할 수도 있다
- 빠른 응답시간이 필요한 대화식 시분할 시스템에 적합하다. 긴급한 프로세스 제어 가능
- 운영체제가 각 프로세스의 요청이 있을 때 특정 요건들을 기준으로 자원을 배분하는 방식

---

- 출처
  - [https://jwprogramming.tistory.com/14?category=680235](https://jwprogramming.tistory.com/14?category=680235)
