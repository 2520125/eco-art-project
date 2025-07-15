# 나의 에코아트
## 제작과정
*정말*멋져요
**핵심기능**
-순서없는 목록
-두번쨰 항목
 -하위 항목
'''const int led1 = 13;  // LED 1 핀 번호
const int led2 = 12;  // LED 2 핀 번호

void setup() {
  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
}

void loop() {
  digitalWrite(led1, HIGH);  // LED 1 켜기
  delay(500);                // 0.5초 대기
  digitalWrite(led1, LOW);   // LED 1 끄기

  digitalWrite(led2, HIGH);  // LED 2 켜기
  delay(500);                // 0.5초 대기
  digitalWrite(led2, LOW);   // LED 2 끄기
}
