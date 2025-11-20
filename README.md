🏧 Simulador de Caixa Eletrônico – Python:
Um programa em Python que simula o funcionamento de um caixa eletrônico, calculando automaticamente quantas cédulas de cada valor serão entregues ao usuário no momento do saque.

📌 Funcionalidades:
Recebe o valor do saque solicitado pelo usuário;
Calcula automaticamente quantas cédulas serão usadas;
Utiliza cédulas de R$50, R$20, R$10 e R$1;
Entrega sempre o menor número possível de cédulas (lógica de troco/greedy);
Exibe o resumo das cédulas entregues;
Finaliza com uma mensagem personalizada do banco.

🛠️ Tecnologias utilizadas:
Python 3.

▶️ Como executar o projeto:
Instale o Python 3 em seu computador;
Salve o arquivo como, por exemplo:

caixa_eletronico.py

Execute no terminal:
python caixa_eletronico.py

Informe o valor do saque quando solicitado.

📚 Exemplo de uso
===================================
            BANCO CEV
===================================
Qual valor você quer sacar? R$ 137
Total de 2 cédulas de R$50.
Total de 1 cédula de R$20.
Total de 1 cédula de R$10.
Total de 7 cédulas de R$1.
=============================================
     Volte sempre ao banco CEV. Tenha um bom dia!
=============================================

💡 Possíveis melhorias:
Permitir escolher quais valores de notas o caixa possui;
Registrar histórico de saques;
Criar uma versão com interface gráfica (Tkinter);
Criar API para simulação em uma aplicação web;
Adicionar verificação de valores inválidos.

📁 Estrutura sugerida do repositório:
Simulador-de-Caixa-Eletronico/
│── caixa_eletronico.py
└── README.md
