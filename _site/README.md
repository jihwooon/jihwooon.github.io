
## github 이력서 만들기

마음에 드는 템플릿을 가져옵니다
-> [modern-resum-theme](https://github.com/sproogen/modern-resume-theme)

위 템플릿 Readme에 친절하게 설명되어 있습니다.

### Step 1 - GitHub
github 계정이 없을 시 가입을 합니다.

### Step 2 - Create Repository
자신의 github 계정에 Repository를 생성합니다.

```bash
계정아이디.github.io //이력서용 깃허브 레포지토리 이름
```
`계정아이디.github.io` 레포지토리 주소를 작성해줍니다.


### Step 3 - Download Resume Template
자신의 Local Storage에 `Resume Template`를 다운을 받습니다.
다운받는 방법은 `.zip` 파일로 다운을 받는 방법이 있습니다.

```bash
mkdir <생성하고 싶은 디렉토리 이름>
cd <생성한 디렉토리 이름>
git clone <resume-theme 원격 저장소 주소>
```

### Step 4 - Push it
Local Storage에서 github Repository로 push를 합니다.
```bash
git branch -M main // master에서 main으로 변경
git add .
git commit -m "first init"
git push origin main
```
###  Step 5 - Run
```
1. `bundle install`
2. `bundle exec jekyll serve`
3. Open your browser to `http://localhost:4000`
```

## Reference
- [bundle exec jekyll serve 구동 문제를 해결하라](https://github.com/jihwooon/jihwooon.github.io/commit/78564c4374760dee2a08ac27f09f86ec286443cb)