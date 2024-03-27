# Laboratório Microsoft Azure 1
1. Criou-se um novo recurso;
2. Foi criado um novo grupo de recursos;
3. Foi preenchido os dados com nome, região, conta de armazenamento, os outros dados foram preenchidos automaticamente como: cofre de chaves e Application Insights;
4. Após carregar é colocado no criar;
5. Demorou um pouco enquanto estava a implantação;
6. Foi aberto o estúdio;
7. Após isso foi clicado em ML automatizado;
8. Foi clicado em novo trabalho de ML automatizado;
9. Foi criado um ML automatizado com o nome mslearn-bike-automl e colocado a descrição de aprendizado de máquina para aluguel de bikes automatizados;
10. Foi escolhido o tipo de tarefa com regressão;
11. Foi colocado o nome e o tipo de ativo de dados como aluguel de bicicletas e a descrição com dados historicos de aluguel de bicicletas e tipo tabular;
12. Foi selecionado a fonte para o ativo de dados de arquivos Web;
13. Foi adicionado o url da documentação;
14. As configurações foram deixadas como estavam: Delimitado, vírgula e UTF-8;
15. Em esquema não foi mudado nada;
16. Configuração de tarefas: coluna de destino foi colocado rentals, configurações adicionais normalizedrootmeansaquqredError e foram desmarcadas as opções, modelos permitidos randomforest e LightGBM;
17. Máximo de avaliações 3, máximo de avaliações simultâneas 3, limite de pontuação de métrica 0,085, tempo limite de experimento 15 min, tempo limite de iteração 15 minutos, estes foram os dados configurados;
18. tipo de validação: divisão de validação de treinamento;
