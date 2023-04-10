![descrição da imagem](https://i.ibb.co/9qC7ZrF/imagem.jpg)

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
