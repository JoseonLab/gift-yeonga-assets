# 선물연가 이미지 에셋

선물연가 홈페이지에서 쓰는 이미지를 GitHub Pages 로 공개 호스팅합니다.
홈페이지 본체가 어디에 올라가든(로컬 시안·개발사 납품·외부 호스팅) **이미지 주소는 바뀌지 않습니다.**

## 주소 규칙

```
https://joseonlab.github.io/gift-yeonga-assets/img/{파일명}
```

예: `https://joseonlab.github.io/gift-yeonga-assets/img/hero.webp`

HTML 에서는 이렇게 씁니다.

```html
<img src="https://joseonlab.github.io/gift-yeonga-assets/img/hero.webp" alt="">
```

## 이미지 목록

| 파일 | 쓰이는 곳 |
|---|---|
| `hero.webp` | 홈 히어로 |
| `cat-hero.webp` | 카테고리 히어로 |
| `band-01.webp` ~ `band-04.webp` | 홈 중간 밴드 4종 |
| `pdp-01.webp`, `pdp-02.webp` | 상세 페이지 |
| `plan-a.webp`, `plan-b.webp`, `plan-c.webp` | 플랜 3종 |
| `part-dark.webp` | 파트너 섹션(다크) |
| `kit-card.webp` | KIT 카드 · KIT 상세 공용 |
| `part-light.webp` | 예비(현재 미사용) |
| `gal-01.webp` ~ `gal-04.webp` | 예비(현재 미사용) |

## 이미지를 바꿀 때

같은 파일명으로 덮어쓰고 커밋·푸시하면 주소는 그대로 둔 채 그림만 바뀝니다.
브라우저·CDN 캐시 때문에 최대 10분 정도 예전 그림이 보일 수 있습니다.
즉시 확인하려면 주소 뒤에 `?v=2` 처럼 아무 값이나 붙여서 엽니다.

## 주의

- 이 리포는 **공개**입니다. GitHub Pages 는 무료 계정에서 공개 리포만 호스팅합니다.
- 한 번 커밋한 이미지는 삭제해도 커밋 이력에는 남습니다. 대외 공개가 곤란한 그림은 올리지 않습니다.
- 원본(고해상도·작업 파일)은 여기가 아니라 구글드라이브에 둡니다. 여기는 **웹 게시용 사본**입니다.
