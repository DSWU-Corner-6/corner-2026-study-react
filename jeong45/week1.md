Git: 코드 변경점 기록, 버전 관리 도구
프로젝트 복사 없이 업데이트하며 수정 기록도 남길 수 있음
Github: 백업과 공유가 가능한 온라인 코드 저장소

[리눅스 명령어]
*pwd(print working directory): 작업중인 폴더 보여줌
*ls(list): 폴더 안의 폴더&파일 보여줌
*ls -a(list all): 숨겨진 폴더&파일도 보여줌
*cd(change directory): 폴더 이동
cd .. : 한 단계 위 폴더로 이동
cd 폴더명/폴더명 : 한 단계 아래 폴더로 이동

[Git 명령어]
*git init(initialize): 초기 세팅(=.git 폴더 생성, 코드 변경 추적 시작), 이후 다른 명령어 입력 가능, 프로젝트 시작 전 한 번 입력, 정확한 프로젝트 폴더에서 입력해야 함!

.git 폴더에서 코드 변경점을 추적&기록함 -> 정확한 프로젝트 폴더에 있어야 함

*rm -rf .git: .git 폴더 삭제
*git add 파일명: 저장할 파일 지정
*git add . : 경로 내의 모든 변경된 파일들 지정
*git commit -m "메세지 작성": 실제 저장, 변경 내용 자세히 작성하는 것이 좋음
*git status: 변경 상태 확인, 변경 O&저장 X -> 붉은색 표시
*git log: 저장 내역 확인
*git diff: 코드 변경 확인
*git reset: 과거로 돌아가기
*git branch (브랜치명): 브랜치 생성
*git switch (브랜치명): 브랜치 이동
*git switch -c (브랜치명): 브랜치 생성&이동 동시에
*git checkout (브랜치명): 브랜치 이동
*git checkout -b (브랜치명): 브랜치 생성&이동 동시에

코드 합치기; 최종 브랜치로 이동 -> git merge (합칠 브랜치 이름)
git merge는 잘 안 씀 협업 시 주로 github에서 pull request로 합침

*git pull origin (브랜치명): 온라인에서 머지한 코드 로컬에 반영

