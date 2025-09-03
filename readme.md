# Laboratório DOM

## Relatório – Calculadora Simples 
**1. Estrutura HTML**
-	Criei um arquivo chamado index.html.
-	No HTML coloquei:Um título (“Calculadora”).
-	Um campo de texto (input) para ser o visor.
-	Botões para os números (0 a 9) e operações (+ - * /).
-	O botão C (limpar) e o botão = (resultado).
-	Também adicionei a referência para o arquivo de estilo (style.css) e para o arquivo de script (script.js).

**2. Estilo (CSS)**
-	Criei um arquivo chamado style.css.
-	Nele defini:
-	Fonte Arial para a página.
-	O fundo da página em cinza claro.
-	O visor (input) alinhado à direita, com tamanho fixo.
-	Os botões com largura e altura iguais, para ficarem organizados.
-	Um efeito simples de hover nos botões (mudam de cor quando o mouse passa por cima).

**3. Funções em JavaScript**
-	Criei um arquivo chamado script.js.
-	Nele fiz três funções principais:
-	adicionar(valor) → adiciona o número ou operador no visor.
-	limpar() → apaga o que está no visor.
-	calcular() → resolve a conta com eval() e mostra o resultado.

**4. Eventos**
-	Usei o atributo onclick em cada botão para chamar as funções do JavaScript.
-	Exemplo: o botão 7 chama adicionar('7').
-	O botão C chama limpar().
-	O botão = chama calcular().

**5. Funcionamento**
-	Quando o usuário clica nos números, eles aparecem no visor.
-	Pode usar os operadores (+, -, *, /) para montar a expressão.
-	Ao clicar em =, a calculadora faz o cálculo e mostra o resultado.
-	Se clicar em C, o visor fica vazio novamente.

**6. Conclusão**
-	A calculadora funciona corretamente para operações básicas (soma, subtração, multiplicação e divisão).
-	A atividade ajudou a praticar:
-	Estrutura de página com HTML;
-	Estilização simples com CSS;-
-	Manipulação do DOM com JavaScript.
