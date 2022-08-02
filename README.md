# TIL

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FDoK6n%2FTIL&count_bg=%235B4C8C&title_bg=%235B4C8C&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

### Rules
- 메인 README 내용은 간략화하여 작성
- 상세내용은 md 추가 작성

---  
</br></br>

# Today I Learned List

**[2021.12.22] AWS DMS 분석 - RDS to DynamoDB**
> IAM 정책, 역할 추가  
> 복제 인스턴스 생성  
> 소스/타겟 엔드포인트 생성  
> 데이터 마이그레이션 태스크 생성 및 객체 맵핑 구성  
> 최적화 없이 그냥 1:1 맵핑 -> 약 2만건 3m 30s 

**[2021.12.23] Android Termux어플에 개발환경 구성**
> termux 단축키 설정 path: ~/.termux/termux.properties  
> install: termux-style, fish shell, oh-my-fish, z, exa, hexyl, gcc, nodejs, neovim(with lunarvim IDE), mariadb

**[2021.12.26] Interective Web develop**
> mouse move, parallax scrolling, progress bar  
> [Interective Web Samples Repo](https://github.com/DoK6n/interective-web-samples "go repo")

**[2021.12.27] Interective Web develop**
> 교차 페이지 효과

**[2021.12.28] 업비트 API 및 사이트 분석** 

**[2021.12.30] AWS DMS 성능 최적화로 속도 향상**
> Task 설정: "ParallelApplyThreads": 10, "ParallelApplyBufferSize": 500 -> 약 10배가량 속도 향상

**[2021.12.30] WSL2 Ubuntu-18.04에 개발환경 구성**
> fish shell, oh-my-fish, z, exa, hexyl, gcc, fzf, nvm, neovim(with lunarvim IDE) 

**[2022.1.2] React Hooks: useState, useEffect 동작 원리 이해를 위한 내부코드 구현**

**[2022.1.3] AWS DMS TASK 옵션**
> 대상 테이블 준비 모드(Target table preparation mode): DO_NOTHING, DROP_AND_CREATE, TRUNCATE_BEFORE_LOAD  
> 태스크 Amazon CloudWatch Logs로 태스크 로그 활성화

**[2022.1.3] JS Closure 착각하기 쉬운 부분**
> 내부에 선언된 함수가 외부함수의 지역변수를 사용해 줬을 때만 클로저라고 선언됨  
> 클로저인 경우 console.dir로 [[Scopes]] 부분에 Closure라는 항목을 확인가능

**[2022.1.10] React Hooks: 내장 함수 공부**
> useMemo, useCallback, React.memo, useReducer, Context API, class component lifecycle

**[2022.1.20] Husky로 커밋 메시지 검증하기**
> Husky, conventional commit, commitlint

**[2022.2.1] NestJS Typeorm Migration**

**[2022.2.2] AWS EC2에 docker에 nginx로 배포 테스트**
> 참고 영상: https://youtu.be/HvrIPQ77xRY  
> test link: http://15.164.214.228/hello.html

**[2022.2.3] AWS VPC, 서브넷**  

**[2022.2.5] docker, docker-compose, nodejs cluster 대용량 트래픽 처리**

**[2022.2.14] AWS IoT Core**  
> 스마트 디바이스, 제어 디바이스, 디바이스 섀도우, IoT Core, 정책

**[2022.2.14] Deno**  
> https://deno.land/  
> https://youtu.be/Kg4yubiBZ4A

**[2022.2.15] Apple Login**  
> apple developer 문서 분석  
> apple-auth모듈 분석  

**[2022.3.17] AWS IoT Core**  
> 디바이스에 인증서 등록하는 방법 4가지  
> 1. Bulk Registration  
>>  - 공장 출하시 장치와 서버에 일괄 등록하는 방법  
>  
> 2. JITR(Just int Time Registration), JITP(Just In Time Provisioning)  
>>  - Bulk Registration과 마찬가지로 장치에 인증서 넣어 출하 후 장치가 AWS IoT에 최초 연결될 때 IoT 서버에 등록하는 방법  
>>>  - JITR : MQTT Event 및 Lambda 함수를 통해 등록  
>>>  - JITP : AWS IoT Core API를 통해 등록(JITR 간소화 버전)  
>  
> 3. Fleet provisioning  
>>  - 생산 시 장치에서 동일한 등록용 인증서(프라이빗 키 포함)를 포함 시켜 출하 후 AWS IoT에 최초 연결 시 해당 인증서를 통해 고유 인증서를 발급받는 방법  

**[2022.3.19] React useReducer 구현 및 ContextAPI**
> useReducer및 Custom useReducer 구현 : https://codesandbox.io/s/usereducer-hx6vu4?file=/src/CustomHooks/CustomHookCounter.js  
> ContextAPI을 이용한 상태값 추가 삭제 실습  

**[2022.3.22] NodeJS buffer, ArrayBuffer, DataView, TS config**  
> Unsigned Int 8bit -> 16bit, 32bit 변환하여 바이너리파일 읽기  
> Typescript tsc, ts-node, ts-node-dev, tsconfig.json  

**[2022.3.27] Drag & Drop**
> react-beautiful-dnd 라이브러리

**[2022.4.1 ~ 4.2] Electron + React + Codemirror로 마크다운 에디터 구현**
> Electron + Vue Boilerplate에서 React로 변경  
> Codemirror 라이브러리  

**[2022.4.4 ~ 4.5] Electron IPC Module로 Main <-> Renderer 프로세스간 통신 구현**
> Renderer -> Main  
> Renderer -> Main -> Renderer  
> Renderer Upload File -> Main receive File Data  

**[2022.4.6] Elastic Beanstalk AMI Docker 플랫폼 배포 실패 이슈**  
> EC2에 올라간 소스와 exec 명령어로 도커 컨테이너에 올라간 빌드된 소스 버전 비교  
> 둘이 서로 다른것 확인 후 eb 로그 확인  
> C++ 위치정보암호화 모듈사용을 위해 addon build하는 과정에서 실패하여 EB에서 최근 배포 성공한 소스의 컨테이너를 올림  
> aws콘솔에서 EB 플랫폼 버전을 업데이트 후 성공  

**[2022.4.7] JS Bundler Vite**
> 기존 번들러보다 빠르게 번들링이 가능한 빌드 도구  
> 앱을 종속성과 소스코드 두 가지 범주로 나누어 시작시간을 대폭 향상  
> 의존성이 큰 앱의 경우 ESBuild로 종속성을 사전 번들링함  
> ESBuild는 Go로 작성되어 매우 빠름  
> vue, react, preact, lit, vanila, lit, svelte등 기본 템플릿 제공  

**[2022.4.10] EC2에 Docker Log 관리**
> 컨테이너 로그 확인 - `docker log -f {{container id 혹은 name}}`  
> 컨테이너 로그는 `/var/lib/docker/containers/`에 저장됨  
> 컨테이너가 완전히 삭제되면 해당 컨테이너의 폴더도 같이 삭제됨  
> Elasticbeanstalk 로그 관리 과정  
>> - logrotate로 과거,최근 로그 시점과 삭제등 다양한 설정으로 관리  
>> - cron으로 logrotate를 주기적으로 실행  
>> - 도커 컨테이너는 awslogs를 이용하며 s3에도 로그를 관리  

**[2022.04.10] Git Log Custom Alias 설정**
```bash
git config --global alias.hist "log --graph --all --pretty=format:'%C(yellow)[%ad]%C(reset) %C(green)[%h]%C(reset) | %C(white)%s %C(italic magenta)(%cr) %C(bold red)<%an>%C(reset) %C(blue)%d%C(reset)' --date=short"
```

**[2022.4.16 ~ 17] Nginx 로드밸런싱과 Docker 컨테이너 포트 관련**
> upstream을 이용한 로드밸런싱  
> Dockerfile EXPOSE와 docker run -p의 차이점  
>> EXPOSE  
>>> Dockerfile로 build한 image로 띄운 컨테이너의 포트를 외부로 개방  
>>> 하지만 사용자가 해당 포트로 접근하는것은 아니며 호스트OS로 들어오는 포트와 해당 포트를 매핑시켜야 함  
>   
>> docker run -p 80:3000  
>>> 호스트OS와 컨테이너의 포트를 매핑  
>>> 좌측 [실사용자가 접근할 포트] : 우측 [컨테이너의 포트]  

**[2022.4.24 ~ 25] S3, CloudFront, Route53 배포**  

**[2022.5.1] zustand**
> 상태관리 라이브러리 zustand  
> 미들웨어를 통해 react-devtools 사용 가능  
> Provider로 래핑하지 않아도 됨  
> boilerplate가 적음  
> 원본 코드는 Typescript로 작성  
> Zustand는 발행/구독 모델을 기반이며 클로저를 활용  
> Context API를 사용할 때와 달리 상태 변경 시 불필요한 리렌더링을 일으키지 않도록 제어하기 쉽다  
>> Context API의 불필요한 리렌더링 해결 방안  
>> - 하나의 거대한 값을 가진 Context를 만들지 말고 여럿으로 분리하여 필요한 부분만 사용하기  
>> - 컴포넌트를 쪼개고 React.memo 를 활용하기  
>> - useMemo 훅을 사용하여 컴포넌트 랜더링 부분을 감싸기  

**[2022.5.12] markdown preview editor (velog 참조)**  
> editor : codemirror6  (_velog : codemirror5_)  
> preview : react-markdown  
> 링크 : [preview editor playground](https://podote.com/mdplayground)  

**[2022.6.1] React `JS` &#8594; `TS`로 전환 작업**  
> [링크](https://github.com/DoK6n/podote/commit/2eaa7a76b5ec4438a5b630628bb5914e29cd382b)  
> `이슈`: 사용하던 [react-clipboard-button](https://github.com/guipas/react-clipboard-button) 라이브러리에서 TS로 전환하는 과정에서 children type 관련 이슈 발생  
> `오픈소스 기여`: 수정하여 [PR](https://github.com/guipas/react-clipboard-button/pull/3) 보냈지만 답장이 늦어질것 같아 라이브러리 소스가 몇줄 안되서 프로젝트 내로 옮김  
> 현재는 `closed` 됨.  

**[2022.7.22] React + Firebase Google Auth**  
> React에서 Firebase Auth로 Google 인증  

**[2022.8.2] Docker Volumn + postgresql**  
> ```bash
> $ mkdir /Users/Shared/databases/postgresql/data    # DB 데이터 저장할 로컬PC 경로
> $ docker pull postgres:latest     # postgres 이미지 받음
> $ dokcer run -p 5432:5432 --name postgres-container \     # postgres 이미지로 컨테이너 띄움 - 데이터의 영속성을 위해 볼륨옵션 추가
>  -e POSTGRES_PASSWORD=1234 \
>  -v /Users/Shared/databases/postgresql/data:/var/lib/postgresql/data -d \     # : 를 기준으로 데이터가 저장될 경로를 나눔 
>  postgres:latest                                                              # -> 로컬 PC 경로 : 컨테이너 내 경로
>  
> $ docker ps
> $ docker exec -it postgres-container \bin\sh   # container 접속
>  $ psql -U postgresql   # db 접속
>  # CREATE DATABASE test;    # 확인용 DB 추가
> $ docker rm -f postgres-container    # 컨테이너 삭제
> # 다시 docker run후 test db 추가되어있는지 확인
> ```  
