# BE-Week7-Esercizio3
Security &amp; Programming Best Practices - 3. Advanced Git

### Prove Git sul terminale
  
1. Un membro del team ha creato una repository con link https://github.com/Lucalatt/Es22_02.git inserendo un nuovo progetto JPA e aggiungendo gli altri come collaboratori  
2. Abbiamo clonato la repository su eclipse  
3. Abbiamo creato un branch a testa con il comando 'git branch nomeBranch'  
4. Ci siamo spostati sul nostro branch con il comando 'git checkout nomeBranch'  
5. Ognuno ha creato un nuovo package e al suo interno un file con il comando 'touch file.txt'  
6. Abbiamo poi inserito il file nella Staging Area con il comando 'git add .'  
7. Abbiamo fatto il commit sulla repository locale con il comando 'git commit -m "descrizione commit"'  
8. Abbiamo fatto il merge dei nostri branch al main spostandoci prima nel branch main con 'git checkout main' e poi facendo 'git merge nomeBranch'  
9. Abbiamo inserito tutte le modifiche sul repository con il comando 'git push -u origin nomeBranch'  
10. Attraverso il comando 'git pull' poi abbiamo recuperato nel nostro eclipse il progetto completo con tutti i file inseriti dagli altri del team  
11. Abbiamo inserito il tag con il comando 'git tag -a v1.0.1 -m "Questa è la versione 1.0.1"'  
12. Infine abbiamo controllato gli ultimi commit con il comando 'git log --pretty=oneline -3'  
