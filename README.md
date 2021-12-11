# OHJUNGGYU GIT BOLG 
## 환경
1. 윈도우 10 환경에 WSL 리눅스 18.04를 설치합니다.
2. WSL에 jekyll을 설치합니다.
3. 이후 깃허브에서 <username>.github.io로 레포를 생성합니다.
4. bundle install과 bundle update를 해줍니다.
5. ohjunggyu.github.io라는 폴더를 생성합니다.
6. 해당 폴더를 깃허브 공식 가이드를 따라 깃허브와 연동시킵니다.
7. 이후 폴더에서 bundle 을 쳐주고 nano gemfile로 편집해줍니다.
   1. gem "github-pages", "~> 222", group: :jekyll_plugins 라는 문구를 gemfile에 등록합니다.
   2. gem "jekyll"를 삭제합니다.
8. bundle install을 해주며 깃허브 플러그인을 설치하고 만약 오류가 있다면 gemfile.lock 을 지워줍니다.
9. 깃허브에 올리기 위해 remote_theme를 사용합니다.
10. _config.yml파일에서  gem"minima" 를 삭제해줍니다.
11. 이후 remote_theme: StartBootstrap/startbootstrap-clean-blog-jekyll 를 입력해줍니다.
12. 잘 되는지 확인하고 내용들을 알차게 채워준뒤 플러그인을 추가하고 푸쉬합니다.

## 구글 애널리스틱
1. 애널리스틱에 가입 이후 UA id를 찾아야 합니다.
아래 링크를 통해 볼수 있습니다.
https://devsungyeon.github.io/github%20blog/Google-analytics/

2. 이후  _config.yml파일에서 google_analytics: 'UA-<ID>' 항목을 추가해줍니다. 
3. 구글 애널리스틱으로 데이터가 들어오는지 확인합니다
