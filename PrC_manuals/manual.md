# PRIBIT Connect Agent 설치 및 사용 가이드

이 문서는 PRIBIT Connect Agent를 설치하고 사용하는 전체 과정을 안내합니다.

<br>

- [1. 설치](#1-설치)
  - [1.1. 사전 준비 사항](#11-사전-준비-사항)
  - [1.2. 설치 파일 다운로드](#12-설치-파일-다운로드)
  - [1.3. 설치 과정](#13-설치-과정)
  - [1.4. 설치 확인](#14-설치-확인)
  - [1.5. 문제 해결](#15-문제-해결)
- [2. PRIBIT Connect Agent 실행](#2-pribit-connect-agent-실행)
- [3. PCA 접속 로그인 정보 입력](#3-pca-접속-로그인-정보-입력)
- [4. PCA OTP 등록](#4-pca-otp-등록)
  - [4.1. Google Authenticator OTP 사용 가이드](#41-google-authenticator-otp-사용-가이드)
- [5. PCA 임시 비밀번호 변경](#5-pca-임시-비밀번호-변경)
- [6. PCA 로그인 완료](#6-pca-로그인-완료)

<!-- TOC end -->

<br>

<!-- TOC --><a name="1-설치"></a>
## 1. 설치

이 문서는 사용자 PC에 Pribit Connect Agent를 설치하는 방법을 안내합니다.

<br>

<!-- TOC --><a name="11-사전-준비-사항"></a>
### 1.1. 사전 준비 사항
- 관리자 권한이 있는 계정 
- 인터넷 연결 

<br><br> 

<!-- TOC --><a name="12-설치-파일-다운로드"></a>
### 1.2. 설치 파일 다운로드  
1) 제공된 설치 파일 [다운로드](https://support.packetgo.com/kr/front/home/neopharm) 링크에서 설치 파일을 다운로드합니다.  
2) 다운로드가 완료되면 파일을 실행합니다.  

<br><br> 

<!-- TOC --><a name="13-설치-과정"></a>
### 1.3. 설치 과정 

1) 설치 마법사의 안내에 따라 **다음**을 클릭하여 진행합니다.  
![Agent Installation - installing](/PrC_manuals/img/agent_installation_installing.png)  

<br>

2) 설치가 완료되면 **마침**을 클릭합니다.  
![Agent Installation - complete install](/PrC_manuals/img/agent_installation_complete_install.png)   

<br><br>

<!-- TOC --><a name="14-설치-확인"></a>
### 1.4. 설치 확인
1) 바탕화면 또는 시작 메뉴에서 Connect Agent 아이콘을 확인합니다.  
![Agent Installation - complete install icon](/PrC_manuals/img/agent_installation_complete_install_icon.png)  

**PRIBIT Connect**

<br>

2) 프로그램이 실행되고 설정할 언어를 선택합니다. 
![Agent Installation Setup](/PrC_manuals/img/agent_installation_setup.png)   
- **English**  
- **한국어** (선택)  

<br>

3) 프로그램을 실행하여 정상적으로 동작하는지 확인합니다. 

<br>

![Agent Start View](/PrC_manuals/img/agent_controller_access.png)

<br><br>

<!-- TOC --><a name="15-문제-해결"></a>
### 1.5. 문제 해결 
- 설치 중 오류 발생 시 관리자 권한으로 다시 시도하세요.
- 추가 지원이 필요하면 IT 기술 지원 담당팀에 문의하세요.

<br>

---

<br>

<!-- TOC --><a name="2-pribit-connect-agent-실행"></a>
## 2. PRIBIT Connect Agent 실행

아래 단계에 따라 PRIBIT Connect Agent로 Pribit Controller 와 인증하고 Gateway(Tunnel)에 접속할 수 있습니다.

<br>

- 설치된 PRIBIT Connect Agent 프로그램을 실행합니다.
- 프로그램 설치는 위의 [1. 설치](#1-설치) 섹션을 참고하세요.

<br>

<!-- TOC --><a name="3-pca-접속-로그인-정보-입력"></a>
## 3. PCA 접속 로그인 정보 입력  

PCC 접속 주소와 컨트롤러 아이디를 입력하여 로그인 합니다.  
![pca controller access](/PrC_manuals/img/agent_controller_access.png)  
  - 컨트롤러 서버 주소 : PCC Server 주소를 입력합니다.   
  - 입력된 주소로 TLS(TCP 443 Port)통신을 통해 컨트롤러와 인증처리를 수행합니다.  
    - **컨트롤러 서버 주소 : 110.45.174.35**  
  - 컨트롤러 아이디 : PCC 에 설정한 컨트롤러 아이디를 입력합니다.  
    - **컨트롤러 아이디 : neopharm**  

<br>

접속할 사용자 아이디와 비밀번호를 입력합니다.   
![pca user login](/PrC_manuals/img/agent_controller_user_login.png)   
  - 사용자 아이디 : PCC 에 등록된 사용자 아이디를 입력합니다.  
  - ex) *[신청한 사용자 ID]*  
  - 사용자 비밀번호 : 로그인 할 사용자의 비밀번호를 입력합니다. 
  - ex) *[임시 비밀번호 : 1111]*   

<br>

<!-- TOC --><a name="4-pca-otp-등록"></a>
## 4. PCA OTP 등록  

OTP 를 등록합니다. 
휴대폰에서 Google Authenticator 앱을 열어 화면에 보이는 QR 코드를 스캔합니다.  

![pca user login otp registration](/PrC_manuals/img/agent_user_login_otp_registration.png)   

<!-- TOC --><a name="41-google-authenticator-otp-사용-가이드"></a>
### 4.1. Google Authenticator OTP 사용 가이드

<br>

#### 4.1.1. 구글 OTP 앱 설치

![Google Authenticator Installation - 1](/PrC_manuals/img/google_otp_1.png)  

<br>

#### 4.1.2. 구글 OTP 앱 실행

![Google Authenticator Installation - 2](/PrC_manuals/img/google_otp_2.png)  

<br>

#### 4.1.3. QR 코드 등록하기

![Google Authenticator Installation - 3](/PrC_manuals/img/google_otp_3.png)  

<br> 

#### 4.1.4. 구글 Authenticator 로 2단계 인증하기

![Google Authenticator Installation - 4](/PrC_manuals/img/google_otp_4.png)  

<br> 

---

<br>

성공적으로 등록이 완료되면, OTP 앱에서 OTP 코드를 확인하여 화면에 보이는 6자리 OTP 인증 코드를 입력합니다.   

![pca user login otp registration](/PrC_manuals/img/agent_user_login_otp_verification.png)   

정상적으로 등록이 완료되면, OTP 등록 & 검증이 완료됩니다.   

> [!NOTE]  
> OTP 등록이 완료되면 다시 로그인을 수행합니다.  

<br> 

[3. PCA 접속 로그인 정보 입력](#3-pca-접속-로그인-정보-입력) 과정을 다시 수행합니다.  

<br>

<!-- TOC --><a name="5-pca-임시-비밀번호-변경"></a>
## 5. PCA 임시 비밀번호 변경  

임시 비밀번호를 사용하여 로그인 한 사용자는 반드시 비밀번호를 변경해야 합니다. 

> [!NOTE]   
> 사용자 최소 생성 시 임시 비밀번호를 발급받습니다.    

아래 절차대로 임시 비밀번호를 변경합니다.   

![pca user login temporary password](/PrC_manuals/img/agent_user_login_temporary_password.png)   
- `지금 변경` 버튼을 눌러 변경을 시작합니다.  
- *`앱 종료` 버튼을 누르면 에이전트 프로그램이 종료됩니다.*   

사용자 임시 비밀번호 변경을 위한 사용자 인증(MFA)을 수행합니다.  

![pca user login temporary password - mfa email](/PrC_manuals/img/agent_user_login_mfa_email.png)   

사용자 인증(MFA)은 계정에 등록된 이메일로 OTP 코드가 전달됩니다. 

![pca user login temporary password - mfa email](/PrC_manuals/img/agent_user_login_mfa_email_otp_code.png)   

이메일로 전달된 OTP 코드를 앱 화면에 입력하여 인증합니다.   
정상적으로 사용자 인증(MFA)이 완료되면 비밀번호를 변경하는 화면으로 이동합니다.  

![pca user login change temporary password](/PrC_manuals/img/agent_user_login_change_temporary_password.png)   
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

![pca user login complete changing temporary password](/PrC_manuals/img/agent_user_login_complete_changing_temporary_password.png)  

<br>  

> [!NOTE]  
> 비밀번호 변경이 완료되면 변경된 비밀번호로 다시 로그인을 수행합니다.  

<br> 

[3. PCA 접속 로그인 정보 입력](#3-pca-접속-로그인-정보-입력) 과정을 다시 수행합니다.  

<br> 

<!-- TOC --><a name="6-pca-로그인-완료"></a>
## 6. PCA 로그인 완료   

로그인이 정상적으로 완료되면 다음과 같은 화면으로 이동합니다.   
![pca login complete](/PrC_manuals/img/agent_login_complete.png)   

<br>


*** 

<br>

> 접속 과정에서 문제가 발생할 경우 관리자에게 문의하세요.
