# Análise de Chamados de Suporte Técnico

Link para visualizar o arquivo PBI na íntegra: [Visão Gerencial de Atendimento de Chamados](https://app.powerbi.com/view?r=eyJrIjoiNThhNDMxYTMtOTEwZS00OGZkLThhMjgtZjk4ZWM3N2NhMjMwIiwidCI6ImFiNTNkNTJlLWRmNDctNDlmOS04OTYwLThhMmQzMjBkMGM4ZCJ9)  

Link para baixar a base de dados em excel: 

## Contextualização
Participei de um desafio para gerar insights de negócios a partir de dados de chamados do time de suporte técnico. Sem instruções prévias, a proposta era surpreender a diretoria com análises 
relevantes apresentadas de forma visual, impactante e sugerindo ações. Foi disponibilizado um arquivo em excel (link acima) contendo 400 linhas de registros.

**Prazo de entrega:** 1 dia corrido (dados recebidos na quinta-feira às 13h, entrega até sexta-feira às 18h).


## Resolução

**1. Análise inicial da base de dados**  
   Como se trata de uma base de dados pequena, a análise inicial foi feita pelo próprio excel para entender o contexto e verificar os valores nulos.   

   <p align="center">
    <img src="https://github.com/user-attachments/assets/82dbcb64-7f73-4095-a25c-e0db813ac4b2" width="800" height="191" />
   </p>   

   Foram identificados valores nulos nas colunas "Data de Resolução" e "Tempo de Atendimento". Isso é esperado para chamados “Abertos” ou “Em andamento”, mas 11 chamados “Resolvidos” também
   apresentam nulos. Esses registros foram tratados como erros e desconsiderados através da maipulação via Power Query, visando preservar o arquivo em seu estado original.

**2. Definição dos indicadores de performance e estruturação do dashboard**   
   Após compreender os dados, defini perguntas-chave e testes para avaliar a performance da operação e identificar desvios. Embora tenha sido a etapa mais trabalhosa, foi essencial, pois um bom planejamento garante a excelência na entrega. Uma 
   vez em posse do escopo das informações, estruturei o layout abaixo:
   
   <p align="center">
   <img src="https://github.com/user-attachments/assets/e216717d-ba68-4a18-a904-84ef160d3d85" width="800" height="449"/>
   </p>   

**3. Visão geral do dashboard filtrado para os chamados resolvidos**
   Observações:   
   - O mês fevereiro apresentou o maior tempo médio de resolução, embora a quantidade de chamados tenha ficado abaixo da média geral;
   - Houve 	um aumento expressivo de chamados no mês de maio;
   - O gráfico de dispersão evidenciou que os “bugs” tiveram maiores ocorrências cujas resoluções demandaram a alocação intensiva de horas de trabalho;
   - Ação: este fato traz o insight sobre a oportunidade de investir em ações preventivas, tais como análise de risco e manutenção antecipada, de modo a reduzir a ocorrência desses casos;





<p align="center">
<img src="https://github.com/user-attachments/assets/c91674dc-0256-4f3b-b189-941cf0af2e6b" width="800" height="449" alt="image" />
</p>  
