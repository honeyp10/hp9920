# 모여라 광장

광장에 모여 OX 퀴즈, 별 모으기, 도깨비불 피하기를 함께 하는 2D 웹 게임이에요.

## 파일
- `index.html`: 게임 전체 (화면, 규칙, 그림)
- `vendor/supabase.js`: Supabase 공식 라이브러리 2.45.4 (실시간 연결용)
- `config.js`: Supabase 연결 정보. 비워 두면 봇과 혼자 하는 모드로 열려요.

## 온라인 연결
1. Supabase 프로젝트의 Project URL과 anon public key를 `config.js`에 넣어요.
2. Vercel 같은 정적 호스팅에 이 폴더를 그대로 올려요. 빌드 과정은 없어요.

## 방 규칙
- 링크로 들어오면 `plaza` 1번 방에 들어가요. 방이 80명으로 차면 다음 방으로 넘어가요.
- 주소 끝에 `?room=이름`을 붙이면 그 이름의 방에서 만나요.
