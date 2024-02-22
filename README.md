# openDID-cli

**입력받은 비밀번호와 .wallet파일과 .did 파일을 Entity담당자에게 전달하고 DIDDoc을 TAS관리자에게 전달하여 iVC가입증명서를 받는다.**

1. 필수 SDK
    - wallet_sdk
    - did_sdk
    - crypto_sdk
2. 동작 방식
    - wallet 생성 (with 비밀번호)
    - wallet에 keyId 별 키쌍 생성
    - DID Doc 생성