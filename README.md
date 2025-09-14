
# pretalab-ciclo14-git-github
Atividade prática - Ciclo de vida

>>> Resumo Básico de Git e GitHub

* Configuração inicial:

git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"



* Comandos iniciais:

- Iniciar repositório: 
git init
- Ver status dos arquivos:
git status
- Adicionar arquivos para commit:
git add nome_do_arquivo (arquivo específico)
git add .  (todos os arquivos)
- Fazer commit:
git commit -m "Mensagem do commit"
- Ver histórico de commits:
git log



* Trabalhando com Repositórios Remotos:

- Conectar com repositório remoto:
git remote add origin https://github.com/usuario/repositorio.git
- Enviar commits para o GitHub:
git push origin main
- Baixar alterações do GitHub:
git pull origin main
- Clonar repositório existente:
git clone https://github.com/usuario/repositorio.git


* Fluxo Básico de Trabalho:

1. Modificar arquivos no seu projeto
2. Verificar mudanças: git status
3. Adicionar alterações: git add .
4. Commit: git commit -m "mensagem"
5. Enviar para GitHub: git push origin main

