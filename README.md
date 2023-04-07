![descrição da imagem](https://lh3.googleusercontent.com/l2HpAMpTN1kkJMpomZBCTHW82yC4oJhdBzUUTogsb7k8POXtBlM-_8I7_G0cQgfx2MJCSl23lED_Lrj8EL5nUS_XSjrM9DFEDnw7tOcGI-sNCCjeLIJWIUoLwali_5SLCdqfCfEHvzC14jzdXndZF8w07oHlTAv724JDBLl-n6yYEjQIo2-5lWyKZFLi5KN2970iFqEdvudz3SNIySzVYq8eeFmk_-Tl-tLxQ9EORIG-ViB2_1f_TpPrjB_saQQ295FyQ5S09XWTyQH3BpDPnw_MXy8uurPHfHb_4ukDf7tUiqG4Z2GcteJOm5IUWXkGeqzaB4yZiTAizs7y27o5NZJMB423gviQcsF0J62cjaNdklQk--nyrGhmj7xPcJvS1D10W4-WcCDABaeJj2UCH_uZzFwoqKsZ7X1cdW0vttrw6XP5KVDEKknT752pYN-HzwpeobaW5-t2-_oYhxoX-bLWoz8r9aCZBxItK3fZ7Ya2RHjDnkpLjFJlD8Dj8Gy7qD4TW-kPA0mKBiysrkVgdGAnl8sw0KVVh7PIYoFXf_PZtZvZpacV7Qnzfs4RJag2jNLz6YzM5tIEF1h3fY7UgaO2o4xHniX_ZRh31r9-FaEKiE7lIK4TbZnsaVXnhIj6F5_RhWZolwbFvY_eyOlc0n00wDQaRnH3msPAQSL77gQGbTO-QPfHU16NXeNbn9BAI8073nH3tGCYYp3ICAd0R_ijZjiP8m78eJlIhcsN41oxJuU_ndwf7pErWv0KwxDdilHr9DSfzPRxbuJ3KPoxGLiQe4Bi-W9H48Yphcxr-dw2gmiPxkTke2aowYFeF1UFxuQsMOEggJ9mnCTFDB327XxDbomvNVF-pCP43hAC33Skjot6suE-bItZIJGBtEl6eTpND6VgBPFC0TBV1u9SLa_zRpQEFav_ZEZaChzS0CMgyCSBv0HSSoDGIWVMZh-f1I981CgXg41TETXXfc0aZ0rE4sP0dx7gkdtYQQMF8vPqddMAYjhydCGlMLVE7gFj36G9KphvCx8DwSaaUGtE9ymyjUGs8A=w1128-h191-s-no?authuser=0)

<p>A empresa fictícia Alura Voz tem o objetivo de diminuir as taxas de clientes que cancelam o contrato (Churn Rate), uma vez que é mais caro para o negócio conquistar um novo público do que manter a base atual.</p>
Os dados utilizados estão disponíveis <a href="https://raw.githubusercontent.com/sthemonica/alura-voz/main/Dados/Telco-Customer-Churn.json">aqui</a></br>
Me encontre no linkedIn clicando <a href="https://www.linkedin.com/in/edersonliver/">aqui</a>.</br>
Me acompanhe no Medium clicando <a href="https://medium.com/@edersonoliveira">aqui</a>.

<h3> Objetivo</h3>
<p>Esse projeto foi desenvolvido com o objetivo de utilizar o dataset de clientes da empresa para criar um modelo eficaz em prever se um determinado cliente irá evadir ou não.</p>

<h3>Etapas do projeto</h3>
<ol>
<li><b>Tratamento dos dados:</b></li>
<ul>
<li>Tratamento de dados ausentes e nulos</li>
<li>Transformação de dados categóricos</li>
<li>Concatenação de json</li>
</ul>
<br>
<li><b>Análise exploratória:</b></li>
<ul>
<li>Análise da taxa de churn</li>
<li>Análise dos tempos dos contrato</li>
<li>Análise de inconsistencia nos dados</li>
<li>Correlação entre as variáveis</li>
</ul>
<br>
<li><b>Machine learning:</b></li>
<ul>
<li>Balanceamento dos dados</li>
<li>Separação dos dados de treino e teste</li>
<li>Aplicação dos 4 modelos utilizados, com cross validation e otimização de hiperparâmetros</li>
<li>Avaliação das métricas</li>
</ul>
</ol>

<h3>Conclusão</h3>
<p>Após todo o tratamento e exploração do dataset, eu testei 4 modelos: Logistic Regression, Decision Tree Classifier, Random Forest Classifier e Support Vector Machine. Considerei o recall como a métrica mais importante para o problema de negócio em questão, uma vez que ela mostra o quanto o modelo consegue identificar quem realmente irá cancelar o contrato. Logo, o modelo mais adequado nessa situação foi o Decision Tree Classifier, capaz de acertar 83% dos verdadeiros positivos.</p>

<h3>Vale a pena investir nessa estratégia?</h3>
<p>Um modelo de prever churn é extremamente importante para empresas de telefonia, pois a retenção de clientes é fundamental para manter a rentabilidade e competitividade no mercado. Através da identificação de clientes propensos a deixarem a empresa, é possível desenvolver estratégias específicas para mantê-los, como oferecer descontos, upgrades de planos ou outros benefícios. Além disso, um modelo de prever churn permite que o negócio possa se antecipar a possíveis problemas de qualidade de serviço ou insatisfação dos clientes, possibilitando ações preventivas para evitar que esses problemas se transformem em cancelamentos.</p>


<h3>Dados do dataset</h3>
<ul>
<li>gender: gênero (masculino e feminino)</li>
<li>SeniorCitizen: informação sobre um cliente ter ou não idade igual ou maior que 65 anos</li>
<li>Partner: se o cliente possui ou não um parceiro ou parceira</li>
<li>Dependents: se o cliente possui ou não dependentes</li>
<li>Serviço de telefonia</li>
<ul>
    <li>tenure: meses de contrato do cliente</li>
    <li>PhoneService: assinatura de serviço telefônico</li>
    <li>MultipleLines: assisnatura de mais de uma linha de telefone</li>
</ul>
<li>Serviço de internet</li>
<ul>
    <li>InternetService: assinatura de um provedor internet</li>
    <li>OnlineSecurity: assinatura adicional de segurança online</li>
    <li>OnlineBackup: assinatura adicional de backup online</li>
    <li>DeviceProtection: assinatura adicional de proteção no dispositivo</li>
    <li>TechSupport: assinatura adicional de suporte técnico, menos tempo de espera</li>
    <li>StreamingTV: assinatura de TV a cabo</li>
    <li>StreamingMovies: assinatura de streaming de filmes</li>
</ul>
<li>Contrato</li>
<ul>
    <li>Contract: tipo de contrato</li>
    <li>PaperlessBilling: se o cliente prefere receber online a fatura</li>
    <li>PaymentMethod: forma de pagamento</li>
    <li>Charges.Monthly: total de todos os serviços do cliente por mês</li>
    <li>Charges.Total: total gasto pelo cliente</li>
</ul>
</ul>
