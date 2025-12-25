New repository 생성

% 1. 기존 연결(origin) 삭제\
`git remote remove origin`

% 2. 새로운 Private 저장소 주소 등록 (주소는 본인의 새 저장소 URL로 바꾸세요)\
`git remote add origin (github URL path)`

% 3. 강제로 코드 밀어넣기\
`git push -u origin main`\
(혹은 git push -f origin main)
