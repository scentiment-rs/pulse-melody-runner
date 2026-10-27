# pulse-melody-runner

원곡 mp3를 재생하면서 채보한 멜로디 노트를 같은 타임라인에 맞춰 Web Audio로 함께 연주하는 페이지입니다.

- 페이지: https://scentiment-rs.github.io/pulse-melody-runner/
- `index.html`: 플레이어 (피아노롤, 싱크 오프셋, 볼륨·음색 조절)
- `notes.js`: 트랙별 노트 데이터 (FINEST THING · WITH · 백화요란 · MEME · DRAGON = track01–05, `withNotes`는 WITH)
- `audio/`: 원곡 track01–05.mp3

로컬에서 볼 때:

```bash
python -m http.server 8765
```
