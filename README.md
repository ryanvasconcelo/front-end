# front-end
# GIT
## versionamento

 - historico
 - controle de versionamento
 - quem alterou
 - o que foi alterado
 - quando alterou
 - todos os arquivos do projeto
 - aprimoramento contínuo

## Release
versao mais estável do projeto (versao de seguranca)

## Commits
informar a alteracao apos testar o codigo alterado e subir no git
- apos testado o codigo
- git add *
- git commit -m "mensagem do commit"
- git status
- git push (envia alteracoes pro repositorio git)
- git pull (puxa o codigo atualizado do repositorio pra maquina)

## Markdown
linguagem muito usada pra escrever documentacao de codigo, entendivel pelo git e traduzivel para html quando renderizada

## gitflow
fluxo do git

### branchs
sao ramificacoes do codigo/versoes de codigos que funcionam em simultaneo
- ex:
- branch - master (principal, a que vai pra producao, quando é publicado)
- branch - alguma feature especifica que apos finalizada ira ser commitada para a branch principal ou uma branch de ambiente de teste de codigo quando atingir o DOD: definition of done (criterios de aceite, quando o codigo atendeu as demandas exigidas pelo cliente)

- git checkout -b NomeDaBranch - cria uma nova branch copiando as coisas da master pra nova branch

- EM HIPOTESE alguma se deve commitar um codigo que esta quebrando, mesmo que outro problema tenha sido resolvido

- git fetch --all verifica se nao existe uma versao mais recente na branch master no repositorio, importante fazer isso antes de pushar o codigo pra branch principal