# RoR Scaffold LikeLion 6th

## 개발 환경 설정 순서
* Select C9 workspace template 'Ruby'
* Move to 'Gemfile'
* gem 'rails', '4.2.5' edit to gem 'rails', '~> 5.0.6'
* 'Gemfile' Save
* bundle update
* rails -v

## 스캐폴드
* rails g scaffold post title:string content:text


## rails 명령어
* rake routes : 설정되어 있는 모든 라우트 확인