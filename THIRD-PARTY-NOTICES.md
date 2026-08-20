# 서드파티 고지 (Third-Party Notices)

온에어킷(onairkit)은 아래 서드파티 자산을 사용합니다.
**온에어킷 자체 코드의 MIT License는 아래 자산에 적용되지 않습니다.**

---

## Pretendard

```
Copyright (c) 2021, Kil Hyung-jin (https://github.com/orioncactus/pretendard),
with Reserved Font Name 'Pretendard'.

Copyright 2014-2021 Adobe (http://www.adobe.com/),
with Reserved Font Name 'Source'.
Source is a trademark of Adobe in the United States and/or other countries.

Copyright (c) 2016 The Inter Project Authors (https://github.com/rsms/inter),
with Reserved Font Name 'Inter'.

Copyright 2021 The M+ FONTS Project Authors (https://github.com/coz-m/MPLUS_FONTS),
with Reserved Font Name 'M PLUS 1'.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
```

- 라이선스 전문: <https://github.com/orioncactus/pretendard/blob/main/LICENSE>
- OFL 안내: <https://openfontlicense.org/>
- **사용 방식**: jsDelivr CDN을 통한 **원본 그대로의 웹폰트 로드 (수정 없음)**
- **버전**: v1.3.9
- 글꼴 파일은 이 저장소에 포함되어 있지 않습니다.
- 온에어킷은 Pretendard 프로젝트와 제휴·후원·보증 관계가 없습니다.

---

## 온에어킷 개발자가 지켜야 할 규칙

Pretendard는 SIL Open Font License 1.1로 배포되며, 글꼴 **단독 판매**를 제외한
모든 상업적 행위·수정·재배포가 가능합니다. 다만 아래 세 가지는 라이선스 위반입니다.

### 1. 직접 서브셋을 뜬 뒤 `Pretendard` 이름을 그대로 쓰면 안 된다

OFL FAQ 2.6이 **서브셋을 명시적으로 "수정(modification)"으로 규정**합니다.
로딩 최적화를 이유로 `pyftsubset` 등으로 글자를 잘라낸 파일을 만들고
`font-family: 'Pretendard'` 로 선언하면 Reserved Font Name 조항 위반이며,
위반 시 라이선스가 **즉시 무효화**됩니다(OFL TERMINATION 조항).

> **그래서 온에어킷은 자체 서브셋을 만들지 않고 공식 dynamic-subset CDN을 그대로 쓴다.**
> 이 결정을 바꾸지 말 것. 꼭 잘라 써야 한다면 `font-family: 'OnairKit Sans'` 처럼
> **다른 이름으로 리네임**해야 한다.

### 2. 제품·테마·브랜드 이름에 `Pretendard` 를 넣으면 안 된다

`Pretendard Theme Pack` 같은 이름은 안 됩니다(OFL 조건 4).
"Pretendard 글꼴을 사용합니다" 같은 **사실 고지는 허용**됩니다.
`Source` / `Inter` / `M PLUS 1` 도 동일하게 예약된 이름입니다.

### 3. 글꼴만 따로 팔면 안 된다

OFL 조건 1은 **단독 판매만** 금지합니다.
유료 테마 팩처럼 위젯 HTML·CSS·에셋이 함께 들어 있는 묶음은 문제없습니다.

> **유료 팩에 글꼴 파일을 동봉하는 경우에만** 추가로 지킬 것:
> `fonts/Pretendard/OFL.txt` 에 라이선스 **전문**을 복사해 넣고(요약본 금지),
> 판매 페이지에 아래 문구를 적을 것.
>
> ```
> 본 테마 팩에 포함된 Pretendard 글꼴은 SIL Open Font License 1.1로 배포되며,
> 동봉된 fonts/Pretendard/OFL.txt에 전문이 포함되어 있습니다.
> 글꼴 자체는 판매 대상이 아니며, 자유롭게 무료로 내려받아 사용할 수 있습니다.
> ```

---

_최종 확인: 2026-08-18 — 라이선스 원문을 직접 열어 확인했습니다._
