# 🐰 UMC Ewha 8th GitHub Guide 🐰

안녕하세요, UMC Ewha 8기 챌린저 여러분! 😆  
이곳은 **UMC Ewha 8기**의 깃허브 활용 가이드입니다.  
워크북 미션은 깃허브 조직 리포지토리를 통해 제출받을 예정이니, 아래 가이드를 참고하여 설정해 주세요!  

## ✨ 목차 ✨

- [📌 GitHub 기본 가이드](#📌-github-기본-가이드)
- [🚀 초기 세팅 가이드](#🚀-초기-세팅-가이드)
- [💌 PR(Pull Request) 생성 및 제출 방법](#💌-prpull-request-생성-및-제출-방법)
- [🐱 코드 리뷰 및 협업](#🐱-코드-리뷰-및-협업)

---

## 📌 GitHub 기본 가이드

🔽 **GitHub 개념이 낯설다면?**  
👉 [GitHub 기본 가이드](https://www.notion.so/Github-aaa7f52c9fa64656b4e4ea02de51a0a9?pvs=21)  
👉 [원격/조직 리포지토리 개념 이해](https://jayeon8282.tistory.com/4)  
👉 [다른 사람 레포에 PR 날리기](https://velog.io/@burningjeong/다른-사람-레포에-PR-날리기)  

---

## 🚀 초기 세팅 가이드

### 1️⃣ UMC Ewha 8th Organization의 본인 파트 레포지토리를 Fork 하기

1. 이메일로 초대받은 **UMC-Ewha-8th** 조직 리포지토리에 들어갑니다.
2. 우측 상단의 `Fork` 버튼을 클릭하여 개인 깃허브 계정으로 복사합니다.
3. Fork된 개인 레포지토리가 생성되었는지 확인합니다.

> ⚠️ **주의**  
> - 개인 레포지토리에 먼저 `push`한 후, 조직 레포지토리에 PR을 보내주세요!  
> - 조직 레포지토리에는 직접 `push` 하지 않습니다.

### 2️⃣ Fork한 레포지토리를 로컬 저장소로 Clone 하기

1. **로컬 디렉토리**에서 원하는 위치로 이동 후 아래 명령어 실행
   ```bash
   git clone https://github.com/본인-github-아이디/본인-레포지토리.git
   ```
2. 프로젝트 루트 폴더에서 **주차별 폴더**(`week1`, `week2` 등)를 생성하여 관리해주세요.

---

## 💌 PR(Pull Request) 생성 및 제출 방법

### 1️⃣ 개인 레포지토리에서 브랜치 만들기 (선택 사항)
```bash
git switch -c weekN  # ex) git switch -c week1
```

### 2️⃣ 최신 코드 가져오기
```bash
git pull origin main
```

### 3️⃣ 작업 내용 commit 후 push
```bash
git add .
git commit -m "[weekN] 닉네임/본명 N주차 미션 제출"
git push origin 생성한브랜치명  # ex) git push origin week1
```

### 4️⃣ 개인 레포지토리에서 PR 생성하기
1. GitHub 개인 레포지토리에 접속 후 `Pull Request` 버튼 클릭
2. PR 타이틀을 `[weekN] 닉네임/본명 N주차 미션 제출` 로 작성
3. PR 내용을 아래 템플릿을 참고하여 작성
   ```markdown
   ## 📌 이슈 번호
   #1

   ## 💻 작업 내용
   - [x] 기능 1 구현
   - [x] 예외 처리 추가

   ## 📢 기타 사항
   - 추가적으로 고려해야 할 부분이 있을까요?
   ```
4. PR 생성 후, **UMC Ewha 8th 조직 레포지토리에 PR을 한 번 더 보냅니다.**
5. 조직 레포지토리에서 자신의 브랜치로 merge 후, 최종적으로 제출 완료!

> 🚧 **주의 사항**  
> - **조직 레포지토리의 main 브랜치에는 merge하지 말아주세요!**
> - **개인 브랜치에서만 작업 후, 조직 레포지토리의 동일한 브랜치로 PR을 보냅니다.**

---

## 🐱 코드 리뷰 및 협업

- PR을 보내면, 같은 스터디원이 리뷰를 진행합니다.
- 리뷰어의 피드백을 확인 후, 필요한 수정 사항을 반영합니다.
- 리뷰가 완료되면 본인이 직접 merge합니다.

> 🛠 **PR 작성 규칙**
> - **Title:** `[Week 숫자] 해당 주차 제목_닉네임`
>   - ex) `[Week 1] Server 기초_루이`
> - **Content:** 
>   ```markdown
>   ## 📌 이슈 번호
>   #이슈번호
>
>   ## 💻 작업 내용
>
>   ## 📢 기타 사항
>   ```
> - **Reviewers:** 스터디원 추가
> - **Assignees:** 본인 선택
> - **Labels:** PR 성격에 맞게 추가 (선택)

🐰 **UMC Ewha 8기**에서 깃허브 사용에 익숙해지셨으면 좋겠습니다! 모르는 부분은 언제든 질문 주세요 (´▽`ʃ♡ƪ) ✨
