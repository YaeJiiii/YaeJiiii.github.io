![blog-preview](https://user-images.githubusercontent.com/105334974/204706833-933081cd-e277-4f2f-a7bb-145f618e2a82.JPG)

## My project Build Process
약 한달에 걸쳐 git과 github 그리고 그 외 다양한 사이트와 기능들을 배우면서 최종적으로 나만의 git 블로그를 완성하였다. Git, Github, jekyll, markdown에 대한 자세한 내용은 블로그 [post](https://yaejiiii.github.io/blog/welcome-to-jekyll/)에서 확인할 수 있다.

## Github 환경 구축하기

- **Github 계정과 Repository를 생성** 
    (저장소 이름 :username.github.io)
- **Local -Remote Repository 와 연동**

    저장소 Remote Repository의 주소를 복사하고 원하는 위치에서 터미널을 연다.
    ```c
    git clone https://github.com/YaeJiiii/YaeJiiii.github.io.git
    ```
- **commit 확인**
    "Hello world"라는 내용의 `index.html`을 작성 및 현재상태를 확인 후 변경파일을 추가해준다.
    ```c
    git status
    ```
    ```c
    git add .
    ```
    git commit -m "msg"로 커밋을 남긴다
    ```c
    git commit -m "add:index.html"
    ```

- **git push**
    git push로 원격저장소에 반영한다
    ```c
    git branch -M main
    ```
    ```c
    git push origin main
    ```

- **Github Page 설정 확인**
    https://yaejiiii.github.io/로 접속해서 *hello world*가 잘 떠있는지 확인
    

## Jekyll 설치 및 확인

- **Jekyll 환경구성**
    [Install Ruby + Devkit](https://rubyinstaller.org/downloads/)
    [Install Jekyll](http://jekyllrb.com)

    ```c
    gem install jekyll bundler
    ```

- **설치 확인**
    해당 폴더로 들어가서 Jekyll이 잘 설치되어있는지 확인
    되어있다면 버전이 출력될 것
    ```c
    jekyll -v
    ```
- **현재디렉토리 Jekyll 설치**
    ```c
    jekyll new . --force
    ```
    ```c
    ls
    ```
    ```c
    bundle exec jekyll serve
    ```
- **From Local to Remote**
    내 깃허브 저장소로 commit하기
    1. 우선 기존 hello world `index.html`삭제 
    ```c
    git rm index.html
    ```
    2. 파일 추가
    ```c
    git add .
    ```
    3. 커밋메시지 남기기
    ```c
    git commit -m "msg"
    ```
    4. 원격저장소에 반영하기
    ```c
    git push origin main
    ```

- *참고사항*
    - [Install Bundler](http://bundler.io/)
    - Run `bundle install`
    - Install gulp dependencies by running `npm install`
    - Run Jekyll and watch files by running `bundle exec gulp`
    - Customize and watch the magic happen!

## 나만의 블로그 만들기 (1) - 테마입히기

### 마음에 드는 테마 고르기
- [사이트1](http://jekyllthemes.org/)과 [사이트2](https://jekyllthemes.io/free)
- [내가 고른 테마](https://jekyllthemes.io/theme/long-haul)

### 테마 적용하기

- **git clone**
    원하는 테마의 github 주소를 들어가 해당 주소를 복사
    ```c
    git clone (해당주소)
    ```
- **덮어쓰기**
    테마 파일들을 파일 밖으로 덮어쓴다. 

- **로컬저장소에 반영**
    ```c
    git add .
    ```
    ```c
    git commit -m "msg"
    ```
    ```c
    git push origin main
    ```

## 나만의 블로그 만들기 (3) - comment 추가하기 및 그 외 기능들


