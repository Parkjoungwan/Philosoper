# 서브젝트 요약

---

### 스레드와 뮤텍스를 사용해 철학자들 구현하기

- 한명 이상의 철학자가 둥근 테이블에 앉아 다음 행동중 하나를 취함 (먹기, 자기, 생각하기)
- 철학자들은 양손에 포크가 있어야 먹을 수 있다
- 철학자가 밥을 다 먹었으면, 포크를 내려놓고 잠자기 시작
- 철학자가 잠을 다 잤으면, 생각하기 시작
- 철학자가 한 명이라도 사망하면 시뮬레이션이 종료

# 실행방법

makefile을 사용해 프로그램을 빌드해주세요.

```jsx
make all
```

philo 프로그램이 생성됐다면, 필요한 인자에 맞춰 매개변수로 프로그램을 실행시켜주세요.

```jsx
./philo [철학자의 수] [철학자의 수명] [먹는데 필요한 시간] [자는데 필요한 시간] [몇 번 먹고 종료할 것인지]
```

# 실행예시

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/941df175-f930-4f3a-a0cf-4caa87fcc5ce/Untitled.png)

# 노션정리

[Philosophers](https://www.notion.so/Philosophers-88f3e28e3e834b298f1cf66d62240a86)
