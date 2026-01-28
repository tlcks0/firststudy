# PRIBIT Connect Agent를 통한 PRIBIT Connect SDP(VPN) 접속 안내

아래 단계에 따라 PRIBIT Connect Agent로 Pribit Controller 와 인증하고 Gateway(Tunnel)에 접속할 수 있습니다.

<br>

- [1. PRIBIT Connect Agent 실행](#1-)
- [2. PCA 접속 로그인 정보 입력](#2-)
- [3. PCA 로그인 완료](#3-)

<!-- TOC end -->

<br>

<!-- TOC --><a name="1-"></a>
## 1. **PRIBIT Connect Agent 실행**
- 설치된 PRIBIT Connect Agent 프로그램을 실행합니다.
- 프로그램 설치는 이전 페이지에서 다운로드 받아 설치해주세요. 

<br>

<!-- TOC --><a name="2-"></a>
## 2. **PCA 접속 로그인 정보 입력**  
PCC 사용자 ID와 비밀번호를 입력하여 로그인합니다. 
![pca controller access](/img/agent_controller_access.png)  
  - 컨트롤러 서버 주소 : PCC Server 주소를 입력합니다.   
  - 입력된 주소로 TLS(TCP 443 Port)통신을 통해 컨트롤러와 인증처리를 수행합니다.  
    - **컨트롤러 서버 주소 : 110.45.174.35**  
  - 컨트롤러 아이디 : PCC 에 설정한 컨트롤러 아이디를 입력합니다.  
    - **컨트롤러 아이디 : neopharm**  

<br>

접속할 사용자 아이디와 비밀번호를 입력합니다.  
![pca user login](/img/agent_controller_user_login.png)  
  - 사용자 아이디 : PCC 에 등록된 사용자 아이디를 입력합니다.  
  - ex) *pribit*  
  - 사용자 비밀번호 : 로그인 할 사용자의 비밀번호를 입력합니다.  
  - ex) *******  

<br>

<!-- TOC --><a name="3-"></a>
## 3. **PCA 로그인 완료**  

로그인이 정상적으로 완료되면 다음과 같은 화면으로 이동합니다.  
![pca login complete](/img/agent_login_complete.png)  

<br>

*** 

> 접속 과정에서 문제가 발생할 경우 관리자에게 문의하세요.
