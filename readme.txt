Relatório – Calculadora Simples (DOM)
1. Estrutura HTML
•	Criei um arquivo chamado index.html.
•	No HTML coloquei:
o	Um título (“Calculadora”).
o	Um campo de texto (input) para ser o visor.
o	Botões para os números (0 a 9) e operações (+ - * /).
o	O botão C (limpar) e o botão = (resultado).
•	Também adicionei a referência para o arquivo de estilo (style.css) e para o arquivo de script (script.js).

2. Estilo (CSS)
•	Criei um arquivo chamado style.css.
•	Nele defini:
o	Fonte Arial para a página.
o	O fundo da página em cinza claro.
o	O visor (input) alinhado à direita, com tamanho fixo.
o	Os botões com largura e altura iguais, para ficarem organizados.
o	Um efeito simples de hover nos botões (mudam de cor quando o mouse passa por cima).

3. Funções em JavaScript
•	Criei um arquivo chamado script.js.
•	Nele fiz três funções principais:
o	adicionar(valor) → adiciona o número ou operador no visor.
o	limpar() → apaga o que está no visor.
o	calcular() → resolve a conta com eval() e mostra o resultado.

4. Eventos
•	Usei o atributo onclick em cada botão para chamar as funções do JavaScript.
o	Exemplo: o botão 7 chama adicionar('7').
o	O botão C chama limpar().
o	O botão = chama calcular().

5. Funcionamento
1.	Quando o usuário clica nos números, eles aparecem no visor.
2.	Pode usar os operadores (+, -, *, /) para montar a expressão.
3.	Ao clicar em =, a calculadora faz o cálculo e mostra o resultado.
4.	Se clicar em C, o visor fica vazio novamente.

6. Conclusão
A calculadora funciona corretamente para operações básicas (soma, subtração, multiplicação e divisão).
A atividade ajudou a praticar:
•	Estrutura de página com HTML;
•	Estilização simples com CSS;
•	Manipulação do DOM com JavaScript.

