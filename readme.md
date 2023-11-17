```mermaid
flowchart TD
Pay[간편 결제]
Password[비밀번호 입력]
Check{유효한가}
Success[결제 완료]
Error[에러]
Pay-->Password-->Check
Check-->|yes|Success
Check-->|no|Error

```