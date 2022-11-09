# awesome-baekjoon

눈여겨볼만한 백준 온라인 저지 관련 프로젝트를 모아둡니다.

실렸으면 하는 프로젝트가 있다면 이슈를 달아주세요!
PR을 바로 작성하는 건 README.md 파일을 병합 충돌의 나락으로 빠트리기 쉽습니다.

## 목차

- [awesome-baekjoon](#awesome-baekjoon)
  - [목차](#목차)
  - [라이브러리](#라이브러리)
  - [문제 출제](#문제-출제)
  - [발표](#발표)
  - [브라우저 확장](#브라우저-확장)
  - [서비스](#서비스)
  - [에디토리얼](#에디토리얼)
    - [제작 관련](#제작-관련)
    - [구데기컵](#구데기컵)
  - [유틸리티](#유틸리티)
  - [학습](#학습)

## 라이브러리

- [frozenca/BTree](https://github.com/frozenca/BTree) - C++로 짠 범용, 헤더 온리, STL과 닮은 B-Tree 구현체입니다.
- [atcoder/ac-library](https://github.com/atcoder/ac-library) - AtCoder 측에서 공식 제공하는 라이브러리로, 컨볼루션, 펜윅 트리, 느리게 갱신되는 세그먼트 트리, 강한 연결 요소 등 다양한 코드를 제공합니다.
- [cheran-senthil/PyRival](https://github.com/cheran-senthil/PyRival) - Python으로 구현한 알고리즘 라이브러리 묶음입니다.

## 문제 출제

- [UCPC 디스크립션 작성 및 포매팅 컨벤션](https://github.com/ucpcc/problemsetting-guidelines) - UCPC 문제 출제 시 따를 디스크립션 작성 및 포매팅 규약입니다.
- [문제 안내 - BOJ Stack](https://stack.acmicpc.net/guide/problem) - 백준에 문제를 출제할 때 지켜야 하는 문제 스타일, 문체, 기호 활용법, 제한/데이터 설정법 등을 총망라한 문서입니다.
- [ucpcc/ucpc2020-description-layout](https://github.com/ucpcc/ucpc2020-description-layout) -  [olymp.sty](https://github.com/GassaFM/olymp.sty), [SPC 2019](https://acm.sogang.ac.kr/spc/) 문제지 레이아웃 기반 문제 본문 템플릿입니다.
- [solved-ac/boj-description-converter](https://github.com/solved-ac/boj-description-converter) - UCPC 측에서 사용하는 [olymp.sty](https://github.com/GassaFM/olymp.sty) 기반 TeX 문제 본문을 BOJ Stack과 UCPC 규약에 알맞게 변환하는 도구입니다.
- [UCPC 2022에서 번거로운 디스크립션 작업을 초고속으로 해결한 방법](https://blog.shift.moe/2022/08/17/boj-description-converter/) - solved-ac/boj-description-converter이 풀고자 하는 문제와 도구의 사용 방법을 설명하는 게시글입니다.
- [Startlink/boj-judge-samples](https://github.com/Startlink/boj-judge-samples) - BOJ Stack 상에서 쓸 수 있는 문제 채점기(인터렉터, 스페셜 저지 등)의 예시를 소개한 저장소입니다.
- [MikeMirzayanov/testlib](https://github.com/MikeMirzayanov/testlib) - 문제 출제 과정에서 문제 채점기, 데이터 검증기, 데이터 제너레이터 등을 만들때 도움이 되는 유틸리티를 모아놓은 라이브러리입니다.
- [실수의 실수: 스페셜 저지만 붙인다고 끝나는 것이 아니다](https://blog.shift.moe/2022/10/31/on-floating-point-errors/) - 실수 연산에서 일어나는 절대 오차와 상대 오차가 어떻게 전파되는지 자세히 설명하는 글로, 실수를 활용하는 문제를 출제할 때 큰 도움이 되는 글입니다.
- [알고리즘 문제해결의 관점에서 프로그래밍 언어라는 것은](https://blog.shift.moe/2022/07/18/on-programming-languages-in-competitive-programming/) - 알고리즘 문제 해결에서 C++, Python, Java 등의 언어를 특정 사용례를 바탕으로 표준 라이브러리가 제공하는 기능의 차이와 이에 따른 문제 출제/해결 시 일어나는 일을 적어둔 글입니다.

## 발표

- [코딩 테스트 및 알고리즘 문제해결 공부 방법 (고려대학교 KUCC, 2022년 4월) - Suhyun Park](https://www.slideshare.net/SuhyunPark23/kucc-2022-4)

## 브라우저 확장

- [토탐정](https://github.com/wzrabbit/boj-totamjung) - 백준 온라인 저지에서 알고리즘 분류를 가리면서도 혹시 내가 모르는 알고리즘을 쓰는 게 아닌지 확인할 수 있습니다. ([Chrome](https://chrome.google.com/webstore/detail/%ED%86%A0%ED%83%90%EC%A0%95/hannhecbnjnnbbafffmogdlnajpcomek))
- [BOJ Extended](https://github.com/joonas-yoon/boj-extended) - 사용자 페이지, 채점 현황, 문제 타이머, 사용자 비교, 빠른 검색, 다크 모드 등 백준 온라인 저지 사용자 경험을 전반적으로 향상시키는 다양한 기능 묶음을 제공합니다. ([Chrome](https://chrome.google.com/webstore/detail/boj-%ED%94%84%EB%A1%9C%ED%95%84-%EB%AC%B8%EC%A0%9C-%EB%B3%B4%EA%B8%B0/mfcaadoifdifdnigjmfbekjbhehibfel), [Whale](https://store.whale.naver.com/detail/epdpeloboklojnaelckeihkghcgebhnp), [Firefox](https://addons.mozilla.org/ko/firefox/addon/boj-extended/))
- [BaekjoonHub](https://github.com/BaekjoonHub/BaekjoonHub) - 백준 온라인 저지, 프로그래머스 등에서 맞았습니다를 받을 경우 해당 소스 코드를 열람해 복사한 후 GitHub에 올려주는 브라우저 확장입니다. ([Chrome](https://chrome.google.com/webstore/detail/ccammcjdkpgjmcpijpahlehmapgmphmk))
- [TIERIMNIDA](https://github.com/mazassumnida/tierimnida) - 백준 온라인 저지에서 사용자 페이지의 문제 번호를 티어 색상으로 칠해줍니다. ([Chrome](https://chrome.google.com/webstore/detail/tierimnida/mgdddbhbedfjdodjccjefgbdgkglokdg))

## 서비스

- [solved.ac][] - 백준 온라인 저지 문제에 태그와 난이도를 붙이는 커뮤니티 프로젝트입니다.
- [Telegram @solvedacbot](https://github.com/kiwiyou/solvedacbot) - Telegram 메신저에서 [solved.ac][] 문제/사용자 검색을 돕는 봇입니다.
- [@solvedac/unofficial-documentation](https://github.com/solvedac/unofficial-documentation) - [solved.ac][] API를 문서화하는 비공식 커뮤니티 프로젝트입니다. 
- [RECJOON](https://github.com/boostcampaitech3/final-project-level3-recsys-14) - 백준 온라인 저지 및 [solved.ac][] 사용자의 문제 풀이 이력을 바탕으로 맞춤 문제 및 라이벌을 추천해주는 인공지능 서비스입니다.
- [mazassumnida/mazassumnida](https://github.com/mazassumnida/mazassumnida) - 레이팅, 푼 문제 수, 티어 정보, 자체 티어 아이콘 등을 담은 예쁜 [solved.ac][] 정보 기반 뱃지/배너를 만들어줍니다.
- [mazassumnida/mazandi](https://github.com/mazassumnida/mazandi) - 예쁜 [solved.ac][] 잔디 배너를 만들어줍니다.
- [hyp3rflow/github-readme-solvedac](https://github.com/hyp3rflow/github-readme-solvedac) - 레이팅, 푼 문제 수, 티어 아이콘, 랭킹, 장착한 뱃지, 클래스, 자기소개 등을 담은 예쁜 [solved.ac][] 정보 기반 배너를 만들어줍니다.
- [Algorithm Visualizer](https://algorithm-visualizer.org/) - 알고리즘을 시각화해 배우기 쉽게 하고, 나아가 시각화 자료를 만들어낼 수도 있는 인터랙티브 플랫폼입니다.

## 에디토리얼

### 제작 관련

- [ucpcc/ucpc2020-solutions-theme](https://github.com/ucpcc/ucpc2020-solutions-theme) - UCPC 2020 풀이 및 이에 사용된 beamer 테마입니다.

### 구데기컵

- [제 1회 구데기컵, 진짜 최종 구데기컵 2018](https://github.com/ghudegy/2018)
- [EtvycAuRLZpb6hhe86x0](https://github.com/ghudegy/2021)
- [진짜 최종 구데기컵 2 2](https://github.com/ghudegy/2022)

### 기타

- [UCPC 과거 대회 정보](https://ucpc.me/about/#%EA%B3%BC%EA%B1%B0-%EB%8C%80%ED%9A%8C-%EC%A0%95%EB%B3%B4) - UCPC 2011 풀이, UCPC 2013~2022 문제 및 풀이가 실려있습니다.
- [제1회 초콜릿컵 에디토리얼](https://blog.bubbler.space/posts/chocolate1/editorial/)

## 유틸리티

- [duqrldudgns/PS_CounterEx_Generator](https://github.com/duqrldudgns/PS_CounterEx_Generator) - 맞았습니다가 뜨는 C++ 코드와 틀렸습니다가 뜨는 C++ 코드가 주어질 때 무차별 대입 기법으로 반례를 찾아냅니다.
- [zshchun/bojtools](https://github.com/zshchun/bojtools) - 백준 온라인 저지 및 [solved.ac][] 전용 CLI 도구 묶음입니다.
- [kiwiyou/basm-rs](https://github.com/kiwiyou/basm-rs) - 정적 링크한 no-libc, no-std Rust 프로그램 바이너리를 C 프로그램으로 번역해줍니다. 미리 구현해 제공하는 라이브러리는 물론, 조건에 맞는 외부 Rust 라이브러리도 사용할 수 있으며 빠릅니다.

## 학습

- [바킹독의 실전 알고리즘](https://github.com/encrypted-def/basic-algo-lecture) - C++를 사용한 실전 알고리즘 강좌로, C/C++ 문법에 친숙한 상태에서 알고리즘 지식을 익히기에 좋도록 작성되었습니다.
- [코딩테스트 대비 문제집 with Baekjoon](https://github.com/tony9402/baekjoon) - 코딩 테스트 대비용 알고리즘 문제집입니다.


[solved.ac]: https://solved.ac/
