# Opensource-Contribution

How to submit a contribution(step 1-5)


Contribution 단계입니다. Step 3, 4는 프로젝트마다 다를 수 있습니다.


step (1)
 
원하는 Organization의 프로젝트를 fork하여 본인 계정의 레퍼지토리에 저장합니다.


step (2)
프로젝트를 clone하여 받은 후 수정을 합니다.

step (3) - 프로젝트마다 차이가 있습니다.(Contribution 방법은 프로젝트마다 REAMME에 잘 정리돼있습니다)


1.	git add 수정한 파일(git add .처럼 전체 파일을 하면 다운 받으면서 설정이 바뀔 수 도 있으므로 수정한 파일만 해야됩니다)


2.	git commit -s -m “커밋 메세지”


3.	git push --force-with-lease origin master


이후 수정사항이 본인 레퍼지토리에 반영이 됩니다.


step (4) - 프로젝트마다 차이가 있습니다.(검사도 프로젝트마다 REAMME에 잘 정리돼있습니다)


수정한 레퍼지토리의 프로젝트를 적용할 오픈소스 프로젝트에 Pull Request를 합니다.
 

DCO – Commit //Sign-off 여부 체크
LGTM.com // Javascript Change detector
Azure Pipelines //프로젝트에서 정해놓은 테스트
Pull request를 할 경우 위 총 6계 단계를 Bot이 자동으로 검사합니다. 검사가 완료될 경우 Review를 받을 수 있습니다.

step (5)


이후, 아래처럼 Reviewer가 수락할 경우, Merge가 되고 Contributor가 됩니다.
 
안되는 경우:

아래 처럼 Reviewer가 거절한 경우 -> 다시해야됩니다 (반영하지 못하는 이유를 알려주므로 수정해서 다시 요청을 하면 됩니다.)
 

Issue를 등록한 경우 -> Issue를 찾아 등록하고 수정이 돼도 Contributor는 프로젝트에 Merge가 된 경우에만 되는 것 같습니다.

