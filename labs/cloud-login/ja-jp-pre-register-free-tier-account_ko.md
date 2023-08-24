# 필수 조건

## 시작

시작하기 전에 Oracle Cloud 계정이 필요합니다. 이 5분 분량의 실습에서는 Oracle Cloud Free Tier 계정 획득 및 로그인 지침을 제공합니다.

### 기존 클라우드 계정

이미 Oracle Cloud 계정이 있는 경우 **작업 2**로 건너뛰고 클라우드 테넌트에 사인인합니다.

### 필요한 사항

*   적합한 전자메일
*   SMS 텍스트 인증을 수신하는 기능(등록된 메일이 없는 경우에만)

## 작업 1: 무료 체험판 계정 생성

클라우드 계정이 이미 있는 경우 **Task 2**로 이동합니다.

1.  웹 브라우저를 열어 [oracle.com/cloud/free](https://signup.cloud.oracle.com)에서 Oracle Cloud 계정 등록 양식에 액세스하십시오.
    
2.  등록 페이지가 나타납니다. ![OCI](./images/ja-jp-cloud-infrastructure.png " ")
    
3.  다음 정보를 입력하여 Oracle Cloud Free Tier 계정을 생성합니다.
    
    *   **국가**
    *   **전체 이름** 및 **전자 메일 주소**
    *   **hCaptcha**를 사용하여 ID 확인
4.  적합한 전자메일 주소를 입력한 후 **전자메일 검증** 단추를 선택합니다. 버튼을 선택하면 다음 화면이 나타납니다. 버튼을 선택하면 다음 화면이 나타납니다. ![전자메일 확인](./images/ja-jp-verify-email.png " ")
    
5.  이메일을 확인하세요. 계정 확인 이메일이 받은 편지함에 나타납니다. 이메일은 다음과 같습니다. ![확인 전자메일](./images/verification-mail.png " ")
    
6.  **전자 메일 확인**을 누릅니다.
    
7.  다음 정보를 입력하여 Oracle Cloud Free Tier 계정 만들기 \* **비밀번호** \* **회사 이름** \* **클라우드 계정 이름** 입력에 따라 자동으로 생성되지만 새 값을 입력하여 변경할 수 있습니다. 입력한 내용을 기억하십시오. 나중에 사인인하려면 이 이름이 필요합니다. \* 등록한 후에는 **홈 영역** 홈 영역을 변경할 수 없습니다. \* **계속**을 누르십시오. ![계정 정보](./images/ja-jp-account-info.png " ")
    
8.  주소 정보를 입력하십시오. **Continue**를 누릅니다. ![주소](./images/ja-jp-free-tier-address.png " ")
    
9.  국가를 선택하고 휴대폰 번호를 입력하여 확인합니다. **코드 텍스트** 단추를 누릅니다.
    
    ![휴대폰 번호](./images/ja-jp-free-tier-address-2.png " ")
    
10.  코드를 받으면 코드를 입력하고 **코드 확인**을 누릅니다. ![확인 코드](./images/ja-jp-free-tier-address-4.png " ")
    
11.  **지불 검증 방법 추가** 버튼을 누릅니다. ![지불](./images/ja-jp-free-tier-payment-1.png " ")
    
12.  確認方法を選択します。この場合は **Credit Card**ボタンをクリックします。お客様の情報とお支払い内容を入力します。_注：これは無料のクレジットプロモーションアカウントです。アカウントのアップグレードを選択しない限り、課金されることはありません。_ ![신용 카드](./images/ja-jp-free-tier-payment-2.png " ")
    
13.  지급을 확인한 후 체크박스를 눌러 동의를 검토하고 이에 동의합니다. **Start Free Trial** 버튼을 누릅니다. ![동의](./images/ja-jp-free-tier-agreement.png " ")
    
14.  계정이 지금 프로비전되고 있으며 몇 초 후에 사용할 수 있습니다. 준비가 되면 자동으로 사인인 페이지로 이동합니다. 또한 두 개의 이메일을 받게 됩니다. 하나는 먼저 프로비저닝이 진행 중임을 알리는 것입니다. 다른 하나는 프로비저닝이 완료되었음을 알리는 전자 메일입니다. 다음은 최종 통지의 복사본입니다. ![계정 프로비저닝됨](./images/account-provisioned.png " ")
    

## 태스크 2: 계정에 사인인

Oracle Cloud에서 사인아웃한 경우 아래 단계를 사용하여 다시 사인인하십시오.

1.  [cloud.oracle.com](https://cloud.oracle.com)으로 이동하여 클라우드 계정 이름을 입력하고 **다음**을 누릅니다. 이전 섹션에서 계정을 생성할 때 선택한 이름입니다. 전자메일 주소가 아닙니다. 이름을 잊어버린 경우 확인 이메일을 참조하십시오.
    
    ![클라우드 계정 이름](./images/ja-jp-cloud-oracle.png " ")
    
2.  _Oracle Cloud Infrastructure Direct Sign-In_ 뒤의 화살표를 확장하여 로그인 입력 필드를 표시합니다.
    
    ![Oracle Cloud Infrastructure Direct Sign-In 확장](./images/cloud-login-tenant.png " ")
    
3.  클라우드 계정 인증서를 입력하고 **사인인**을 누릅니다. 사용자 이름은 전자메일 주소입니다. 계정에 등록할 때 선택한 비밀번호입니다.
    
    ![사인인](./images/oci-signin.png " ")
    
4.  이제 Oracle Cloud에 사인인되었습니다!
    
    ![OCI 콘솔 홈 페이지](https://oracle-livelabs.github.io/common/images/console/ja-jp-home-page.png " ")
    

**다음 랩**으로 이동합니다.

## 확인

*   **작성자/날짜/시간** - Kay Malcolm, 데이터베이스 제품 관리, 2020년 3월
*   **게시자** - John Peach, Kamryn Vinson, Rene Fontcha, Arabella Yao
*   **최종 업데이트** - Arabella Yao, 2022년 12월