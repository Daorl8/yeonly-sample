# STRUCTURE · yeonly-sample (v0.1 · 스크랩북 다이어리 + 시술 안내형 · 크림 · 연분홍 / 연보라 줄무늬 · 폴라로이드 · 모서리 2px · 배포 예정 yeonly-sample.lgt3232.workers.dev)

```
yeonly-sample/
├─ index.html                  단일 파일 (CSS · JS 인라인)
├─ wrangler.toml               name = yeonly-sample
├─ .assetsignore               img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ yl-pretendard-v01.woff2     한글 · 본문 (Pretendard 300–700, 페이지 글자 전부 · ✦ 포함)
├─ yl-cormorant-v01 · -i-v01.woff2  영문 라벨 · 가격 숫자 (Cormorant Garamond 정체 400–600 · 이탤릭 400–500, 영문만)
├─ yl-logo.png · yl-wordmark.png    로고 글자 투명 PNG(SINCE 2022 포함 · 두 줄 글자만)
├─ yl-h1~h3.webp              히어로 폴라로이드
├─ yl-g1~g6.webp              시술 사진 폴라로이드
├─ favicon.png · og-yl.jpg
├─ img/                        다올 제공 원본 + _원문.md (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md  (로컬 정본 · 업로드 안 함, R-38)
```

## 섹션 순서
헤더 `.top`(sticky · 로고 · PC 메뉴 5 · 「오픈카톡 예약」 / 900 미만 `.snav` 5칸) → 히어로(글 | 폴라로이드 쌓기 — 900 미만 2장 · 이상 3장) → 줄무늬 띠 → `#perm`(연보라 · 3단계 계단) → 띠 → `#extension`(줄 목록) → 띠 → `#works`(연보라 · 폴라로이드 6) → 띠 → `#price`(두 단) → 띠 → `#booking`(연보라 · 소개 · 영업시간) → 띠 → `#visit`(구글 지도) → 띠 → 푸터(연보라) + 모바일 `.quick`.

## 버튼 · 링크
- 오픈카톡 `https://open.kakao.com/o/sMAdmHXe`(메인): 헤더(PC) · 히어로 · 예약 · 푸터 · 하단 바
- 전화 `tel:050713570462`: 히어로 · 예약 · 오시는 길 · 하단 바
- 인스타 `instagram.com/yeonly_beauty/` · 블로그 `blog.naver.com/wjddus5227` · 네이버 지도 `map.naver.com/p/entry/place/1360893874` · 네이버 플레이스(푸터 · JSON-LD)
- 구글 지도 검색어 「충남 천안시 동남구 새말4길 6」(배포 후 핀 확인 · R-35)

## 모션 (강제 재생)
- `.reveal` setInterval(화면 90% 선 · 바닥 도달 시 전부) · 앵커 rAF 스크롤(R-25). reduced-motion 분기 없음.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사 + 파일 이름 버전 올리기(R-43 · v01 → v02).
