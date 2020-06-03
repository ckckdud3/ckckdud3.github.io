# 프로젝트 진행 현황
## 2019.06.04 Update
내가 기여할 것들 중 하나인 Queue 중에서 가장 단순한 형태인<br>
Singly linked list를 기반으로 한 Queue를 만들었다.<br>
사실 자료구조 디렉토리에 Queue가 없는 줄 알았는데 알고 보니<br>
디렉토리로 분류되어 있지 않은 queue.c 파일이 있었다.<br>
그러나 코드가 영 부실하여, 처음부터 새로 만들었다.<br>
지금 pull request를 올리고, 막상 생각해보니 Dequeue를 할 때<br>
dequeue한 값을 리턴하는 것을 까먹어, 수정을 해야 한다.<br>
수정한 후에는 Doubly linked list 기반의 Queue와 Deque를 추가할<br>
생각이다.<br>
