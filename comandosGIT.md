## ============================================//============================================ ##

git init                                                - inicia um novo repositorio git local vazio

## ============================================//============================================ ##

git remote add origin link do repositorio no github     -  linka o repositorio local criado anteriormente com o repositorio remoto do github. Origin (nome dado ao repositorio)

## ============================================//============================================ ##

git add nomearquivo.extensao                            - manda o arquivo especificado para o staging do repositorio

## ============================================//============================================ ##

git add .                                               - manda todos os arquivos disposniveis para serem enviados para o staging

## ============================================//============================================ ##

git status                                              - mostra os status atual do repositorio, por exemplo, se ha arquivos a serem commitados

## ============================================//============================================ ##

git commit -m "mensagem do commit"                      - commita os arquivos presentes no staging no repositorio

## ============================================//============================================ ##

git branch -M nome                                      - renomeia a branch (usualmente se altera o nome da branch "master" para "main")

## ============================================//============================================ ##

git push -u origin main                                 - adiciona os arquivos do repositorio local no repositorio do github (primeira vez)

## ============================================//============================================ ##

git push origin main                                    - adiciona/atualiza os arquivos no repositorio do github (a partir da segunda vez)

## ============================================//============================================ ##

git checkout -b nomedabranch                            - cria uma nova branch para novas alteracoes (criar antes de realizar as modificacoes). Pode ser utilizado para alternar entre as branches

## ============================================//============================================ ##

git merge nome_branch                                   - junta as branches em uma so. Dar checkout na branch que deseja adicionar as alteracoes.

## ============================================//============================================ ##

git clone link.git                                      - clona o projeto presente no github para a maquina em que esta

## ============================================//============================================ ##

git pull                                                - puxar as alteracoes realizadas no repositorio do github por outra maquina

## ============================================//============================================ ##
