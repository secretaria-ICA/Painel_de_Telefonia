
# Painel_de_Telefonia

#### Aluno: [Eduardo Mendes Tavares](https://github.com/edumenta)
#### Orientador: [Anderson Nascimento](https://github.com/insightds).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/edumenta/projeto-final). 

---

### Resumo

Este trabalho descreve um projeto desenvolvido com o objetivo de resolver problemas reais enfrentados pela gerência de TI responsável pela gestão do serviço de telefonia corporativo de uma empresa.

Para o desenvolvimento do trabalho foram utilizados para a extração, transformação e carga (ETL) dos dados as ferramentas, SQL Power Architect, Jupyter Notebook, Pentaho Data Integration e PostgreSQL. Para a elaboração do painel de telefonia foi utilizado o Power BI.
Ao final do projeto foi entregue para a empresa um Data Warehouse e um painel contendo os dados relevantes do sistema de telefonia.


### 1. Introdução

Devido à vasta quantidade de localidades atendidas, a diversidade de dispositivos telefônicos utilizados e o grande número de usuários, ter uma visão geral dos números relacionados ao Serviço de Telefonia Corporativo sempre foi um desafio para os gestores da área de TI desta empresa. Os dados sempre estiveram disponíveis, mas não havia uma integração, muito menos o acesso de forma interativa e intuitiva. Os levantamentos e consolidações das informações eram feitos por demanda e de forma manual.  

Este artigo apresenta a processo e a metodologia utilizados para a elaboração de um painel desenvolvido no Power BI, com informações a respeito da rede de telefonia. O desenvolvimento deste dashboard permitiu a integração dos dados, a disponibilização de self-service para análises específicas, tabelas e gráficos dinâmicos, tornando mais produtivo o planejamento e administração do serviço de telefonia.

### 2. Modelagem

Para a elaboração do painel de telefonia, foram utilizadas diversas fontes de dados.
A primeira fase do projeto consistiu no levantamento de requisitos e planejamento da solução com os gerentes da empresa. A etapa seguinte de planejamento da solução consistiu em definir a arquitetura e ferramentas utilizadas. O Modelo multidimensional foi desenvolvido na ferramenta Power Architect. 

O Data Warehouse foi implementado para realizar a integração das informações do serviço de telefonia relevantes para a elaboração do painel. Foi desenvolvido em um sistema de gerenciamento de banco de dados PostgreSQL, versão 12. A arquitetura escolhida foi a Global e Centralizada. Por conta disto, não foram desenvolvidos Data Marts. Além disso, optou-se por utilizar a arquitetura on-premisses.

Para o processo de ETL foram utilizadas as ferramentas Jupyter Notebook e Pentaho Data Integration (PDI).

### 3. Resultados

O painel foi elaborado considerando-se as necessidades de consulta, correlação e visualização de dados. Para isto foi utilizada a ferramenta Power BI. O painel apresenta informações, tais como quantidade total de ramais, quantidade de ramais que utilizam a tecnologia IP (VoIP) e TDM, quantidade de dispositivos distintos, quantidade de ramais por tipo de ambiente, quantidade de aparelhos telefônicos e softphone e histórico dos quantitativos de dispositivos distintos.

### 4. Conclusões

O painel elaborado tornou muito mais prática a visualização dos dados gerais do Serviço de Telefonia corporativo.  A integração dos dados e o acesso de forma interativa e intuitiva torna o consumo das informações fácil e imediato. Os levantamentos e consolidações que antes eram feitos por demanda e de forma manual agora estão disponíveis de forma direta. O acesso às informações do painel leva de imediato a alguns insights que têm colaborado com o acompanhamento e planejamento da evolução do serviço. 

---

Matrícula: 192.671.048

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
