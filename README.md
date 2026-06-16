# 사자가온다 제안서 링크페이지

사자가온다에서 제작한 제안서(주로 HTML)파일들을 모아두고, GitHub Pages로 바로 확인할 수 있도록 관리하는 레포입니다.

제안서는 아래 링크에서 확인할 수 있습니다.

## 제안서 링크

### 0. 기본 링크 페이지

https://sajagaonda.github.io/proposals/

### 1. DREAMTELLER

https://sajagaonda.github.io/proposals/dreamteller/

### 2. AI X 게임 제작 부트캠프

https://sajagaonda.github.io/proposals/ai-game-camp.html

### 3. 패밀리톡톡! 가족 숏폼 만들기

https://sajagaonda.github.io/proposals/family-talktalk.html

---

## 새로운 제안서 추가하는 방법

새로운 제안서를 추가할 때는 `main` 브랜치에 파일을 업로드하면 됩니다.

GitHub main 브랜치에 push를 진행하면 자동으로 웹 사이트에 반영됩니다.

### 1. HTML 파일 준비하기

새 제안서 파일을 준비합니다.

예시:

```txt
new-proposal.html
```

이미지나 추가 파일이 있는 프로젝트라면 폴더로 묶어서 준비합니다.

예시:

```txt
new-proposal/
├─ index.html
└─ images/
   └─ sample.png
```


---

### 2. main 브랜치에 Push하기

GitHub Desktop이나 GitHub 웹사이트에서 파일을 추가한 뒤, 반드시 `main` 브랜치에 저장합니다.

GitHub Desktop을 사용하는 경우:

1. 파일을 main 브랜치에 업로드하기
2. GitHub Desktop에서 변경된 파일 확인하기
3. 커밋 메시지 작성하기
4. `Commit to main` 클릭하기
5. `Push origin` 클릭하기

---

### 4. 잠시 기다린 뒤 확인하기

`main` 브랜치에 Push하면 GitHub Pages가 자동으로 새 파일을 반영합니다.

보통 **30초~1분 정도 기다리면** 웹에서 확인할 수 있습니다.

바로 안 보이면 조금 더 기다린 뒤 새로고침하면 됩니다.

---

### 5. 파일명으로 접속하기

HTML 파일은 **파일명까지 정확히 입력해야** 접속할 수 있습니다.

예를 들어 파일을 이렇게 올렸다면:

```txt
proposals/new-proposal.html
```

접속 주소는 이렇게 됩니다.

```txt
https://sajagaonda.github.io/proposals/new-proposal.html
```

폴더 안에 `index.html`로 올렸다면:

```txt
proposals/new-proposal/index.html
```

접속 주소는 이렇게 됩니다.

```txt
https://sajagaonda.github.io/proposals/new-proposal/
```

파일명은 대소문자까지 정확히 맞아야 합니다.

예를 들어 아래 파일명들은 서로 다른 파일로 인식됩니다.

```txt
family-talktalk.html
Family-talktalk.html
family-talktalk.HTML
```

---

## 추가로 해야 될 내용

새로운 제안서를 추가한 뒤에는 아래 내용도 같이 확인합니다.

### 1. 링크페이지에 새 제안서 추가하기

새 제안서를 추가했다면 `proposals/index.html`에도 링크를 추가해야 합니다.

그래야 아래 주소에서 새 제안서가 목록에 보입니다.

```txt
https://sajagaonda.github.io/proposals/
```

---

### 2. 파일명 확인하기

URL은 파일명과 똑같이 입력해야 합니다.

파일명에 띄어쓰기, 한글, 특수문자가 많으면 주소가 복잡해질 수 있으니 되도록 영어 소문자와 하이픈을 사용합니다.

좋은 예시:

```txt
ai-game-camp.html
family-talktalk.html
new-proposal.html
```

피하는 것이 좋은 예시:

```txt
새 제안서 최종본.html
new proposal final.html
proposal(최종).html
```

---

### 3. 이미지 경로 확인하기

제안서 안에 이미지가 있다면 이미지 경로가 잘 맞는지 확인합니다.

추천하는 방식:

```html
<img src="./images/logo.png" alt="로고">
```

주의가 필요한 방식:

```html
<img src="/images/logo.png" alt="로고">
```

`/images/logo.png`처럼 앞에 `/`가 붙으면 사이트 전체의 최상위 폴더에서 이미지를 찾기 때문에 이미지가 깨질 수 있습니다.

---

### 4. 모바일에서 확인하기

제안서는 주로 휴대폰에서 확인할 수 있으므로 업로드 후 모바일에서도 꼭 확인합니다.

확인할 내용:

* 글자가 너무 작지 않은지
* 이미지가 화면 밖으로 튀어나가지 않는지
* 버튼이나 링크가 잘 눌리는지
* 세로 스크롤이 자연스럽게 되는지

---

### 5. 링크 공유 전 최종 확인하기

외부에 링크를 보내기 전에 아래 순서로 확인합니다.

1. 제안서 링크가 잘 열리는지 확인
2. 이미지가 깨지지 않는지 확인
3. 모바일에서 보기 편한지 확인
4. `proposals/index.html` 링크 목록에 잘 추가되었는지 확인
5. 최종 링크를 복사해서 공유

---

## 기본 링크페이지

전체 제안서 목록은 아래 주소에서 확인할 수 있습니다.

https://sajagaonda.github.io/proposals/
