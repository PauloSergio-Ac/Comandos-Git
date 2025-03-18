Aqui estão alguns dos comandos básicos e úteis do Git:

1. Configuração inicial
    Configurar nome e email (configuração global):
    
    bash
    Copiar
    git config --global user.name "Seu Nome"
    git config --global user.email "seuemail@dominio.com"
2. Criação e inicialização de repositórios
    Inicializar um novo repositório Git:
    
    bash
    Copiar
    git init
    Clonar um repositório existente:
    
    bash
    Copiar
    git clone <url_do_repositorio>
3. Verificação do status
    Verificar o status do repositório:
    
    bash
    Copiar
    git status
4. Trabalhando com arquivos
    Adicionar arquivos ao staging (preparar para commit):
    
    bash
    Copiar
    git add <nome_do_arquivo>
    git add .  # Adiciona todos os arquivos modificados
    Remover arquivos do repositório:
    
    bash
    Copiar
    git rm <nome_do_arquivo>
    Desfazer alterações em arquivos:
    
    Descartar alterações locais em um arquivo específico:
    
    bash
    Copiar
    git checkout -- <nome_do_arquivo>
5. Commits
    Fazer um commit (salvar as alterações):
    
    bash
    Copiar
    git commit -m "Mensagem do commit"
    Ver o histórico de commits:
    
    bash
    Copiar
    git log
6. Branches
    Criar uma nova branch:
    
    bash
    Copiar
    git branch <nome_da_branch>
    Trocar de branch:
    
    bash
    Copiar
    git checkout <nome_da_branch>
    Criar e trocar de branch em um único comando:
    
    bash
    Copiar
    git checkout -b <nome_da_branch>
    Excluir uma branch:
    
    bash
    Copiar
    git branch -d <nome_da_branch>
7. Merge (mesclar branches)
    Mesclar uma branch na branch atual:
    
    bash
    Copiar
    git merge <nome_da_branch>
8. Repositórios remotos
    Adicionar um repositório remoto:
    
    bash
    Copiar
    git remote add origin <url_do_repositorio>
    Verificar os remotos configurados:
    
    bash
    Copiar
    git remote -v
    Enviar alterações para o repositório remoto:
    
    bash
    Copiar
    git push origin <nome_da_branch>
    Baixar as alterações do repositório remoto:

    bash
    Copiar
    git pull origin <nome_da_branch>
    Fazer fetch (baixar as alterações sem mesclar):
    
    bash
    Copiar
    git fetch
9. Revertendo alterações
    Reverter um commit (cria um novo commit que desfaz as alterações):
    
    bash
    Copiar
    git revert <id_do_commit>
    Resetar o repositório para um estado anterior (cuidado, pode alterar o histórico!):
    
    bash
    Copiar
    git reset --hard <id_do_commit>
10. Outros comandos úteis
    Ver as diferenças entre arquivos (before commit):
    
    bash
    Copiar
    git diff
    Criar um stash (salvar alterações temporariamente):
    
    bash
    Copiar
    git stash
    Listar todos os stashes:
    
    bash
    Copiar
    git stash list

