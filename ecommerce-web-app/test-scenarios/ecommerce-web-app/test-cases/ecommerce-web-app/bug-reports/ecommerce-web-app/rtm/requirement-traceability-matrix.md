# Requirement Traceability Matrix (RTM)

| Requirement ID | Requirement Description                              | Test Scenario ID | Test Case ID | Status | Remarks                  |
| -------------- | ---------------------------------------------------- | ---------------- | ------------ | ------ | ------------------------ |
| RQ_001         | User should be able to log in with valid credentials | TS_LOGIN_001     | TC_LOGIN_001 | Pass   | Working as expected      |
| RQ_002         | System should validate invalid passwords             | TS_LOGIN_001     | TC_LOGIN_002 | Pass   | Error message displayed  |
| RQ_003         | Username is mandatory                                | TS_LOGIN_001     | TC_LOGIN_004 | Pass   | Validation implemented   |
| RQ_004         | Password is mandatory                                | TS_LOGIN_001     | TC_LOGIN_005 | Pass   | Validation implemented   |
| RQ_005         | Account should lock after 5 failed attempts          | TS_LOGIN_003     | TC_LOGIN_008 | Pass   | Security requirement met |
| RQ_006         | Application should prevent SQL Injection             | TS_LOGIN_003     | TC_LOGIN_009 | Pass   | Secure implementation    |
