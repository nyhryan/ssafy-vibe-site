You are a professional frontend web engineer. Help the user below.

---

Your job is to create a website for me. 

Read through the proposal and requirements and build the website.


<proposal>
# 웹사이트 구축 제안서: 개성 있는 개발자 포트폴리오

이 제안서는 클래스 구성원(친구, 선생님)을 대상으로 본인을 매력적이고 명확하게 소개하기 위한 개인 웹사이트 기획안입니다.

---

## 1. 기본 방향 및 콘셉트

* **웹사이트 목적:** 클래스 내 네트워크 형성 및 친밀감 형성, 본인의 독창적인 캐릭터 각인
* **핵심 키워드:** 다재다능(Versatile), 도전 정신, 리드미컬, 탐험가
* **디자인 톤앤매너:** 서브컬처 느낌을 주는 귀엽고 부드러운 파스텔 톤(라이트 모드)

---

## 2. 웹사이트 페이지 구조 (Information Architecture)

* **메인 페이지 (Landing Page):** 전체 콘텐츠의 요약본이자 첫인상을 결정하는 페이지

---

## 3. 페이지별 세부 콘텐츠 기획

### [Page 1] 메인 페이지 (Landing Page)

방문자가 스크롤을 내리며 본인의 핵심 아이덴티티를 한눈에 파악할 수 있도록 구성합니다.

* **히어로 섹션 (Hero Section):**
* 핵심 카피 배치: "디버깅부터 다크소울 보스까지 - 항상 어떤 도전에도 준비되어 있는 개발자"
* 키워드 강조: 나를 표현하는 단 하나의 형용사 'Versatile' 시각화


* **요약 섹션 (Quick Overview):**
* 어떤 환경이나 언어에도 빠르게 적응하는 유연한 적응력 요약 제 시
* 도전, 리듬, 모험으로 대변되는 3가지 매력 포인트 맛보기 노출


* **취향 스냅샷 (Taste Preview):**
* 음악, 영화, 게임 등 하단 큐레이션 페이지로 이동할 수 있는 흥미로운 티저 위젯 배치

## 4. 디자인과 테마

배경은 밝은 색, 텍스트는 어두운 색으로 할 것.

배경과 텍스트를 제외한 색(primary, secondary, accent, ...)은 아래의 팔레트를 사용하라.

- Baby pink: FF9BC6
- Soft blossom: FFBCD6
- lavender veli: FFE5F9
- perwinkle: B7B6FF
- icy blue: AFDEFF

The design principles of this website are:
- Cute and rounded design
- Use the following font from google font:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Gaegu:wght@300;400;700&display=swap" rel="stylesheet">
```
</proposal>

<requirements>
- Use only Korean language for site's contents. 
- Single HTML page. HTML, JavaScript in a single file
- Use plain vanila JavaScript.

- Apply TailwindCSS: Attach the CDN script below.
```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```
- Apply the palette attached in the proposal.
- Apply the following CSS convention:
    - Readable line length: 80 characters
    - Watch out for word wrap, line breaks that applies to Korean language.
    - Mobile responsive layout. Do not go overkill. Just need to be readable in mobile layout.
- navbar: home(landing page), about me, culture curation(movie, anime, music, travel)
</requirements>
