# Typescript + TSLint + Mocha + Chai + ts-node + nyc로 모던한 프론트 엔드 테스트 환경 구축
[![Build Status](https://travis-ci.org/perfectacle/front-test-setting.svg?branch=travis-ci)](https://travis-ci.org/perfectacle/front-test-setting)
[![Coverage Status](https://coveralls.io/repos/github/perfectacle/front-test-setting/badge.svg?branch=coveralls)](https://coveralls.io/github/perfectacle/front-test-setting?branch=coveralls)

* Typescript: ES2015+의 슈퍼셋 격으로 자바스크립트에 정적 타입 및 다양한 기능을 부여한 언어  
* TSLint: 협업하는데 코드의 일관성과 품질을 높이기 위해 코딩 컨벤션을 준수하게 끔 도와주는 도구  
* Mocha: 자바스크립트의 테스트 코드를 작성하는데 도와주는 도구  
* Chai: 테스트 코드의 Assertion을 도와주는 라이브러리  
* ts-node: Typescript 런타임을 제공해주는 노드 라이브러리  
* nyc: 테스트 커버리지 도구인 Istanbul의 CLI
* rollup: 여러 모듈 간의 의존 관계를 파악해서 하나의 모듈로 말아주는 모듈 번들러  
* Travis CI: 테스트, 빌드, 배포 등등을 자동화 시켜주는 도구로써 별도의 CI 서버 구축이 필요 없음.  
* Coveralls: Travis CI -> NYC -> Coveralls -> Github의 구조로 테스트 커버리지를 전파해줌.