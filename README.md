# Kaggle Dataset: Diagnosis of COVID-19 and its clinical spectrum

**AI and Data Science supporting clinical decisions (from 28th Mar to 1st Apr)**

Este repositório foi criado para organizar os códigos, análises e referencias utilizadas no estudo do dataset disponibilizado pelo [Hospital Albert Einstein]() no Kaggle.

Autores e participantes do projeto:

  * [Fellipe Gomes](https://github.com/gomesfellipe) (Estatístico) 
  * [João Pedro Medeiros](http://lattes.cnpq.br/2533554356367029) (Estudante de Medicina)

**Atenção**: Toda a documentação abaixo foi obtida e traduzida livremente da descrição do Dataset no Kaggle: <https://www.kaggle.com/einsteindata4u/covid19>

Submissões:

  * Submissão Task 1: <https://www.kaggle.com/gomes555/task1-covid-19-diagnosis>
  * Submissão Task 2: <https://www.kaggle.com/gomes555/task2-covid-19-admission-ac-94-sens-0-92-auc-0-96>

# Background

A Organização Mundial da Saúde (OMS) caracterizou o COVID-19, causado pela SARS-CoV-2, como uma pandemia em 11 de março, enquanto o aumento exponencial no número de casos estava em risco de sobrecarregar os sistemas de saúde em todo o mundo com uma demanda. para leitos de UTI muito acima da capacidade existente, com regiões da Itália sendo exemplos proeminentes.

O Brasil registrou o primeiro caso de SARS-CoV-2 em 26 de fevereiro, e a transmissão do vírus evoluiu apenas de casos importados, para transmissão local e finalmente comunitária muito rapidamente, com o governo federal declarando transmissão comunitária em 20 de março.

Até 27 de março, o estado de São Paulo registrava 1.223 casos confirmados de COVID-19, com 68 mortes relacionadas, enquanto o município de São Paulo, com uma população de aproximadamente 12 milhões de pessoas e onde o Hospital Israelita Albert Einstein está localizado, possuía 477 casos confirmados e 30 mortes associadas, a partir de 23 de março. Tanto o estado como o município de São Paulo decidiram estabelecer medidas de quarentena e de distanciamento social, que serão aplicadas pelo menos até o início de abril, em um esforço para retardar a propagação do vírus.

Uma das motivações para esse desafio é o fato de que, no contexto de um sistema de saúde sobrecarregado com a possível limitação para realizar testes para a detecção de SARS-CoV-2, testar todos os casos seria impraticável e os resultados dos testes poderiam ser postergados, mesmo se apenas uma subpopulação de destino seria testada.

# Dataset

Este conjunto de dados contém dados anonimizados de pacientes atendidos no Hospital Israelita Albert Einstein, em São Paulo, Brasil, e que tiveram amostras coletadas para realizar o SARS-CoV-2 RT-PCR e testes laboratoriais adicionais durante uma visita ao hospital.

Todos os dados foram anonimizados seguindo as melhores práticas e recomendações internacionais. Todos os dados clínicos foram padronizados para ter uma média de zero e um desvio padrão unitário.

# Detalhes de tarefas

  1. Prever casos confirmados de COVID-19 entre casos suspeitos: 
    * Com base nos resultados de exames laboratoriais comumente coletados para um caso suspeito de COVID-19 durante uma visita à sala de emergência, seria possível prever o resultado do teste para SARS-Cov-2 (positivo / negativo)?
  2. Prever admissão na enfermaria geral, unidade semi-intensiva ou unidade de terapia intensiva entre os casos confirmados de COVID-19:
    * Com base nos resultados dos exames laboratoriais comumente coletados entre os casos confirmados de COVID-19 durante uma visita ao pronto-socorro, seria possível prever quais pacientes precisarão ser internados em uma enfermaria geral, unidade semi-intensiva ou unidade de terapia intensiva?

# Submissão Esperada

Envie um bloco de anotações que implemente o ciclo de vida completo da preparação dos dados, criação e avaliação do modelo. Sinta-se à vontade para usar esse conjunto de dados e outros dados disponíveis. Como essa não é uma competição formal, você não está enviando um único arquivo de envio, mas toda a sua abordagem para criar um modelo.

# Avaliação

Como não é uma competição formal, não avaliaremos os resultados estritamente em relação a um determinado conjunto de validação usando uma métrica estrita. Em vez disso, o que gostaríamos de ver é um processo bem definido para construir um modelo que possa oferecer resultados decentes (avaliado por você mesmo).

A Equipe avaliará:

  * **Desempenho do modelo**: Qual é o desempenho do modelo nos dados reais? Pode ser generalizado ao longo do tempo? Pode ser aplicado a outros cenários? Foi super ajuste?
  * **Preparação de dados**: Até que ponto os dados foram analisados antes de inseri-los no modelo? Existem visualizações úteis? O leitor aprende novas técnicas através desta submissão? Uma excelente entrada será informativa, instigante e atualizada, tudo ao mesmo tempo.
  * **Documentação**: Seu código, notebook e fontes de dados adicionais estão bem documentados para que o leitor possa entender o que você fez? Suas fontes são claramente citadas? Uma análise de alta qualidade deve ser concisa e clara em cada etapa, para que a lógica seja fácil de seguir e o processo seja reproduzível.

