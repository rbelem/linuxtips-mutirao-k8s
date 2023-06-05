
# Instalar o Devbox
`curl -fsSL https://get.jetpack.io/devbox | bash`

# Adicionar ao final do `~/.bashrc`
`source <(devbox completion bash)`

# Clonar o projeto
`git clone https://github.com/rbelem/linuxtips-mutirao-k8s.git`

# Entrar no devbox do repositório
`cd linuxtips-mutirao-k8s`

# Ativar o devbox
`devbox shell`

# Adicionar as permissões para rodar o podman(alternativa ao Docker)
`devbox run setup-podmand`

# Pronto!
Agora pode continuar o [# Mutirão Kubernetes](https://github.com/badtuxx/CertifiedContainersExpert/tree/main/DescomplicandoKubernetes/day-1).
