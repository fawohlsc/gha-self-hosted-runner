# Deploy GitHub self-hosted runners to Azure

## Folder structure
- **.github/workflows** - _GitHub Actions workflows_
  - vm-deploy.yml - _GitHub Actions workflow for deploying the GitHub self-hosted runner on a VM_
  - container-deploy.yml - _GitHub Actions workflow for deploying the GitHub self-hosted runner as container_
- **docs** - _Documentation_
- **src** - _Source code_
  - vm - _Scripts for deploying GitHub self-hosted runner on a VM_
  - container - _Scripts for deploying GitHub self-hosted runner as container_
  - utils - _Utilities to cleanup GitHub self-hosted runners, trigger the GitHub Actions workflows, ..._

## Host runner on a VM
![alt text](docs/vm.png "Automatically setup GitHub self-hosted runner on a VM") 

## Host runner as Container
![alt text](docs/container.png "Automatically setup GitHub self-hosted runner as containers") 

## Credits
Kudos to [Marcus Young](https://github.com/myoung34/docker-github-actions-runner) for his excellent work around packaging GitHub self-hosted runners as containers.
