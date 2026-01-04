# calculadora-fii-realista
Meu primeiro projeto de Excel: um simulador de investimentos em FIIs que desconta a inflação e projeta o poder de compra real ao longo do tempo
Olá! Este é o meu primeiro projeto prático de Excel e também minha estreia aqui no GitHub. Desenvolvi esta calculadora como projeto de um curso que estou realizando, com o objetivo de aplicar na prática tudo o que aprendi sobre fórmulas financeiras, lógica de dados e dashboards interativos.

🌟 O Desafio
Ao começar a estudar sobre investimentos em Fundos Imobiliários (FIIs), percebi que muitas calculadoras na internet são "otimistas demais" pois não consideram a inflação. Meu objetivo foi criar uma ferramenta que mostrasse a realidade nua e crua: quanto o seu dinheiro realmente vai valer no futuro (Poder de Compra).

🧠 O que eu aprendi e apliquei
Neste projeto, saí das fórmulas básicas e explorei recursos avançados do Excel que eu não conhecia:

1. Matemática Financeira Realista
Aprendi a usar a função VF() (Valor Futuro), mas o maior aprendizado foi entender a diferença entre Taxa Nominal e Taxa Real.

Desenvolvi uma fórmula para descontar a inflação (IPCA) mensalmente, garantindo que o gráfico mostre o crescimento real do patrimônio.

2. Inteligência por Perfil (Lógica Ponderada)
Em vez de uma taxa fixa, criei uma aba AUXILIAR que funciona como o "cérebro" da planilha.

Usei a função SOMARPRODUTO para que, ao escolher um perfil (Conservador, Moderado ou Agressivo), a planilha calcule automaticamente o rendimento com base em uma carteira diversificada de FIIs de Papel, Tijolo e outros.

3. Gráficos Interativos

Usei o Gerenciador de Nomes combinado com a função DESLOC. Isso permite que o usuário escolha ver a projeção de 2 anos até 30 anos, e o gráfico se ajusta sozinho na tela sem deixar espaços vazios.

📊 Como a planilha funciona
Configuração: O usuário insere o salário e quanto deseja investir.

Personalização: É possível escolher o perfil de risco e se os dividendos serão reinvestidos ou não.

Visualização: O dashboard mostra 4 curvas:

Nominal vs Real (com reinvestimento).

Nominal vs Real (sem reinvestimento).

🛠️ Tecnologias e Funções utilizadas
Excel (Funções: VF, DESLOC, SOMARPRODUTO, SE, VALIDACAO DE DADOS).



Dica de Aluno: Se você está começando no Excel como eu, o maior aprendizado aqui foi quebrar a cabeça com o erro #VALOR! até entender como as referências de abas funcionam. Foi difícil, mas valeu a pena!

Sinta-se à vontade para baixar, testar e me dar feedbacks. Toda sugestão é muito bem-vinda para o meu crescimento!
