INTEGRANTES: Matheus Ricoi e Davi Alcantara
TURMA: 10
PROFESSOR: Lucas Rafael Costella Pessutto

Exercício 1 README	


1.	O arquivo Exercicio_1.ipynb contém todo o código utilizado para a extração dos dados da Wikipédia.

2.	A pasta paginas-teste contém os arquivos disponibilizados pelo professor no Moodle, usados como base para os testes.

3.	A pasta Paginas HTML armazena as páginas da Wikipédia coletadas automaticamente, a partir da página inicial “https://pt.wikipedia.org/wiki/Dinheiro”, totalizando até 5000 páginas de verbetes.

4.	A pasta Paginas JSON contém as informações extraídas das infoboxes de todas as páginas que possuíam infobox entre as 5000 coletadas.

5.	A pasta Paginas Teste JSON armazena os arquivos JSON resultantes da execução do código sobre as páginas de teste disponibilizadas pelo professor. Essa execução está localizada ao final do notebook.

Durante o desenvolvimento, foi necessário adicionar a condição Infobox_Sem_Titulo, pois algumas páginas apresentavam um título visível, mas ainda assim eram salvas com nomes vazios. Isso causava a sobrescrição de arquivos. Mesmo com essa verificação, o problema persistiu em alguns casos. Contudo, nos testes com as páginas fornecidas pelo professor, o processo funcionou corretamente.

Também estava ocorrendo erro com títulos muito grandes, logo fizemos o Try Except para apenas continuar quando desse erro

----------------------------------------------------------------------------
Exercício 2 README

1.	Arquivo Exercicio_2.ipynb é o arquivo do código completo

2.	Um arquivo com todas o arquivo JSON
 
3.	A popularidade eh apenas o numero da popularidade

4.	Revisar porque e quais series não estão pegando

----------------------------------------------------------------------------

