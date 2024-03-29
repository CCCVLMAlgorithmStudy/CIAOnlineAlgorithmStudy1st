# CIA Algorithm Study 

1. 프로그래밍이란?

   **프로그래밍 = 문제해결** -> 컴퓨터를 이용해서!

2. 좋은 프로그램이란?
   1. 일단은 돌아가야 합니다. -> 실행 가능
   2. 원하는 대로 돌아가야 합니다. -> 올바른 결과
   3. 빠르게 돌아가야 합니다. -> 시간 복잡도
   4. 메모리를 효율적으로 써야 합니다. -> 공간 복잡도

3. 알고리즘?

   알고리즘 : 어떠한 문제를 해결하기 위한 일련의 절차나 방법, 컴퓨터가 수행할 수 있을 정도로 객관적이고 명료해야 한다. 

   세상에는 수많은 문제가 있고, 모든 문제는 각자의 해결법을 가지고 있습니다. -> 모든 문제 해결법은 알고리즘이 될 수 있습니다.

   어떠한 문제는 비슷한 방법으로 해결할 수 있습니다. -> 이렇게 공통된 방법은 체계화 되어서, '잘 알려진 알고리즘'이 됩니다.

   

4. 알고리즘 공부?

   1. 다양한 문제를 풀어보는 것 

      > 문제 풀이의 6단계 (출저 : 프로그래밍 대회에서 배우는 알고리즘 문제해결전략[구종만,인사이트])
      >
      > 1. 문제를 읽고 이해한다.
      > 2. 문제를 익숙한 용어로 재정의 한다.
      > 3. 어떻게 해결할지 계획을 세운다.
      > 4. 계획을 검증한다.
      > 5. 프로그램으로 구현한다.
      > 6. 어떻게 풀었는지 돌아보고, 개선할 방법이 있는지 찾아본다.

   2. 잘 알려진 알고리즘을 익히는 것

   3. 여러 사람과 알고리즘 공부한 것을 나누면서 함께 자라는 것

5. 복잡도(Complexity) : 입력의 크기에 따른 컴퓨터 자원의 사용도

   1. 시간 복잡도(time Complexity) : 입력 크기에 따른 계산 시간

   2. 공간 복잡도(space Complexity) : 입력 크기에 따른 공간 사용도 

   3. Big-O 표기법 : 자원 사용의 상한선을 나타낸 것. 가장 높은 차수의 항만 남기고, 계수도 지운다.

      ex)  n 크기의 입력에 대해서 수행시간이 3*n^3 + 5*n^2 + 90n + 1 이라면 시간 복잡도는 O(n^3)이다.

      > Big-Omega 표기법(자원 사용의 하한선),  Big-Theta(자원 사용의 평균) 등도 있지만 알고리즘이 어려워질 수록 이 두 표기법을 적용하기 어렵습니다. 따라서 주로 Big-O(표기법)을 사용합니다.

      

      * 왜 이런 걸 알아야 하나요? : 알고리즘을 평가할수 있는 기준이 되기 때문에!

6. 알고리즘 공부를 할 수 있는 사이트

   1. 국내 

      1. BOJ - https://www.acmicpc.net

      2. 프로그래머스 - https://programmers.co.kr

      3. SW Expert Academy - https://swexpertacademy.com

      4. Algospot - https://algospot.com

      5. CodeUp - https://codeup.kr

      6. 정올 - http://www.jungol.co.kr

         기타 등등...

   2. 해외 -> 영어! 영어! 영어!

      1. Codeforces - http://codeforces.com
      2. AtCoder - https://atcoder.jp
      3. Topcoder - https://www.topcoder.com
      4. 비야돌리드 대학 온라인 채점 사이트 - https://uva.onlinejudge.org

   > 여기 사이트들은 전체의 일부입니다. 그 외에도 다양한 사이트들이 있습니다.

7. 알고리즘 관련 도서 추천
   1. Introduction to Algorithm - 알고리즘 교재의 바이블
   2. 프로그래밍 대회에서 배우는 알고리즘 문제 해결 전략 - 일명 종만북. 알고리즘 추천 도서를 요청하면 반드시 추천되는 책이지만, 내용이 그리 쉽지많은 않습니다.
   3. 알고리즘 트레이닝 시리즈(프로그래밍 대회 입문 가이드, 자료구조, 알고리즘 문제 해결 핵심 노하우) - 국내에는 잘 나오지 않는 알고리즘 책 중에서는 비교적 최근에 출간된 책으로, 기초부터 친절하게 설명해주어 혼자 공부하기 좋습니다.
   4. 프로그래밍 콘테스트 챌린징 :  일본 프로그래밍 대회 고수들이 쓴 책. 실용적인 테크닉이 많습니다.
   5. Programming Challenges :  비야돌리드 대학 온라인 채점 사이트의 문제들 중 일부를 실어놓은 문제 풀이 책. 다양한 난이도 문제를 실어 놓아 시작하기 좋으나, 그래도 완전한 초보자용 책은 아닙니다.