# FNDLOAD Commands Reference

<br>

### Script Example
| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Example     | FNDLOAD apps/password 0 Y DOWNLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt [entity] [parameters] | FNDLOAD apps/password 0 Y UPLOAD $FND_TOP/patch/115/import/config-file.lct data-file.ldt|

<br>

<br>

## Application Object Library (AOL) Entities

<br>

### Concurrent Program Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Concurrent Programs     | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct <Program>.ldt PROGRAM APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" CONCURRENT_PROGRAM_NAME="<PROGRAM_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct <Program>.ldt|
| 2      | Executables             | FNDLOAD apps/$APPS_PASSWORD 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpprog.lct <filename>.ldt EXECUTABLE APPLICATION_SHORT_NAME="<APPSHORT>" EXECUTABLE_NAME="<EXECUTABLE_NAME>" | FNDLOAD apps/$APPS_PASSWORD 0 Y UPLOAD $FND_TOP/patch/115/import/afcpprog.lct <filename>.ldt |
| 3      | Request Groups          | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcpreqg.lct <ReqGroup>.ldt REQUEST_GROUP REQUEST_GROUP_NAME="<GROUP_NAME>" APPLICATION_SHORT_NAME="<APP_SHORT_NAME>" | FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcpreqg.lct <ReqGroup>.ldt |
| 4      | Request Sets            | FNDLOAD apps/<APPS_PASSWORD> 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcprset.lct <ReqSet>.ldt REQ_SET REQUEST_SET_NAME="<SET_NAME>"| FNDLOAD apps/<APPS_PASSWORD> 0 Y UPLOAD $FND_TOP/patch/115/import/afcprset.lct <ReqSet>.ldt|
| 5      | Request Set Links       |  FNDLOAD apps/$APPS_PASSWORD 0 Y DOWNLOAD $FND_TOP/patch/115/import/afcprset.lct <filename>.ldt REQ_SET APPLICATION_SHORT_NAME="<APPSHORT>" REQUEST_SET_NAME="<REQUEST_SET_NAME>" | FNDLOAD apps/$APPS_PASSWORD 0 Y UPLOAD $FND_TOP/patch/115/import/afcprset.lct <filename>.ldt |

<br>

### Lookups

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Lookups                 | FNDLOAD apps/$APPS_PASSWORD 0 Y DOWNLOAD $FND_TOP/patch/115/import/aflvmlu.lct <filename>.ldt FND_LOOKUP_TYPE APPLICATION_SHORT_NAME="<APPSHORT>" LOOKUP_TYPE="<LOOKUP_TYPE>" | FNDLOAD apps/$APPS_PASSWORD 0 Y UPLOAD $FND_TOP/patch/115/import/aflvmlu.lct <filename>.ldt|

<br>

### Profile Options

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 
| 1      | Profile Options         | FNDLOAD apps/$APPS_PASSWORD 0 Y DOWNLOAD $FND_TOP/patch/115/import/afscprof.lct <filename>.ldt PROFILE PROFILE_NAME="<PROFILE_OPTION_NAME>" APPLICATION_SHORT_NAME="<APPSHORT>" | FNDLOAD apps/$APPS_PASSWORD 0 Y UPLOAD $FND_TOP/patch/115/import/afscprof.lct <filename>.ldt |

<br>

### Flexfields

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

### Message Dictionary

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

### Attachments

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 

<br>

## Security & Access Control Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## Workflow & Approval Management Entities

### Workflow

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Approvals Management Engine (AME)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Transaction Types

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Attributes

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Conditions

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Approver Groups

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


#### Rules

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## Reporting & BI Publisher (XDO) Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## SOA, Integrations & Web ADI Entities

### Integrated SOA Gateway (ISG)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Application Desktop Integrator (Web ADI)

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


### Alerts Entity

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 


<br>

## Forms Personalization Entities

| Code   | Entity Name             | Download  | Upload  |  
| :-:    | :--------               | :----     | :----   | 



<br>
