### Introdução

Um desafio enfrentado por sistemas conversacionais é a manutenção da relevância e eficácia ao longo do tempo. A evolução da linguagem ocorre rapidamente, novos termos, contextos e novos fenômenos de como as pessoas expressam aparecem regularmente. Este fenômeno é conhecido como “concept drift”, quando as relações entre os dados e as características do problema mudam ao longo do tempo . Quando os modelos não são devidamente atualizados, as respostas podem ser imprecisas – ou anteriores, prejudicando a exatidão da experiência do usuário.


### Solução proposta

Para resolver o problema do aprendizado contínuo em relação aos sistemas conversacionais, sugerimos um sistema de atualização automática. Ele possui três blocos principais que são Coleta de dados, Treinamento progressivo e Avaliação.

### Diagrama de Blocos

<img width="309" alt="image" src="https://github.com/renanribeir0/-aprendizado-cont-nuo-num-sistema-conversacional/assets/110369271/92d5e6f5-68dc-412a-862f-3bcd291e7f55">


### Descrição dos Blocos

**Coleta de dados:**
Reúne dados de várias fontes como conversas recentes, comentários do usuário, interações com APIs externas, entre outras.

Usa linguagem natural técnica processamento para extrair as informações necessárias de todas as fontes e prepará-las para treinamento.

**Treinamento Incremental:**

Assume os dados obtidos anteriormente e os introduz no sistema regulamente para treinamento.

Utiliza algoritmos de aprendizado incremental, como o Online Learning, para ajustar o modelo aos novos dados sem a necessidade de reprocessar todo o conjunto de treinamento.

### Conclusão
A proposta de implementar um sistema de aprendizado contínuo em sistemas conversacionais visa mitigar os desafios decorrentes da falta de atualização dos modelos. Embora demande esforço inicial para desenvolvimento e integração dos diferentes blocos, a implementação dessa solução pode trazer benefícios significativos a longo prazo, garantindo que o sistema permaneça relevante e eficaz em face das mudanças constantes na linguagem e nos contextos de uso.

### Referências Bibliográficas
Gama, J., Sebastião, R., & Rodrigues, P. (2009). Issues in evaluation of stream learning algorithms. In Proceedings of the 15th ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 329-338).
Nguyen, T. B., Nguyen, T. T., Nguyen, L. M., & Pham, S. B. (2019). A survey on concept drift adaptation. ACM Computing Surveys (CSUR), 52(4), 1-38.
Raza, K., Iqbal, W., & Celebi, M. E. (2020). A systematic review on concept drift adaptation. Applied Soft Computing, 96, 106634.
