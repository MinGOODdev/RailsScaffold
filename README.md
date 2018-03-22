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

## form_for
* 모델 객체 (post)가 신규 or 이미 저장 완료되었는지를 판단해 적절한 url로 안내한다.
* @post = Post.new면 create action으로
* @post = Post.find(params[:id])면 update action으로 알아서 보낸다.


## rails 명령어
* rake routes : 설정되어 있는 모든 라우트 확인