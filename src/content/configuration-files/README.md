# Configuration Files

<br>

## Concurrent Program Entities
| Code   | Entity Name                      | Entity Code      | Configuration File   | Table Name |
| :-:     | :--------                       | :----            | :----   | :----   |
| 1    | Concurrent Programs                | PROGRAM          | $FND_TOP/patch/115/import/afcpprog.lct | FND_CONCURRENT_PROGRAMS  |
| 2    | Executables                        | EXECUTABLE       | $FND_TOP/patch/115/import/afcpprog.lct | FND_EXECUTABLES  |
| 3    | Request Groups                     | REQUEST_GROUP    | $FND_TOP/patch/115/import/afcpreqg.lct | FND_REQUEST_GROUPS  |
| 4    | Request Sets                       | REQUEST_SET      | $FND_TOP/patch/115/import/afcpreqs.lct | FND_REQUEST_SETS  |
| 5    | Request Set Links                  | REQUEST_SET_LINK | $FND_TOP/patch/115/import/afcpreqs.lct | FND_REQUEST_SET_LINKS  |

<br>

## Application Object Library (AOL) Entities

### Lookups
| Code   | Entity Name      | Entity Code      | Configuration File                    | Table Name |
| :-:    | :--------        | :----            | :----                                 | :----   |
| 1      | Lookups          | LOOKUP_TYPE      | $FND_TOP/patch/115/import/aflvmlu.lct | FND_LOOKUP_TYPES  |
| 2      | Lookup Values    | LOOKUP_VALUE     | $FND_TOP/patch/115/import/aflvmlu.lct | FND_LOOKUP_VALUES  |

<br>

### Profile Options
| Code   | Entity Name              | Entity Code          | Configuration File                     | Table Name |
| :-:    | :--------                | :----                | :----                                  | :----   |
| 1      | Profile Options          | PROFILE_OPTION       | $FND_TOP/patch/115/import/afscprof.lct | FND_PROFILE_OPTIONS  |
| 2      | Profile Option Values    | PROFILE_OPTION_VALUE | $FND_TOP/patch/115/import/afscprof.lct | FND_PROFILE_OPTION_VALUES  |

<br>

### Flexfields
| Code   | Entity Name               | Entity Code            | Configuration File                     | Table Name |
| :-:    | :--------                 | :----                  | :----                                  | :----   |
| 1      | Key Flexfield Structures  | KEY_FLEXFIELD          | $FND_TOP/patch/115/import/afffload.lct | FND_ID_FLEX_STRUCTURES  |
| 2      | Descriptive Flexfields    | DESCRIPTIVE_FLEXFIELD  | $FND_TOP/patch/115/import/afffload.lct | FND_DESCRIPTIVE_FLEXS  |
| 3      | Value Sets                | VALUE_SET              | $FND_TOP/patch/115/import/afffload.lct | FND_FLEX_VALUE_SETS  |

<br>

### Messages Dictionary
| Code   | Entity Name           | Entity Code   | Configuration File                     | Table Name |
| :-:    | :--------             | :----         | :----                                  | :----   |
| 1      | Messages Dictionary   | MESSAGE       | $FND_TOP/patch/115/import/afmdmsg.lct    | FND_NEW_MESSAGES  |

<br>

### Attachments
| Code   | Entity Name             | Entity Code   | Configuration File                     | Table Name |
| :-:    | :--------               | :----         | :----                                  | :----   |
| 1      | Attachments Definitions | ATTACHMENT    | $FND_TOP/patch/115/import/afattach.lct | FND_DOCUMENTS  |
| 2      | Attachments Categories  | ATTACHMENT    | $FND_TOP/patch/115/import/afattach.lct | FND_ATT_CATEGORY  |
| 3      | Media Items             | ATTACHMENT    | $FND_TOP/patch/115/import/afattach.lct | FND_ATT_MEDIA  |

### Attachments (To Review)
| Code   | Entity Name                | Entity Code                 | Configuration File                     | Table Name |
| :-:    | :--------                  | :----                       | :----                                  | :----   |
| 1      | Attachment Definitions     | FND_ATTACHMENT_FUNCTIONS    | $FND_TOP/patch/115/import/afattach.lct | FND_ATTACHMENT_FUNCTIONS|
| 2      | Attachment Block Entities  | FND_ATTACHMENT_BLOCKS       | $FND_TOP/patch/115/import/afattach.lct | FND_ATTACHMENT_BLOCKS  |
| 3      | Attachment Block → Entities| FND_ATTACHMENT_BLK_ENTITIES | $FND_TOP/patch/115/import/afattach.lct | FND_ATTACHMENT_BLK_ENTITIES |
| 4      | Document Categories (Usage)| FND_DOCUMENT_CATEGORIES     | $FND_TOP/patch/115/import/afattach.lct | FND_DOCUMENT_CATEGORIES |
| 5      | Document Data Types        | FND_DOCUMENT_DATATYPES      | $FND_TOP/patch/115/import/afattach.lct | FND_DOCUMENT_DATATYPES |
| 6      | Media Items                | MEDIA                       | $FND_TOP/patch/115/import/afattach.lct | FND_ATT_MEDIA |
<br>


## Security & Access Control Entities
| Code   | Entity Name     | Entity Code    | Configuration File                     | Table Name |
| :-:     | :--------      | :----          | :----                                  | :----   |
| 1    | Users             | USER           | $FND_TOP/patch/115/import/afscusr.lct  | FND_USER  |
| 2    | Responsibilities  | RESPONSIBILITY | $FND_TOP/patch/115/import/afscursp.lct | FND_RESPONSIBILITY  |
| 3    | Menus             | MENU           | $FND_TOP/patch/115/import/afsload.lct  | FND_MENUS  |
| 4    | Menu Entries      | MENU_ENTRY     | $FND_TOP/patch/115/import/afsload.lct  | FND_MENU_ENTRIES  |
| 5    | Functions         | FUNCTION       | $FND_TOP/patch/115/import/afscursp.lct | FND_FORM_FUNCTIONS  |
| 6    | Forms             | FORM           | $FND_TOP/patch/115/import/afsecurr.lct | FND_FORM  |
| 7    | Entry             | ENTRY          | $FND_TOP/patch/115/import/afsecurr.lct | FND_FORM_FUNCTIONS  |

<br>

## Workflow & Approval Management Entities

### Workflow
| Code   | Entity Name  | Entity Code   | Configuration File               | Table Name |
| :-:    | :--------    | :----         | :----                            | :----   |
| 1      | Workflow     | WFLOAD        | $FND_TOP/patch/115/import/wf.lct | WF_ITEMS  |

<br>

### Approvals Management Engine (AME)

#### Transaction Types
| Code | Entity Name       | Entity Code          | Configuration File                | Table Name |
| :-:  | :--------         | :----                | :----                             | :----   |
| 1    | Transaction Types | AME_TRANSACTION_TYPE | $AME_TOP/patch/115/import/ame.lct | AME_TRANSACTION_TYPES  |

#### Attributes
| Code | Entity Name           | Entity Code         | Configuration File                | Table Name |
| :-:  | :--------             | :----               | :----                             | :----   |
| 1    | Attributes            | AME_ATTRIBUTE       | $AME_TOP/patch/115/import/ame.lct | AME_ATTRIBUTES  |
| 2    | Attribute Definitions | AME_ATTRIBUTE_DEF   | $AME_TOP/patch/115/import/ame.lct | AME_ATTRIBUTE_DEFINITIONS  |
| 3    | Attribute Usages      | AME_ATTRIBUTE_USAGE | $AME_TOP/patch/115/import/ame.lct | AME_ATTRIBUTE_USAGES  |

#### Conditions
| Code | Entity Name  | Entity Code   | Configuration File                | Table Name |
| :-:  | :--------    | :----         | :----                             | :----   |
| 1    | Conditions   | AME_CONDITION | $AME_TOP/patch/115/import/ame.lct | AME_CONDITIONS  |

#### Approver Groups
| Code | Entity Name                  | Entity Code               | Configuration File                | Table Name |
| :-:  | :--------                    | :----                     | :----                             | :----   |
| 1    | Approver Groups              | AME_APPROVER_GROUP        | $AME_TOP/patch/115/import/ame.lct | AME_APPROVER_GROUPS  |
| 2    | Definitions   | AME_APPROVER_GROUP_DEF    | $AME_TOP/patch/115/import/ame.lct | AME_APPROVER_GROUP_DEFINITIONS  |
| 3    | Configuration | AME_APPROVAL_GROUP_CONFIG | $AME_TOP/patch/115/import/ame.lct | AME_APPROVAL_GROUP_CONFIGS  |

#### Rules
| Code | Entity Name       | Entity Code     | Configuration File                | Table Name |
| :-:  | :--------         | :----           | :----                             | :----   |
| 1    | Rule Definitions  | AME_RULE_DEF    | $AME_TOP/patch/115/import/ame.lct | AME_RULE_DEFINITIONS  |
| 2    | Rule Usages       | AME_RULE_USAGE  | $AME_TOP/patch/115/import/ame.lct | AME_RULE_USAGES  |

<br>


## Reporting & BI Publisher (XDO) Entities
| Code | Entity Name      | Entity Code       | Configuration File                    | Table Name |
| :-:  | :--------        | :----             | :----                                 | :----   |
| 1    | Data Definitions | XDO_DS_DEFINITION | $XDO_TOP/patch/115/import/xdodict.lct | XDO_DS_DEFINITIONS  |
| 2    | XML Templates    | XDO_TEMPLATE      | $XDO_TOP/patch/115/import/xdotmpl.lct | XDO_TEMPLATES  |
| 3    | RTF Templates    | XDO_RTF_TEMPLATE  | $XDO_TOP/patch/115/import/xdotmpl.lct | XDO_RTF_TEMPLATES  |

<br>

## SOA, Integrations & Web ADI Entities

### Integrated SOA Gateway (ISG)
| Code | Entity Name   | Entity Code         | Configuration File                | Table Name |
| :-:  | :--------     | :----               | :----                             | :----   |
| 1    | SOA Gateway   | FND_SOA_INTEGRATION | $FND_TOP/patch/115/import/soa.lct | FND_SOA_INTEGRATIONS  |

<br>

### Application Desktop Integrator (Web ADI)
| Code | Entity Name   | Entity Code     | Configuration File                          | Table Name |
| :-:  | :--------     | :----           | :----                                       | :----   |
| 1    | Web ADI       | BNE_INTEGRATOR  | $BNE_TOP/patch/115/import/bneintegrator.lct | BNE_INTEGRATORS  |

<br>


## Alerts Entity
| Code | Entity Name | Entity Code | Configuration File                | Table Name |
| :-:  | :--------   | :----       | :----                             | :----      |
| 1    | Alerts      | ALERT       | $ALR_TOP/patch/115/import/alr.lct | ALR_ALERTS  |

<br>

## Forms Personalization Entities
| Code | Entity Name            | Entity Code           | Configuration File                     | Table Name |
| :-:  | :--------              | :----                 | :----                                  | :----      |
| 1    | Forms Personalizations | FORMS_PERSONALIZATION | $FND_TOP/patch/115/import/affrmcus.lct | FND_FORM_CUSTOM_RULES  |
