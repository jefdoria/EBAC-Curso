# Curso Engenheiro Front-End EBAC
### GIT

## Versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O que alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2


 ## Instalação do GIT
 - https://git.scm.com
 - Linux (sudo apt-get install git)


 ## Criar conta no GITHUB
  - OK


## Clonar Projeto
 git clone https://github.com/jefdoria/EBAC-Curso.git 

## Commit
   Informação de alteração
  - Após testado todo o seu código
  - git add *
  - git commit -m "comentário do objetivo sobre a alteração"
  - git push (emprurrar/ enviar alterações para o repositório)
  - git pull (puxar / puxar alterações do Repositório para a máquina)

## GitFlow
 - Fluxo do GIT

### Branchs
São ramificações / versões paralelas

- main / master (vai para  a produção, quando o projeto é publicado)
- develop
-  DOD Definition Of Done: critérios de aceite 

- versionamento 1.0

git checkout -b dev (criar uma branch nova)
git checkout master (mudar de branch)


### Merge
Mescla de Brachs

git merge main

### Pull Request
Mescla de branchs no repositório
Permite code review
o repositório resolve os conflitos automaticamente

### configura o GitFlow
git flow init
git flow feature start {nome-da-feature}