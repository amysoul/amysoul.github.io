# amysoul.github.io

GitHub Pages로 배포되는 개인 사이트입니다: https://amysoul.github.io

## 페이지

| 경로 | 설명 |
| --- | --- |
| [`/`](https://amysoul.github.io/) | 기본 홈 페이지 |
| [`/focus/`](https://amysoul.github.io/focus/) | 🍅 집중 타이머: 뽀모도로 타이머와 오늘 할 일 목록 |

### 집중 타이머 (`focus/`)

- 집중 25분 · 짧은 휴식 5분 · 긴 휴식 15분 (집중 4번마다 긴 휴식)
- 할 일을 추가하고 하나를 고르면, 끝낸 뽀모도로 수가 그 할 일에 기록돼요
- <kbd>Space</kbd>로 시작/일시정지
- 데이터는 브라우저 `localStorage`에만 저장되고, 날짜가 바뀌면 오늘 완료 수가 초기화돼요

## 로컬에서 실행하기

빌드 과정이 없는 정적 HTML이라 아무 정적 서버로 열면 돼요.

```bash
python3 -m http.server 8000
```

그다음 http://localhost:8000/focus/ 를 열어 보세요.
