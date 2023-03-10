# *Repositorio do desafio de projeto da DIO git/github*

desafio de projeto sobre git/github para o aprimoramento do dev

# linguagem a ser usada no git/github
markdown ou HTML aqui vai um link para entender melhor como esses codigos devem ser usados

https://www.markdownguide.org/cheat-shee/

http://cursos.leg.ufpr.br/prr/capMarkdown.html

# Anotações para facil entendimento no transporte de um documento do git hub para o git e vice versa

o que digitar         | para o que digitar
----------------------|-------------------
`git status`          | git visualizar novo docs
`git clone`           | git clona o docs que estava no github
`git add .`           | git entende que é permitido aceitar novo docs
`git commit -m ""`       | para por alguma mensagem
`git push origim main`| para mandar ao github docs já editado


 
Após copiar o link do commit inicial abrimos o git bash e digitamos 
**git clone** (+link copiado). 

exemplo do que pode aparecer

($ git clone https://github.com/samtplant/desafio-github-1-repositorio.git
Cloning into 'desafio-github-1-repositorio'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.)

Já com o docs editado em nossa maquina falta passar ele para o github
para isso digita-se **git status**(+ o nome do documento que vc editou).

o nome do docs ira aparecer 
:x: vermelho para mudalo e deixa-lo
:heavy_check_mark: verde basta digititar **git add .**  e digitar **git status**. 

Agora digitando **git commit -m "" entre aspas vai a mesagem é referente sobre oque vc editou a pagina clica em enter

digita **git status** e após **git push otigin main** que será adicionado na nuvem 