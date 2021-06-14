# README - Atividade6

### Aplicação e exemplos de formatação no arquivo README.md

## Descrição da atividade:
 
![Atividade 6](https://github.com/lincolnvidal/Atividade6/blob/main/Atividade%206.png)

## Passo a passo para desenvolvimento da atividade 6:

1. Digitar o comando: ```git init```
2. Digitar o comando: ```git clone https://github.com/lincolnvidal/Atividade6.git```
3. Adicionar dois arquivos na sequência: arquivo1.js, arquivo2.js
4. Digitar o comando: ```git add arquivo1.js```
5. Digitar o comando: ```git add arquivo2.js```
6. Digitar o comando: ```git commit -m "commit um" para o primeiro commit```
7. Adicionar um arquivo com o nome: arquivo3.js
8. Digitar o comando: ```git add arquivo3.js```
9. Digitar o comando: ```git tag -a 1.0 -m "versão de início" para criar uma tag inicial no repositório```
10. Digitar o comando: ```git commit -m "commit dois" para o segundo commit```
11. Digitar o comando: ```git push```
12. Digitar o comando: ```git branch dev ```
13. Digitar o comando: ```git checkout dev```
14. Digitar o comando: ```git rm arquivo2.js```
15. Adicionar um arquivo com o nome: arquivo4.js
16. Digitar o comando: ```git add arquivo4.js```
17. Digitar o comando: ```git commit -m "commit três" para o terceiro commit```
18. Adicionar uma linha no arquivo "arquivo1.js", por exemplo: ```console.log('This is a line 1')```
19. Digitar o comando ```git add arquivo1.js```
20. Digitar o comando: ```git commit -m "commit quatro" para o quarto commit```
21. Digitar o comando: ```git push --set-upstream origin dev```
22. Digitar o comando: ```git branch temp```
23. Digitar o comando: ```git checkout temp```
24. Adicionar uma linha nos arquivos arquivo3.js e arquivo4.js, por exemplo: ```console.log('This is a line 1')```
25. Digitar o comando: ```git add arquivo3.js```
26. Digitar o comando: ```git add arquivo4.js```
27. Adicionar um arquivo com o nome: arquivo5.js
28. Digitar o comando: ```git commit -m "commit cinco" para o quinto commit```
29. Digitar o comando: ```git push --set-upstream origin temp```
30. Digitar o comando: ```git checkout dev```
31. Digitar o comando: ```git merge temp```
32. Digitar o comando: ```git push --set-upstream origin dev```
33. Digitar o comando: ```git rm arquivo4.js```
34. Alterar a 1° linha do arquivo arquivo1.js
35. Digitar o comando: ```git commit -m "commit seis" para o sexto commit```
36. Digitar o comando: ```git checkout main```
37. Digitar o comando: ```git merge dev```
38. Digitar o comando: ```git tag -a 1.1 -m "versão de entrega" para criar uma tag de entrega no repositório```
39. Digitar o comando: ```git push --set-upstream origin main```
