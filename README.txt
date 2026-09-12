HOSPITAL WORKFLOW SYSTEM v5
============================

LOGIN FIX
The X-Ray and ECG department login accounts have been corrected.

X-Ray Department
Username: xray
Password: xray123

ECG Department
Username: ecg
Password: ecg123

OTHER LOGINS
Admin: admin / admin123
Doctor: dr.anil / doctor123
Doctor: dr.meera / doctor123
Pharmacy: pharmacy / pharmacy123
Lab: lab / lab123
Reception: reception / reception123

Login now trims accidental spaces and treats the username as case-insensitive.

X-RAY / ECG WORKFLOW
Doctor -> Open assigned patient -> Send X-Ray/ECG Request
-> Department receives request -> Upload result image
-> Request Completed -> Doctor views result image.

IMPORTANT
This is a browser-only prototype using localStorage. Do not use it with real patient data or clinical images. Production deployment requires secure backend/database and file storage, authentication, authorization, encryption, audit logging, backups, and appropriate healthcare security/compliance controls.
