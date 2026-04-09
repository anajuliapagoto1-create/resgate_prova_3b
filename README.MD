Ana Júlia Cavalcante Pagoto 3B

1. O que estava dando errado (Debug)
Abri o console do navegador e o VS Code e encontrei os seguintes erros:

Falta de fechamento: O código tinha { e ( abertos, mas não tinham os } e ) no final para fechar a função e os .then. Isso impedia o script de rodar.

Erro no link da API: A URL estava como /post (singular) e o correto era /posts (plural). Por causa disso, a busca não encontrava nada.

Vírgulas na tela: No HTML, a lista estava aparecendo com vírgulas entre os itens porque faltava o comando .join('').

2. O que eu fiz para arrumar
Consertei o código: Fechei todos os parênteses e chaves da função buscarDados.

Corrigi a API: Ajustei o endereço do fetch para o link certo.

Tradução dos dados: Como a API mandava frases estranhas em latim, criei uma lista (array) em português dentro do código para os dados ficarem legíveis e com cara de sistema real.

Limpeza da lista: Usei o .join('') para tirar aquelas vírgulas que ficavam entre os tópicos.

3. Melhorias que adicionei (PLUS)
Para o projeto não ficar simples demais, dei um tapa no visual:

Visual moderno: Coloquei um CSS para deixar o botão mais bonito, com efeito de cor quando passa o mouse.

Organização: Coloquei os resultados dentro de "cards" brancos com sombra, para não ficar só um texto solto na tela.

Aviso de carregando: Agora, enquanto a gente clica e o dado não chega, aparece um aviso de "Carregando..." para o usuário não achar que o site travou.

4. Git e Versionamento
Fiz todo o processo pelo terminal:

Criei minha branch Aluno_Anajulia_Pagoto.

Subi as alterações com git add e fiz o git commit com meu nome.

Usei o git push --set-upstream para enviar tudo direto para o meu GitHub.
