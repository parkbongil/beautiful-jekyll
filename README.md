# Parkbongil Pages

Parkbongil Pages 는 개인 블로그 입니다.  
정적인 사이트의 무료호스팅 서비스를 제공하는 [Github Pages](https://pages.github.com/)를 이용하고 있습니다. 테마는 [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll)를 사용했습니다. 주요특징 및 사용법은 Beautiful Jekyll 저장소를 참고바랍니다.

## 윈도우즈에서 Jekyll 실행

Windows 10에서 localhost로 실행해 보기 위해서 [윈도우즈에서의 Jekyll](https://jekyllrb-ko.github.io/docs/windows/)에서 제시하는 방법대로 설치 및 설정변경을 하면 됩니다. Ruby+Devkit 2.5.5-1 (x64) 버전으로 확인한 상태 입니다.

1. 설치한 루비 터미널을 엽니다.
2. 터미널에서 클론한 위치로 이동합니다. (예. cd c:\parkbongil.github.io)
3. 터미널에서 'chcp 65001' 를 입력합니다.
4. 터미널에서 'jekyll serve' 를 입력합니다.
5. 브라우저 주소창에 터미널 로그에 안내한 'localhost:4000'을 입력합니다.

## 새로운 윈도우에서 동일한 Jekyll 환경 만들기

최초 Jekyll 환경을 만들고 운영하다가 PC를 포멧하거나 다른 PC에서 동일한 환경을 만들수 있습니다.

1. Ruby+Devkit 2.5.5-1 (x64)을 설치합니다. (최초환경버전)
2. 설치한 루비 터미널을 엽니다.
3. 터미널에서 'gem install bundler -v2.0.1' 를 입력합니다. (최초환경버전)
4. 터미널에서 클론한 위치로 이동 후 Gemfile.lock 파일을 삭제합니다. (예. cd c:\parkbongil.github.io)
5. 터미널에서 'bundle install' 를 입력합니다.
6. 이후는 윈도우에서 Jekyll 실행과 동일합니다.
