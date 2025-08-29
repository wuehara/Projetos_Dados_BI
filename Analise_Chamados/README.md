# Análise de Chamados de Suporte Técnico

Link para visualizar o arquivo PBI na íntegra: [Visão Gerencial de Atendimento de Chamados](https://app.powerbi.com/view?r=eyJrIjoiNThhNDMxYTMtOTEwZS00OGZkLThhMjgtZjk4ZWM3N2NhMjMwIiwidCI6ImFiNTNkNTJlLWRmNDctNDlmOS04OTYwLThhMmQzMjBkMGM4ZCJ9)  

Link para baixar a base de dados em excel: 

## Contextualização
Em julho de 2025, participei de um desafio para gerar insights de negócios a partir de dados de chamados do time de suporte técnico. Sem instruções prévias, a proposta era surpreender a diretoria com análises relevantes apresentadas de forma visual, impactante e sugerindo ações. Foi disponibilizado um arquivo em excel (link acima) contendo 400 linhas de registros.

**Prazo de entrega:** 1 dia corrido (dados recebidos na quinta-feira às 13h, entrega até sexta-feira às 18h).


## Resolução

**1. Análise inicial da base de dados**   <br><br>
   Como se trata de uma base de dados pequena, a análise inicial foi feita pelo próprio excel para entender o contexto e verificar os valores nulos.   
<br>
   <p align="center">
    <img src="https://github.com/user-attachments/assets/82dbcb64-7f73-4095-a25c-e0db813ac4b2" width="800" height="191" />
   </p>   
<br>
   Foram identificados valores nulos nas colunas "Data de Resolução" e "Tempo de Atendimento". Isso é esperado para chamados “Abertos” ou “Em andamento”, mas 11 chamados “Resolvidos” também
   apresentam nulos. Esses registros foram tratados como erros e desconsiderados através da maipulação via Power Query, visando preservar o arquivo em seu estado original.
<br><br>

**2. Definição dos indicadores de performance e estruturação do dashboard**   <br><br>
   Após compreender os dados, defini perguntas-chave e testes para avaliar a performance da operação e identificar desvios. Embora tenha sido a etapa mais trabalhosa, foi essencial, pois um bom 
   planejamento garante a excelência na entrega. Uma vez em posse do escopo das informações, estruturei o layout abaixo:   
<br>
   <p align="center">
   <img src="https://github.com/user-attachments/assets/e216717d-ba68-4a18-a904-84ef160d3d85" width="800" height="449"/>
   </p>   
<br>

**3. Visão geral do dashboard filtrado para os chamados com o status "Resolvido"**   <br><br>
   Observações:   
   - Em fevereiro, o tempo médio de resolução foi o mais alto, mesmo com volume de chamados abaixo da média geral;
   - Em maio, observou-se um aumento expressivo no número de chamados;
   - O gráfico de dispersão destacou que os “bugs” tiveram maior ocorrência e exigiram alocação intensiva de horas de trabalho para resolução.
<br>

   <p align="center">
   <img src="https://github.com/user-attachments/assets/c91674dc-0256-4f3b-b189-941cf0af2e6b" width="800" height="449" alt="image" />
   </p>   
<br>

**3.1. Mantendo o status "Resolvido" e filtrando apenas o mês de fevereiro**   <br><br>
   Observações:   
   - Em fevereiro, alguns casos de maior dispêndio de tempo concentraram-se em dois membros do time: Patrícia e Lucas;
   - O tempo dedicado por eles correspondeu a cerca de metade do total do time no período;
   - As principais demandas vieram dos times de TI e Financeiro, especialmente em "Requisições" e "Incidentes";
   - Ação: avaliar com Patrícia e Lucas esses casos pontuais, assegurando que o time esteja preparado caso situações semelhantes se repitam futuramente.
<br>

   <p align="center">
   <img src="https://github.com/user-attachments/assets/62dd3ffb-5ebd-41bd-aea0-b96fa36bb262" width="800" height="449" alt="image" />
   <p align="center">
   <img src="https://github.com/user-attachments/assets/37949599-2a4c-4779-8553-8e4488ef96e7" width="800" height="449" alt="image" />
   </p>   
<br>

**3.2. Mantendo status "Resolvido" e filtrando apenas o mês de maio**   <br><br>
   Observações:   
   -	Ocorreu o aumento abrupto de chamados para resolução de "Bugs" no mês de maio;
   -	Esses casos representam 43% do total do tipo de casos atendidos no referido mês;
   -	Possivelmente houve a implantação ou atualização de algum sistema que não foi bem-sucedido;
   -	Ação: identificar a falha no processo, registrá-lo no mapeamento de análise de risco da área, investir em ações preventivas e melhores práticas;
<br>

   <p align="center">
   <img src="https://github.com/user-attachments/assets/d56dff0a-6c98-414d-a2c1-48610b1348c4" width="800" height="449" alt="image" />
   </p> 
<br>

**3.3. Mantendo status "Resolvido" e observando os responsáveis**   <br><br>
   Observações:   
   - João apresentou menor volume de chamados atendidos em comparação aos demais membros do time;
   - Na visão mensal, percebe-se uma queda em abril no número de chamados atendidos por ele;
   - Isso pode estar relacionado a férias ou outro afastamento no período;
   - Ação: caso não tenha ocorrido afastamento, recomenda-se redistribuir parte das demandas da Patrícia e do Lucas para o João, equilibrando a carga de trabalho entre os membros do time.
<br>

   <p align="center">
   <img src="https://github.com/user-attachments/assets/1b905e51-21f5-485d-84ae-67bec81a14a2" width="800" height="449" alt="image" />
   </p> 
<br>

**3.4. Filtrando os chamados com o status "Aberto" e "Em andamento"**   <br><br>
   Observações:   
   - Existem 12 chamados em aberto. É necessário contatar os solicitantes para entender os motivos e, se possível, concluir os chamados, atendendo às diretrizes da auditoria;
   - Ainda 11 chamados em andamento referentes ao primeiro quadrimestre do ano;
   - Ação: reunir o time para acompanhamento e acelerar o processo, garantindo a conclusão dos chamados.
<br>

   <p align="center">
   <img src="https://github.com/user-attachments/assets/7c9ab786-5496-4599-98d5-5d68c2dc81a8" width="800" height="449" alt="image" />
   <p align="center">
   <img src="https://github.com/user-attachments/assets/92a37a8a-ca1b-4999-b0b1-061407c43b5f" width="800" height="449" alt="image" />
   </p>
<br>
