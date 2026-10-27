# AI Security #1:  Microsoft allows standard users to create Agent Identity Blueprints by default (MC1506733):-

| Problem Statement:- |
| --------- |
| __Users without assigned Entra ID roles can create blueprints and agent identities.__ |

| Recommendation:- |
| --------- |
| Disable by default. |
| This introduces risks around __Identity Ownership__ and __Permissions__ as users are allowed to create Non-Human Identities. |

| BEFORE:- |
| --------- |
| <img src="/Images-Security/1-Entra-ID-Users-Create-Agent-Identity-Blueprint-Default.jpg"> |


| AFTER:- |
| --------- |
| <img src="/Images-Security/2-Entra-ID-Users-Create-Agent-Identity-Blueprint-Disabled.jpg"> |