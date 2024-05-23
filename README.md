# Sistema de Controle Financeiro
Descrição do Projeto
Este projeto é um sistema simples para controle financeiro, desenvolvido para avaliar a qualidade do software em relação à Engenharia de Requisitos. O sistema foi criado com base em uma solicitação de um cliente (aluno) que requer as seguintes funcionalidades:

Manutenção de Receitas: Inclusão, alteração, exclusão e consulta de receitas, contendo os seguintes dados:

Número de controle
Descrição
Data
Valor
Manutenção de Despesas: Inclusão, alteração, exclusão e consulta de despesas, contendo os seguintes dados:

Número de controle
Descrição
Valor a pagar
Data de vencimento
Data de pagamento
Valor pago
Fluxo de Caixa: Visualização de contas pagas, contas vencidas e balanço financeiro.

Objetivo
O objetivo deste projeto é avaliar a qualidade do software entregue, verificando se os requisitos foram atendidos. Para isso, foi estabelecido um critério de avaliação e elaborados quesitos a serem respondidos pelo avaliador.

Critério de Avaliação
A avaliação segue o critério de notas de 1 a 5, sendo:

1 – Péssimo
2 – Ruim
3 – Regular
4 – Bom
5 – Excelente
Quesitos de Avaliação
1. Manutenção de Receitas
1.1. Todos os dados requisitados estão disponíveis para cadastro.
1.2. O número de controle não permite ser repetido.
1.3. A descrição possui tamanho razoável para descrever a receita.
1.4. A descrição e o valor são obrigatórios.
1.5. A consulta permite a especificação de um período.

2. Manutenção de Despesas
2.1. Todos os dados requisitados estão disponíveis para cadastro.
2.2. O número de controle não permite ser repetido.
2.3. A descrição possui tamanho razoável para descrever a despesa.
2.4. A descrição, o valor a pagar e a data de vencimento são obrigatórios.
2.5. A consulta permite a especificação de um período.
2.6. A funcionalidade de alteração de despesas é intuitiva e fácil de usar.
2.7. A exclusão de despesas é confirmada antes de ser realizada.
2.8. A interface de consulta de despesas é clara e de fácil navegação.

3. Fluxo de Caixa
3.1. O sistema permite visualizar todas as contas pagas.
3.2. O sistema permite visualizar todas as contas vencidas.
3.3. O balanço financeiro é apresentado de forma clara e compreensível.
3.4. O sistema oferece relatórios detalhados de fluxo de caixa.
3.5. A interface de fluxo de caixa é intuitiva e fácil de usar.
3.6. A atualização das informações de fluxo de caixa é rápida e precisa.
3.7. A funcionalidade permite a exportação de relatórios de fluxo de caixa em formatos comuns (por exemplo, PDF, Excel).
3.8. O sistema permite a geração de gráficos para melhor visualização do fluxo de caixa.

Resumo da Entrega
Olá, aluno(a)!

O trabalho tem basicamente a seguinte ideia: considere que você desenvolveu um software para determinada empresa e depois de alguns meses gostaria de saber se os critérios desejados pela empresa foram atendidos. Por exemplo, a consulta das vendas realizadas. O cliente atribuirá uma nota de 0 a 5 para essa "tela" do sistema sobre consulta de vendas. Você deverá elaborar perguntas para cada quesito apresentado acima. Mas lembre-se, utilizei apenas um exemplo, o sistema pode ser da forma que você desejar. Você pode utilizar uma planilha do Excel para organizar as informações, mas fica ao seu critério.

Como Executar o Projeto
Requisitos
Python 3.x
Flask
Postman (para testar os endpoints)
