# Gitflow

1. Inicialize um repositório Git:

    git init

2. Instale o GitFlow (se ainda não estiver instalado):

    brew install git-flow

3. Inicialize o GitFlow no repositório:


    git flow init

4. Troque para a branch develop:


    git checkout develop

5. Crie uma nova feature:


    git flow feature start nome-da-feature

6. Adicione a pasta ao controle de versão do Git:


    git add .

7. Confirme suas alterações:


    git commit -m "Adicionando a pasta à feature"

8. Conclua a feature:


    git flow feature finish nome-da-feature

9. Envie suas alterações para o repositório remoto:


    git push origin develop
