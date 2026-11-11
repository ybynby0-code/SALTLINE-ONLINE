SALTLINE ONLINE

구성: index.html (기존 SALTLINE 게임 + Supabase 실시간 방 시스템)

온라인 기능:
- 6자리 방 코드 생성 및 참가
- 닉네임 저장
- Supabase Realtime Presence 기반 접속자 추적
- 10Hz 플레이어 위치/방향 브로드캐스트
- 상대 플레이어 3D 표시
- 사격 트레이서 이벤트 브로드캐스트(시각 효과)

현재 한계:
- 온라인 연결 MVP입니다. 서버 권한 판정, 실제 PvP 피격/체력 동기화, 계정/랭킹/매치메이킹은 아직 구현되지 않았습니다.
- 브라우저에 Supabase Publishable key만 포함되어 있습니다. Secret/Service Role 키는 포함되지 않습니다.
- GitHub Pages는 저장소 Settings > Pages에서 Deploy from a branch, main, /(root)를 선택하세요.
