# REST Apis

The backend and frontend communicate through REST Apis. On the frontend, we make Ajax requests using jQuery to the following routes:

| URI                             | Returns                                              |
| ------------------------------- | ---------------------------------------------------- |
| /app/getdiseases                | returns information about all diseases in the system |
| /app/getpatients                | returns information about all patients in the system |
| /app/getpatient/:hospitalNumber | returns information about a specific patient         |
| /app/getrooms                   | returns information about the rooms in the system    |
