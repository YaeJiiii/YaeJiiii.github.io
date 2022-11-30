![preview YAEJI'S BLOG!](/blog-preview.jpg)

## My project Build Process
약 한달에 걸쳐 git과 github 그리고 그 외 다양한 사이트와 기능들을 배우면서 최종적으로 나만의 git 블로그를 완성하였다. Git, Github, jekyll, markdown에 대한 자세한 내용은 블로그 [post](https://yaejiiii.github.io/blog/welcome-to-jekyll/)에서 확인할 수 있다.

## Github 환경 구축하기

- Github 계정 생성과 Repository를 생성 (저장소 이름 :username.github.io)
- Local -Remote Repository 와 연동

저장소 Remote Repository의 주소를 복사하고 원하는 위치에서 터미널을 연다.
```c
git clone https://github.com/YaeJiiii/YaeJiiii.github.io.git
```




- [Dark Mode support](https://github.com/brianmaierjr/long-haul/blob/master/preview-dark.png) via [prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) 

## Jekyll 설치 및 확인

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Long Haul repo](http://github.com/brianmaierjr/long-haul)
3. Clone it
4. [Install Bundler](http://bundler.io/)
5. Run `bundle install`
6. Install gulp dependencies by running `npm install`
7. Run Jekyll and watch files by running `bundle exec gulp`
8. Customize and watch the magic happen!

## 나만의 블로그 만들기 (1) - 기본테마

The main settings can be found inside the `_config.yml` file:

- **title:** title of your site
- **description:** description of your site
- **url:** your url
- **paginate:** the amount of posts displayed on homepage
- **navigation:** these are the links in the main site navigation
- **social** diverse social media usernames (optional)
- **google_analytics** Google Analytics key (optional)

### Header Option

If you'd like your header to be larger then you can use the option below in you `config.yml` to make it take up half of the vertical space on screens 800px wide and up. *Preview image below.*

- **header:** large

![preview Long Haul](/preview-large.png)

## 나만의 블로그 만들기 (2) - 테마 입히기
This is [MIT](LICENSE) with no added caveats, so feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.


## 나만의 블로그 만들기 (3) - comment 추가하기 및 그 외 기능들


