## Markdown
- 정의 : 텍스트 기반의 가벼운 마크업 언어(태그(tag)를 이용하여 문서의 구조를 나타내는것)
- 만들어진 배경 : 문서의 구조와 내용을 쉽고 빠르게 적고자 탄생
- 기능
1. **헤딩(Heading)** : 문서의 제목이나 소제목으로 사용 | 깃허브의 경우 6번까지 중첩 가능하지만 3번까지가 가독성이 좋다
2. 리스트 :목록을 표시하기 위해 사용 | 순서가 있는 것과 없는 것 두가지 있음
3. 링크(link) & 이미지 : 특정 주소를 사용해서 링크와 이미지를 넣을 수 있음(이미지는 넣을때 앞에 **!** 붙여주기 ![이미지](주소))
4. 기울림  : *으하*
5. 굵게 : **야하**
6. 취소선 : ~~냐하~~

## Git : 분산 버전 관리 프로그램

- 의미 
1. 버전 : 컴퓨터 소프트웨어의 특정 상태
2. 관리 : 어떤 일의 사무, 시설이나 물건의 유지, 개량

=> 과거 특정 시점으로 되돌아가거나, 한번에 여러 버전으로 개발자들이 동시에 작업이 진행가능
 
 - 만들어진 배경 : 자료 조사한 것을 뭉치고 합치기 힘든 이유와 유사

 - 필요한 이유
 1. 협업하기 좋다
 2. 대응할 수 있는 협업 툴이 없다
 3. 오픈 소스로 무료로 사용 가능하다 

 - README.md : 프로젝트에 대한 설명 문서
 1. 깃허브 프로젝트에서 가장 먼저 보는 문서
 2. 일반적으로 소프트웨어와 함께 배포
 3.작성 형식은 따로 없으나, 일반적으로 마크다운을 이용해 작성 


- Repository : 특정 디렉토리 버전을 관리하는 저장소(히스토리, 태크, 브랜치)


1. git init : 명령어로 로컬 저장소를 생성
2. git config --global user.email "(이메일)"
git config --global user.name "(이름))" : 이메일과, 이름 생성
3. git add . : 파일 추가
4. git commit -m " " : 커밋
5. git push -u origin : 배포


## Github (Git이 커피라면, Github는 커피숍)

- 기능
1. Read.md 파일을 통해 오픈 소스의 공식 문서 작성
2. 개인 프로젝트의 소개 문서 작성
3. 매일 학습한 내용 정리
4. 마크다운을 이용한 블로그 운영
