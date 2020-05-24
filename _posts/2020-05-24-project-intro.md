# 오픈소스소프트웨어실습 팀 프로젝트 Introduction
본 팀 프로젝트는 오픈소스 프로젝트 TheAlgorithms에 기여하는 것을 목표로 하고 있다.<br>
> [**TheAlgorithms 깃헙 페이지**](https://www.github.com/TheAlgorithms)<br>

## TheAlgorithms?
TheAlgorithms 프로젝트는 자료구조와 알고리즘을 공부하고 이를 여러<br>
프로그래밍 언어에서 구현하여 배포하고 있는 오픈소스프로젝트이다.<br>

> **현재 구현된 언어**<br>
> [**C**](https://www.github.com/TheAlgorithms/C)<br>
> [**C++**](https://github.com/TheAlgorithms/C-Plus-Plus)<br>
> [**Python**](https://github.com/TheAlgorithms/Python)<br>
> [**Java**](https://github.com/TheAlgorithms/Java)<br>
> [**JavaScript**](https://github.com/TheAlgorithms/Javascript)<br>
> [**Go**](https://github.com/TheAlgorithms/Go)<br>

자료구조와 알고리즘 외에도 소켓 프로그래밍, 블록체인 등의 기술적인 주제에도 관련하여<br>
구현된 바 있다. 본 팀 프로젝트에서는 C언어 파트에 기여하는 것을 목적으로 한다.<br>

> [**TheAlgorithms' Issue History**](https://github.com/TheAlgorithms/C/issues)<br>
> * 2017.8.28 구현되지 않은 더 많은 알고리즘의 구현 요청<br>
> * 2019.8.8 [Leetcode](https://leetcode.com/)의 문제들의 Solution 추가 요청<br>
> * 2019.10.10 ReadMe 마크다운에 여러 유저들이 스페인어, 힌디어, 독일어 등 언어로<br>
> 번역을 하면 좋겠다는 요청 이슈화<br>
> * 2019.10.28 그래프 상의 최단거리 알고리즘(데이크스트라, 플로이드-와샬 알고리즘)추가에<br>
> 대한 논의 이슈화<br>
>
> [**TheAlgorithms' Pull Reqests History**](https://github.com/TheAlgorithms/C/pulls)<br>

## 팀 프로젝트 활동 계획
TheAlgorithms는 알고리즘과 자료구조 교육이 주요 목적으로 둔 프로젝트이기 때문에 알고리즘이나<br>
자료구조의 추가 혹은 그에 대한 설명이나 주석을 보충하는 방향성이 요구된다.<br>
> Accessibility Improving
> * 한국의 개발자들이 보고 이해하고, 배우기 쉽도록 한글 번역 진행<br>
> * ReadMe의 한글화, Wiki의 각 알고리즘의 설명을 한글로 작성<br>
> * 알고리즘을 소개하고 설명해주는 페이지 작성<br>
>     * 소개 페이지에는 알고리즘의 Flow Chart 등 이해를 돕는 설명 작성<br>
> * 알고리즘과 자료구조 코드에 한글 주석 작성<br>
>
> Data Structure Project
> * 프로그래밍을 함에 있어 자주 쓰이나 구현되지 않은 자료구조의 구현<br>
> * 자료구조 내에서 활용될 응용 라이브러리(Sorting 등) 구현<br>
> * 최근 프로그래밍 동향을 살피며 요구되는 자료구조의 구현<br>
>
> Misc. Project
> * 행렬 연산 라이브러리 구현
> * Bitwise Operation의 구현 및 설명<br>
> * 그 밖의 다양한 알고리즘들의 구현

## 팀 멤버

> **정승혁(팀장)**<br>
> * Data Structure 파트 기여<br>
> * 알고리즘상의 버그가 있는 부분 수정<br>
> * 최신 프로그래밍 동향 파악, 추가할 수 있는 부분 구현<br>
> * b-트리 등 자주 쓰이는 Tree data structure 우선적으로 구현<br>
> - Issue에 올라온 버그나 요청 파악<br>
> - ReadMe에 기여한 내용 반영<br>
> - 팀 프로젝트 정적 페이지 관리<br>

> **이찬영**<br>
> * 바이토닉 정렬 등 Data Structure 내의 Sorting 라이브러리 구현<br>
> * Queue 등의 자주 쓰이는 대중적인 Data Structure 구현<br>
> * Wiki에 기여한 내용 반영<br>
> * Issue 파악 및 관리<br>
> * ReadMe 관리<br>

> **권윤영**<br>
> * Data Structure 기여
> * 원본 프로젝트에 Single LL 관련 라이브러리만 구현된 점을 고려해
> Double LL 구현
> * 이 외에 많이 쓰이나 아직 구현되지 않은 Data Structure 구현<br>
> * Issue에 올라온 버그와 요청 파악
> * Project 정적 페이지 관리


> **윤태웅**<br>
> * Misc Project 기여<br>
> * 행렬연산 등 C에 적용할만 한 라이브러리 구현<br>
> * Bitwise Operation 관련 라이브러리 구현<br>
> * ReadMe와 Wiki에 기여한 내용 반영<br>
> * 원본 프로젝트의 ReadMe.md 번역, Issue 참여<br>

> **최영우**<br>
> * Misc Project 기여<br>
> * Misc Project에 추가할만한 새로운 라이브러리 구현<br>
> * Bitwise Operation 관련 라이브러리 구현<br>
> * 알고리즘상의 버그가 있는 부분 수정<br>

## 활동 시 고려사항과 제안사항
현재까지 원본 프로젝트에서 제기된 이슈는 대부분 예외 테스트 케이스,<br>
새로운 알고리즘이나 Misc 파트에 대한 Merge Request였다. 우리가 기여하는<br>
방식도 마찬가지로 많이 사용하거나 찾는 빈도가 높은 알고리즘/자료구조/예제<br>
등에 대한 코드 추가에 관련한 내용일 것이다. 프로그래밍 입문으로 많이 사용되는<br>
언어인 C언어에 대한 알고리즘/자료구조에 대한 아카이브형 프로젝트이므로<br>
ReadMe에 대한 한국어 번역도 많은 사람들에게 도움이 될 것이다.<br>
현재 Open 상태인 이슈가 있었으므로 바로 참여가 가능할 것이다. 주의할 점은,<br>
주석이나 변수명 등을 설정할 때 다른 코드들을 참고하며 일관성을 부여해야<br>
하는 점이다. Misc 팀과 Data Structure 팀은 각자 맡은 부분과 관련된 코드를<br>
여러 개 읽으면서 코드에 통일성을 유지하는 것이 도움이 될 것이다.<br>
