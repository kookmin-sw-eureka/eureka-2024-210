# Eureka Team.10 (class 2)

유레카 프로젝트 2분반 10조 사이트입니다.

---

# Welcome to GitHub

유레카 프로젝트 팀 생성을 축하합니다.

**팀페이지 주소** -> https://kookmin-sw-eureka.github.io/ '{{분반 및 자신의 팀 번호}}'

**예시)** 2024년 1분반 1조  https://kookmin-sw-eureka.github.io/eureka-2024-101

## Markdown을 사용하여 내용꾸미기

Markdown은 작문을 스타일링하기위한 가볍고 사용하기 쉬운 구문입니다. 여기에는 다음을위한 규칙이 포함됩니다.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

자세한 내용은 [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Support or Contact

readme 파일 생성에 추가적인 도움이 필요하면 [도움말](https://help.github.com/articles/about-readmes/) 이나 [contact support](https://github.com/contact) 을 이용하세요.





<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>나를 소개하는 웹페이지</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>나를 소개합니다</h1>
  </header>
  <main>
    <div class="card" data-scroll="left">
      <h2>개발자로서의 나</h2>
      <p>안녕하세요! 저는 주로 Java를 다루는 개발자로, C++과 같은 로우레벨 언어와 Python 같은 스크립트 언어도 능숙하게 사용합니다.</p>
    </div>
    <div class="card" data-scroll="right">
      <h2>프로젝트 경험</h2>
      <ul>
        <li>오픈월드 TPS RPG 게임 개발</li>
        <li>커뮤니티 플랫폼 Agit Community 개발</li>
        <li>Agit Community 기반 통합 계정 인프라 구축</li>
        <li>리그 오브 레전드 내전 팀 밸런싱 알고리즘 개발</li>
      </ul>
    </div>
    <div class="card" data-scroll="left">
      <h2>개발 환경</h2>
      <p>제가 선호하는 개발 환경은 VSCode와 Linux 기반이며, Java Spring을 사용한 백엔드 개발을 즐깁니다.</p>
    </div>
    <div class="card" data-scroll="right">
      <h2>개인적인 관심사</h2>
      <p>주식, 리그 오브 레전드, 오버워치 등 다양한 취미를 가지고 있습니다.</p>
    </div>
    <div class="card" data-scroll="left">
      <h2>전공 관련 관심 분야</h2>
      <ul>
        <li>운영체제</li>
        <li>게임 엔진</li>
        <li>웹 및 온라인 게임 개발</li>
        <li>크로스플랫폼 개발</li>
      </ul>
      <p>인공지능에도 관심이 있지만, 다른 분야만큼은 아닙니다.</p>
    </div>
    <div class="card" data-scroll="right">
      <h2>현재</h2>
      <p>저는 현재 대학 1학년 학생으로, 앞으로 더 많은 경험과 지식을 쌓아가고 싶습니다.</p>
    </div>
  </main>
  <script src="script.js">
    location.href = "/test.html";
    const cards = document.querySelectorAll('.card');
const handleScroll = () => {
  cards.forEach(card => {
    const rect = card.getBoundingClientRect();
    const isVisible = rect.top < window.innerHeight && rect.bottom > 0;
    if (isVisible) {
      card.classList.add('visible');
    } else {
      card.classList.remove('visible');
    }
  });
};

window.addEventListener('scroll', handleScroll);

// 페이지 로드 시 초기 호출
handleScroll();
  </script>
</body>
</html>
