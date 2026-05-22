# Título: Charge Grid

# Equipe: GURGEL (Erick B., Erick Yu, Gustavo Araujo, Victor Henrique, Júlia Lemos, Carlos Henrique)

# Problema e Justificativa: 
O carregador veicular HCA da GoodWe permite que os proprietários utilizem energia proveniente da rede CA ou gerada por sistemas fotovoltaicos para o carregamento de veículos elétricos (VEs), contando ainda com função inteligente de troca de fase. No entanto, suas funcionalidades são limitadas ao uso residencial, uma vez que não possui sistema de cobrança, controle de potência ou cadastro de usuários, o que dificulta sua utilização no mercado convencional.

# Proposta e impactos esperados: 
A partir da configuração dos carregadores HCA da GoodWe, de modo que os dados dos cartões utilizados sejam removidos do banco de dados após cada utilização, será desenvolvido pela Gurgel um sistema responsável pelo gerenciamento dos cartões Gurgel nos carregadores. Esse sistema permitirá a realização de cobranças por meio de aplicativo, além de fornecer aos proprietários dos carregadores informações de monitoramento e controle sobre sua utilização, como, por exemplo, a regulagem de potência utilizada em seus carregadores, abrindo, dessa forma, janelas de oportunidade para a integração do antigo carregador HCA para o mercado geral com funcionamento integral.

# Tecnologias utilizadas: 
Python, PostgreSQL, OCPP (Open Charge Point Protocol), RFID, Flutter, API de pagamentos.

# Correlação entre Gurgel e os princípios de energias renováveis e sustentabilidade:
A proposta da Gurgel busca otimizar o uso da infraestrutura já existente dos carregadores HCA da GoodWe, ampliando-a, mas sem a necessidade de criação de novos sistemas físicos. Além disso, o interesse dos proprietários dos carregadores em manter o fornecimento de energia em níveis reduzidos contribui para um consumo energético mais eficiente, reduzindo desperdícios e impactos ambientais. Dessa forma, o projeto incentiva a utilização de veículos elétricos por meio de uma solução economicamente mais acessível e sustentável, favorecendo a substituição gradual de veículos movidos a combustíveis fósseis.
