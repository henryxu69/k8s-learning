# General K8S Notes
### [bash auto-completion](https://kubernetes.io/zh/docs/tasks/tools/included/optional-kubectl-configs-bash-linux/)

`sudo -i apt-get install bash-completion`

`kubectl completion bash | sudo tee /etc/bash_completion.d/kubectl > /dev/null`

`echo 'alias k=kubectl' >>~/.bashrc`

### alias

`alias k=kubectl`
`complete -F __start_kubectl k`