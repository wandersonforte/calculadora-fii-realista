# calculadora-fii-realista
Meu primeiro projeto de Excel: um simulador de investimentos em FIIs que desconta a inflação e projeta o poder de compra real ao longo do tempo

Olá! Este é o meu primeiro projeto prático de Excel, desenvolvido como parte de um desafio de laboratório na DIO (Digital Innovation One). O objetivo foi transformar conceitos teóricos de finanças e ferramentas de produtividade em uma solução real que ajude investidores a planejarem seu futuro com Fundos Imobiliários.

- O DESAFIO
O professor nos propôs o seguinte: construir uma ferramenta que automatize cálculos complexos e responda às dúvidas mais comuns de quem investe: "Quanto vou ter no futuro?", "Qual será minha renda mensal?" e "Quanto preciso investir por mês?".

Mais do que apenas números, o foco foi criar algo que auxiliasse na tomada de decisão informada, saindo do "achismo" e indo para a simulação baseada em dados.

- O QUE EU CONSTRUI?
Eu desenvolvi uma Calculadora de Investimentos em FIIs que não foca apenas no saldo final, mas no poder de compra. Afinal, R$ 1 milhão hoje não comprará as mesmas coisas daqui a 30 anos.

- DESTAQUES DA FERRAMENTA:
Inteligência por Perfil: Em vez de uma taxa fixa, a planilha calcula o rendimento baseado no perfil do usuário (Conservador, Moderado ou Agressivo), simulando uma carteira real de ativos (Papel, Tijolo, etc.).

O Efeito "Bola de Neve": Criei uma função onde o usuário decide se quer reinvestir os dividendos ou não, mostrando visualmente a diferença brutal que isso faz no longo prazo.

Filtro de Inflação: A planilha desconta a inflação estimada para mostrar o Patrimônio Real (quanto o seu dinheiro valerá em "valores de hoje").

Gráfico Interativo: Usei técnicas para que o gráfico mude conforme o tempo escolhido (2, 5, 10... 30 anos), dando um "zoom" nos dados.

- O QUE APRENDI NO CAMINHO
Este projeto foi uma grande jornada de aprendizado. Para concluí-lo, precisei dominar:

Cálculos Financeiros: Aplicação de juros compostos com a função VF() e cálculos de rendimento ponderado.

Lógica e Automação: Aprendi a usar SOMARPRODUTO, DESLOC e o Gerenciador de Nomes para tornar a planilha dinâmica.

Documentação Técnica: Como estruturar este arquivo para que outros entendam o que eu fiz.

Ecossistema GitHub: Esta é minha primeira experiência subindo um projeto e documentando cada passo aqui.

- ESTRUTURA DO PROJETO
APP_INVEST: A interface onde tudo acontece. É o dashboard interativo.

AUXILIAR: Onde guardo as taxas de mercado e as tabelas de suporte que alimentam os gráficos.

- CONSIDERAÇÕES FINAIS

Fique à vontade para baixar, testar e me enviar sugestões. Estou apenas começando, mas muito orgulhoso do resultado!

Desenvolvido por Wanderson Forte durante o desafio de Excel na DIO. aqui foi quebrar a cabeça com o erro #VALOR! até entender como as referências de abas funcionam. Foi difícil, mas valeu a pena!

Sinta-se à vontade para baixar, testar e me dar feedbacks. Toda sugestão é muito bem-vinda para o meu crescimento!
