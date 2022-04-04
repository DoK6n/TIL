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
>> useReducer및 Custom useReducer 구현 : https://codesandbox.io/s/usereducer-hx6vu4?file=/src/CustomHooks/CustomHookCounter.js  
>> ContextAPI을 이용한 상태값 추가 삭제 실습  

**[2022.3.22] NodeJS buffer, ArrayBuffer, DataView, TS config**  
>> Unsigned Int 8bit -> 16bit, 32bit 변환하여 바이너리파일 읽기  
>> Typescript tsc, ts-node, ts-node-dev, tsconfig.json  

**[2022.4.1 ~ 4.2] Electron + React + Codemirror로 마크다운 에디터 구현**
>> Electron + Vue Boilerplate에서 React로 변경  
>> Codemirror 라이브러리  
