## Código

Implementei conforme solicitado no desafio:
https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs

Os testes estão passando.

Fiquei na dúvida de qual deveria ser a resposta da rota `repositories/:id/like`.
Não sabia se retornava o objeto inteiro com os likes ou apenas os likes
já que conforme foi dito no enunciado, era para os os likes como um entidade diferente.

De todo modo como era um POST, retornei o status code `201`.
