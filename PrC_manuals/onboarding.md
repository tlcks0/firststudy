# PRIBIT Connect Agent를 통한 PRIBIT Connect SDP(VPN) 접속 안내 (Onboarding)

아래 단계에 따라 PRIBIT Connect Agent로 Pribit Controller 와 인증하고 Gateway(Tunnel)에 접속할 수 있습니다.  


<br>

- [1. PRIBIT Connect Agent 실행](#1-)
- [2. PCA 접속 로그인 정보 입력](#2-)
- [3. PCA OTP 등록](#3-)
- [4. PCA 임시 비밀번호 변경](#4-)
- [5. PCA 로그인 완료](#5-)
- [6. VDI 접속](#6-)

<!-- TOC end -->

<br>

<!-- TOC --><a name="1-"></a>
## 1. **PRIBIT Connect Agent 실행**
- 설치된 PRIBIT Connect Agent 프로그램을 실행합니다.
- 프로그램 설치는 이전 페이지에서 다운로드 받아 설치해주세요. 

<br>

<!-- TOC --><a name="2-"></a>
## 2. **PCA 접속 로그인 정보 입력**  
PCC 접속 주소와 컨트롤러 아이디를 입력하여 로그인 합니다.  
![pca controller access](/img/agent_controller_access.png)  
  - 컨트롤러 서버 주소 : PCC Server 주소를 입력합니다.   
  - 입력된 주소로 TLS(TCP 443 Port)통신을 통해 컨트롤러와 인증처리를 수행합니다.  
    - **컨트롤러 서버 주소 : 211.173.76.19**  
  - 컨트롤러 아이디 : PCC 에 설정한 컨트롤러 아이디를 입력합니다.  
    - **컨트롤러 아이디 : kicox**  

<br>

접속할 사용자 아이디와 비밀번호를 입력합니다.   
![pca user login](/img/agent_controller_user_login.png)   
  - 사용자 아이디 : PCC 에 등록된 사용자 아이디를 입력합니다.  
  - ex) *[신청한 사용자 ID]*  
  - 사용자 비밀번호 : 로그인 할 사용자의 비밀번호를 입력합니다. 
  - ex) *[임시 비밀번호 : 1111]*   

<br>

<!-- TOC --><a name="3-"></a>
## 3. **PCA OTP 등록**  

OTP 를 등록합니다. 
휴대폰에서 Google Authenticator 앱을 열어 화면에 보이는 QR 코드를 스캔합니다.  
(Google Authenticator 앱을 등록하는 방법은 [여기](/manual/google-otp.md)를 참고하세요.) 

![pca user login otp registration](/img/agent_user_login_otp_registration.png)   

성공적으로 등록이 완료되면, OTP 앱에서 OTP 코드를 확인하여 화면에 보이는 6자리 OTP 인증 코드를 입력합니다.   

![pca user login otp registration](/img/agent_user_login_otp_verification.png)   

정상적으로 등록이 완료되면, OTP 등록 & 검증이 완료됩니다.   

> [!NOTE]  
> OTP 등록이 완료되면 다시 로그인을 수행합니다.  

<br> 

[2. PCA 접속 로그인 정보 입력](#2-) 과정을 다시 수행합니다.  

<br>

<!-- TOC --><a name="4-"></a>
## 4. **PCA 임시 비밀번호 변경**  

임시 비밀번호를 사용하여 로그인 한 사용자는 반드시 비밀번호를 변경해야 합니다. 

> [!NOTE]   
> 사용자 최소 생성 시 임시 비밀번호를 발급받습니다.    

아래 절차대로 임시 비밀번호를 변경합니다.   

![pca user login temporary password](/img/agent_user_login_temporary_password.png)   

- `지금 변경` 버튼을 눌러 변경을 시작합니다.  
- *`앱 종료` 버튼을 누르면 에이전트 프로그램이 종료됩니다.*   

사용자 임시 비밀번호 변경을 위한 사용자 인증(MFA)을 수행합니다.  

![pca user login temporary password - mfa email](/img/agent_user_login_mfa_email.png)   

사용자 인증(MFA)은 계정에 등록된 이메일로 OTP 코드가 전달됩니다. 

![pca user login temporary password - mfa email](/img/agent_user_login_mfa_email_otp_code.png)   

이메일로 전달된 OTP 코드를 앱 화면에 입력하여 인증합니다.   
정상적으로 사용자 인증(MFA)이 완료되면 비밀번호를 변경하는 화면으로 이동합니다.  

![pca user login change temporary password](/img/agent_user_login_change_temporary_password.png)   
- `임시 비밀번호` : **1111** 
- `새 비밀번호`, `새 비밀번호 재입력` : *아래 규칙에 맞게 입력합니다.*  

> [!NOTE]  
> 9 ~ 16 자리 이내로 입력해주세요.  
> 영문 대문자, 소문자, 숫자, 특수문자를 포함해주세요.  
> (&, <, >, ", ', ., \, /, 빈칸 제외)  
> 3자리 이상의 동일한 문자 또는 숫자 없이 입력해 주세요.  
> 키보드 상에서 연속된 4자리 이상의 문자 또는 숫자 없이 입력해 주세요.  
> 아이디와 4자리 이상 유사하지 않게 입력해주세요.  

정상적으로 등록이 완료되면, 비밀번호 변경 메시지가 팝업됩니다.  
*(비밀번호를 변경했습니다. 변경한 비밀번호로 다시 로그인해 주세요.)*   

![pca user login complete changing temporary password](/img/agent_user_login_complete_changing_temporary_password.png)  

<br>  

> [!NOTE]  
> 비밀번호 변경이 완료되면 변경된 비밀번호로 다시 로그인을 수행합니다.  

<br> 

[2. PCA 접속 로그인 정보 입력](#2-) 과정을 다시 수행합니다.  

<br> 

<!-- TOC --><a name="5-"></a>
## 5. **PCA 로그인 완료**   

로그인이 정상적으로 완료되면 다음과 같은 화면으로 이동합니다.   
![pca login complete](/img/agent_login_complete.png)   

<!-- TOC --><a name="6-"></a>
## 6. **VDI 접속**

접속된 프로그램 화면에서 `서비스` 를 선택합니다. 
`VDI 접속` 을 눌러 VDI 를 실행합니다. 

![pca service vdi](/img/agent_service_vdi.png)  

<br>

*** 

<br>

> 접속 과정에서 문제가 발생할 경우 관리자에게 문의하세요.
