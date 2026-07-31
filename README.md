1. 프로젝트 폴더 생성
2. 깃 초기화 명령어 : git init 
3. gitignore 파일 추가
4. 파이썬 버전관리 : uv init --python 3.12
5. 작업 ... (uv add 로 패키설치, 코드 생성)
6. 버전관리를 위해 커밋 생성
    - git add . 또는 git add 파일 목록
    - git commit -m "커밋 메시지!"

7. github로 연결하기
    - 최초 1번 : git remote add origin 레포주소
8. github로 커밋 내역 보내기
    - 최초 1번 : git push -u origin main
    - 그 이후에는 : git push