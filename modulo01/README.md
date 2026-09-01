🍧 Sistema de Vendas - Açaiteria (CLI)
Este projeto consiste num Sistema de Vendas para Açaiteria desenvolvido em Python, que funciona via linha de comando (CLI - Command Line Interface). O sistema permite cadastrar produtos, consultar o catálogo disponível e realizar vendas com atualização automática do estoque.

👥 Visão Geral e Papéis do Projeto
O sistema foi estruturado considerando as necessidades de diferentes atores do negócio:

PO (Dono do Negócio): Controle centralizado das vendas e dos produtos em estoque.
QA (Visão do Cliente): Facilidade e rapidez no processo de compra dos produtos favoritos.
Tech / Dev (Programador): Código eficiente, funcional e preparado para manutenção.
UX (Designer): Planejamento focado na experiência do usuário para futuras versões com interface.
IA (Analista de Dados): Estrutura preparada para coleta de dados de consumo e otimização de estoque.
🔄 Ciclo de Vida do Desenvolvimento
Planejamento: Definição dos requisitos do sistema e necessidades do negócio.
Análise: Modelagem de dados e validação de requisitos.
Desenvolvimento: Construção da lógica em Python via CLI.
Testes: Validação dos fluxos de cadastro, listagem e controle de estoque.
Implantação: Execução do script no ambiente de produção/terminal local.
Manutenção: Correção de bugs e preparação para o lançamento da versão com Interface Gráfica (GUI).
🚀 Funcionalidades do Sistema
1 - Cadastrar Produto: Permite o registro de até 3 produtos individuais guardando nome, quantidade em estoque, preço, data de validade e descrição.
2 - Listar Produtos: Exibe todos os produtos cadastrados com seus respetivos detalhes e quantidade disponível.
3 - Realizar Venda: Permite selecionar o produto pelo nome, informar a quantidade desejada, calcular o valor total e dar baixa automática no estoque.
0 - Sair: Encerra a execução do programa de forma segura.
🛠️ Tecnologias e Conceitos Utilizados
Linguagem: Python 3
Estruturas de Repetição: Laço while True para manter o menu ativo.
Estruturas Condicionais: if / elif / else para controle do fluxo e opções do menu.
Validação de Estoque: Subtração automática e impedimento de vendas sem quantidade suficiente.
Formatação de Texto: Manipulação de strings com .lower() para busca sem diferenciar maiúsculas/minúsculas e formatadores de moeda :.2f.
💻 Como Executar o Programa
Pré-requisitos
Python 3.x instalado no sistema.
Passo a Passo
Baixar o Código: Salve o arquivo Python (por exemplo, acaiteria.py) na sua máquina.

Abrir o Terminal: Navegue até a pasta onde o arquivo foi salvo.

Executar a Aplicação: Execute o seguinte comando no terminal: