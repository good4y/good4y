# 항해 1주차 WIL
- 기간 : 21. 11. 1 ~ 21. 11. 6
- 팀원 : 김영철, 임찬수, 이해원, 김자운

항해 1주차를 회고하기 전에, 1주차에 있었던 일들을 모두 정리했으면 좋았을 걸... 이라는 생각이 먼저 들었다.
앞으로의 항해 여정에는 꼭 하루 배운 내용들을 리뷰하는 시간을 가져야겠다.

일단 첫 주차에는 팀장을 맡아 프로젝트를 수행하게 되었다.
팀장을 맡는 것에는 부담이 없었고, 내가 잘 따라갈 수 있을까? 라는 부담은 좀 있었다.
그럼에도 불구하고, 우리 팀은 잘 해냈고 멘토님께서 칭찬을 아끼지 않아 감사한 마음이 들었다.
팀 분위기도 좋았고, 스터디 내용도 정말 알찼다.
특히 찬수님이 구현하신 정렬 부분은 나도 큰 공부가 되었다.
나는 백엔드와 기상청 날씨 API를 이용한 날씨 정보 알림 구현을 맡았는데 결국 API 구현에는 실패했다.
그 이유로는 첫 번째로 SORS에러였고, 두 번째는 금요일에 너무 많은 데이터가 들어와 데이터를 가공하는 부분이었다.
추후에 좀 더 공부해서 구현을 시도 해 봐야겠다.



# 항해 2주차
- 기간 : 21. 11. 8 ~ 21. 11. 13
- 팀원 : 김영철, 김종욱, 김원석, 김우식 

## 1일 차  
자바를 이용하여 프로그래머스 사이트에서 알고리즘 구현 연습을 했다.  
1. 두 정수 사이의 합  
https://programmers.co.kr/learn/courses/30/lessons/12912/solution_groups?language=java&type=all  
**등차수열의 합 공식 활용 가능** 수학적인 접근이 상당히 인상적이다.  
Math 클래스를 이용할 수 있다.  

2. 평균 구하기
https://programmers.co.kr/learn/courses/30/lessons/12944/solution_groups?language=java&type=all  
for each 구문을 활용하여 더 직관적으로 표현 가능하다.    
import java.util.Arrays ==> 라이브러리 활용 가능  
상대적으로 쉬운 문제임에도 불구하고 에러 처리를 고민하는 풀이법도 있었다.(Null 체크)  
2.5같이 소수점이 붙을 경우 long이나 int 타입은 2로 저장됨   
stream라이브러리, lambda 식??

정규식 사용법 연습하기.  
문제 당 최대한 많은 방법을 이용하여 접근해 보려는 시도를 하고 있다.  
문제별로 코드를 적어보고 싶은데 아직 깃허브 블로그 사용이 미숙하여 아쉽다.  

## 2일 차  
20번까지 풀기.
최대한 프로그래머스 점수를 많이 받고 싶다.  
아직은 라이브러리를 계속 검색하게 된다.  
문자열 검색에는 .equals()를 쓴다.(계속 연산자로 표현하려함)  

30분 이상 고민하지 않고 풀어보기(다양한 유형을 접해보기)   
시간복잡도, 공간복잡도, 배열, 정렬, 배열의탐색, 이분탐색, 스택, 큐, 해쉬, 힙, DFS, BFS 개념 정리

~20번까지 풀었다. 오늘은 최대한 여러각도에서 접근해 다양한 함수를 써보는 것을 목표로 했는데 만족스럽다.  
완벽하진 않아도 앞으로 유사한 알고리즘이 나왔을 때 더 용이하게 함수를 찾아 이용할 수 있을 것이다..  

## 3일 차
28번까지 풀어보기.  
숫자의 길이가 필요할 때? String 변수에 숫자 저장하고 .length() 이용 가능  
==> 수적인 계산이 필요 없을 때는 String과 함께 쓸 수 있는 함수들 적극 이용해보기.  
22. (int)Math.log10(n)+1 로그함수를 이용하여 자연수의 자릿수를 구할 수 있다!(  
