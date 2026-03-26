지금 컴퓨터 뚜들길수 있으면 
코드 하나 내 github에 올리기 ->> 목표

깃 / 깃허브 

*Git = 코드 버전 관리 , 코드의 기록 도구* 
        위치: 내 컴퓨터
        역할: 기록
        로컬영역
*Github = 위에 말한 코드 버전 관리, 기록도구를 올려서 저장하는 저장공간, 클라우드*
        위치: 인터넷
        역할: 공유 
        원격서버

*깃 설치 과정, 사용자등록, 확인 방법*

1. 디코 일반채널에 올려둠
https://git-scm.com/
들어가서 설치

2. cmd 
git --version
->이거 치고, 버전 뜨면 설치완료

깃허브가입시 쓴 이메일 준비

3. cmd 
    git config --global user.name "너의이름(영문추천)"
    git config --global user.email "깃허브 가입한 이메일"

    git config --list -> 확인 명령어 

    이 과정을 하는 이유는 
    누가 작업했는지를 기록하기 위해서.
    이름과 이메일을 등록하고,
    github와 맞추는게 좋아요~

*핵심개념, 용어*

add : 파일 선택

commit : 저장

push : 업로드

pull : 다운로드

git commit -m "first commit"
    -> 깃에 저장을 하겠다 "저장할때 메모, 글귀, 코드내용, 변화점, 변경점, 업데이트 내용, 수정사항"

    커밋메시지 양식, 규칙이 많은데 이거는 차차 알아가기로 합시다.

branch 의 개념

branch는 main가 존재
