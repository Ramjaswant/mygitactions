# Mygitactions
This is jaswant's Experiment and testing repo. 

## Requirements
### Python Version
```3.9.x+```
### Ansible Version
```3.0.x+```

### Requirements

#### Execution Environment
TODO: List EE used and the python packages and collections in the EE that are required by this automation.
| EE Name | Collections List | Roles List | Py packages |
| --- | --- | --- | --- |
| | | |

#### Automation Runtime
Roles and Collections that are not bundled in the EE Above should be list in the appropriate requirements file.
- [Collection/Reuirements.yml]
- [Roles/Requirements.yml]

#### GitHub Actions docker Image
TODO: List docker image used and the python packages and collections in the image that are reuired by the github actions
| Image Name | Collections List | Roles List | Py packages |
| --- | --- | --- | --- |
| | | |

#### CICD Runtime Packages And Collections
Python and Ansible collections required by the github actions taht are not already bundled in the github actions docker image.
- [.github/cicd-pip3-requirements.txt]
- [.github/cicd-ansible-requirements.yml]

## Automation Runtime Variables
### Extra Vars/Survey Vars
| Variable | Description |
| --- | --- |
| | | |

### Defaults/Main.yml
| Variable | Description |
| | | |

### Vars/Main.yml
| Variable | Description |
| | | |

## Credentials
Credentials in Ansible Controller used by this automation
| Credential Name | Credential Type | Environment |
| --- | --- | --- |
|Cred1 | Machine | Prod and NonProd |


# Know Issues
- The Necessary Cred1 is not configured in prod Ansible Controller; if you can run it, the bar will not launch after the foo

# Author
{{ Playbook_User}}

# Change Log
- v0.0.1 Repo Established.
