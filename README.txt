📘 Projeto: Concatenação de Campos (Nick + Earnings)
📋 Descrição

Este projeto em HTML + JavaScript coleta informações digitadas pelo usuário em um formulário e junta (concatena) os valores em uma única mensagem.

O usuário:

Digita seu nick do Fortnite

Digita seus earnings

Clica em Enviar

O sistema mostra um alert com as informações combinadas

Exemplo:

Player123 $5000

🚀 Tecnologias utilizadas

HTML5

JavaScript (Vanilla JS)

📂 Estrutura do projeto
/projeto
 ├─ index.html
 └─ README.md

▶️ Como executar

Abra o arquivo .html no navegador

Preencha os campos do formulário

Clique em Enviar

Veja a mensagem exibida na tela

💻 Como funciona
Elementos principais:

input type="text" → Nick

input type="number" → Earnings

Botão Enviar → chama a função JavaScript

alert() → mostra o resultado

Lógica do JavaScript:
js_nickfort = document.Form.nickfort.value;
js_earnings = document.Form.earnings.value;

js_nickeearnigns = js_nickfort + ' $' + js_earnings;

window.alert('Suas informações: ' + js_nickeearnigns);

Explicação:

.value → pega o texto digitado

+ → concatena strings

' $' → adiciona símbolo do dinheiro

alert() → exibe mensagem pop-up

🧠 Exemplo de uso
Entrada:
Nick: NinjaBR
Earnings: 15000

Saída:
Suas informações: NinjaBR $15000

🔧 Possíveis melhorias

Você pode melhorar o projeto adicionando:

Validação para campos vazios

Formatação monetária (R$ 15.000,00)

Mostrar resultado na página ao invés de alert

CSS para estilizar o formulário

Botão de copiar resultado

Template mais moderno com Flexbox ou Bootstrap

📚 Objetivo educacional

Ideal para treinar:

Manipulação de formulários

Captura de dados com .value

Funções em JavaScript

Concatenação de strings

Eventos de botão (onclick)
