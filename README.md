# healga-images

바른몸애힐가(HEALGA) 사이트용 이미지 호스팅 저장소. jsdelivr CDN을 통해 무료 전송.

## 사용 방법 (jsdelivr URL 패턴)

```
https://cdn.jsdelivr.net/gh/sonbyungjun/healga-images@main/<폴더>/<파일명>
```

예시:
- 메인 홈 히어로 배경: https://cdn.jsdelivr.net/gh/sonbyungjun/healga-images@main/home/bg1.png
- 명상 섹션 배경: https://cdn.jsdelivr.net/gh/sonbyungjun/healga-images@main/home/bg5.png
- 로고: https://cdn.jsdelivr.net/gh/sonbyungjun/healga-images@main/home/logo.png

`@main` 대신 커밋 SHA를 쓰면 영구 캐싱이 보장됩니다. 이미지가 자주 바뀌지 않으면 `@main`으로 충분합니다.

## 디렉토리 구조

| 폴더 | 페이지 |
|------|--------|
| `home/` | 메인 홈 (9개 섹션) |
| `awakening-lab/` | Awakening Lab 서브 페이지 |
| `corporate-flow/` | Corporate Flow 서브 페이지 |
| `golden-session/` | Golden Session 서브 페이지 |

## 메인 홈 이미지 매핑 (잠정)

| 파일 | 사용처 (추정) |
|------|---------------|
| `home/bg1.png`, `home/bg2.png` | 섹션 1 히어로 배경 (영상 없을 때 정적) |
| `home/bg3.png` | (미확정) |
| `home/bg4.png`, `home/bg4-1.png` | (미확정) |
| `home/bg5.png`, `home/bg5-1.png` | 섹션 6 명상 배경 (The GOLDEN HEALGA Way) |
| `home/bg6.png` | (미확정) |
| `home/bg7.png`, `home/bg7-1.png`, `home/bg7-3.png` | 섹션 9 CTA 배경 (그리스 기둥 톤) |
| `home/principles_1~5.png` | 섹션 8 ∞ 시그니처 노드 5개 |
| `home/logo.png` | 헤더 로고 |
| `home/blog.png`, `home/youtube.png` | 푸터 SNS 아이콘 |

원본 파일명 변경:
- `블로그.png` → `blog.png`
- `유튜브.png` → `youtube.png`
- 한글/공백 파일명은 URL 인코딩 문제로 영문화함.

## 라이선스

내부 사용. 외부 재배포 금지.
