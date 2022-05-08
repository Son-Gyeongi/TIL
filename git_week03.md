# TIL 
Today I Learned 오늘 배운 것을 기록합니다.


### 3주차 주요 개념 키워드 적어보기

-------------흐름에 따라 키워드 정리-------------------
* 3주 차 다른 사람 repo에 PR(Pull Request) 등록 후 merge 하기
  * PR(Pull Request, 풀리퀘스트) 는 내 작업내역을 바로 merge 하지 않고, 참여하고 있는 프로젝트에 내 작업(branch)를 merge해달라고 요청(Request) 를 먼저 보내는 것
1. Issues에 들어가서 내가 할 수 있는 이슈에 댓글 남기기
2. fork 그 이슈 내 repo에 들고오기
3. 원격repo에 있는 브랜치 내 로컬repo로 clone하기
4. 새 브랜치 만들어서 새로운 작업 공간에 commit하기
5. commit한 새 브랜치 원격repo로 push하기
6. 원격repo에서 Pull Request 작성 


------------흐름에는 없지만 git에 쓰이는 기능 정리----------------
* commit 관리하기
  * 최신의 commit을 수정하는 것을 amend(어맨드,고치기)
  * 어떤 내용을 되돌렸는지 새로운 commit을 남기는 것을 revert(리버트)
  * commit 했던 작업내역을 말 그대로 리셋시키는 것 reset(리셋)
  * 프로젝트의 변경사항을 임시적으로 보관해둘 때 사용하는 stash(스태시)
