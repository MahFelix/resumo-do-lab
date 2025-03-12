# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


Primeiro, vi como criar uma conta gratuita no Azure, entendendo que a Microsoft oferece um crédito inicial e alguns serviços gratuitos por um tempo limitado. 
Também aprendi que, apesar de precisar cadastrar um cartão, não há cobrança automática se eu não atualizar a conta para o plano pago.

Depois, entrei no conceito de computação em nuvem e como ela funciona. Basicamente, a nuvem permite acessar recursos computacionais sob demanda, 
sem precisar investir em infraestrutura física. Isso traz vantagens como escalabilidade, flexibilidade e custo mais previsível.

Outro ponto importante foi a comparação entre os modelos de nuvem. 
Aprendi sobre os três principais tipos de nuvem:
<br><br>
Nuvem Pública – É oferecida por provedores como AWS, Azure e Google Cloud, onde os recursos são compartilhados entre vários usuários. É uma opção escalável e econômica, ideal para empresas que não querem investir em infraestrutura própria.
<br><br>
Nuvem Privada – Criada e utilizada exclusivamente por uma única empresa, oferecendo mais controle e segurança. Pode estar hospedada localmente ou em um data center terceirizado.
<br><br>
Nuvem Híbrida – Combina a nuvem pública e privada, permitindo que empresas aproveitem a escalabilidade da nuvem pública enquanto mantêm dados sensíveis em uma nuvem privada.
<br><br>

Além disso, também vi a diferença entre CapEx (Capital Expenditure) e OpEx (Operational Expenditure). CapEx são investimentos grandes e pontuais, como comprar servidores físicos, enquanto OpEx são custos operacionais recorrentes, como pagar por serviços de nuvem conforme o uso. A vantagem da computação em nuvem é justamente permitir que empresas foquem mais no modelo OpEx, pagando apenas pelos recursos utilizados, sem a necessidade de grandes investimentos iniciais.

<br><br>
<br><br>
Entre os temas abordados, exploramos os benefícios da nuvem Microsoft Azure e sua relevância para a construção e implantação de APIs.
<br><br><br><br>
Benefícios da Microsoft Azure
Aprendemos que a Azure oferece um conjunto robusto de soluções que facilitam a escalabilidade, segurança e gerenciamento de aplicações na nuvem. Entre os principais benefícios, destacam-se:
<br><br>
Escalabilidade e Performance: A Azure permite a alocação dinâmica de recursos, garantindo que as aplicações suportem variações na demanda sem comprometer a performance. Isso é especialmente útil para arquiteturas baseadas em microservices e APIs REST.
<br><br>
Segurança Avançada: A plataforma oferece integração nativa com Azure Active Directory (AAD), permitindo um controle de acesso eficiente. Além disso, suporta OAuth 2.0, OpenID Connect e JWT, fundamentais para a autenticação e proteção de APIs.
<br><br>
Modelo de Custo Sob Demanda (Pay-as-You-Go): Um dos grandes diferenciais da Azure é a flexibilidade no custo, pois os serviços são cobrados conforme o uso, otimizando investimentos e evitando gastos desnecessários.
<br><br>
Integração com DevOps e CI/CD: Utilizando ferramentas como GitHub Actions e Azure DevOps, é possível configurar pipelines automatizados para deploy contínuo, garantindo agilidade no desenvolvimento e entrega de software.
<br><br>
Serviços Gerenciados para Backend e Banco de Dados: Aprendemos que a Azure oferece soluções como Azure App Service, permitindo a implantação de APIs Spring Boot sem a necessidade de gerenciar infraestrutura. Além disso, serviços como Azure SQL Database, Cosmos DB e Redis possibilitam o armazenamento de dados com alto desempenho e segurança.
<br><br><br><br>
Alta Disponibilidade e SLA
Outro aspecto fundamental estudado foi a garantia de disponibilidade dos serviços em nuvem, que é definida por meio do SLA (Service Level Agreement). O SLA estabelece o tempo máximo de inatividade permitido para um sistema ao longo de diferentes períodos. Conforme vimos na tabela de referência:
<br><br>
Um SLA de 99% significa que o serviço pode ficar indisponível por até 3,65 dias ao ano.
Com um SLA de 99,9%, o tempo de inatividade reduz para 8,76 horas ao ano.
Já um SLA de 99,99% assegura uma interrupção máxima de apenas 52,56 minutos ao ano.
No caso do 99,999% (Five Nines), a inatividade anual é inferior a 5,26 minutos, sendo essa a meta de disponibilidade adotada por empresas que prestam serviços críticos, como bancos e instituições de saúde.
Essa compreensão nos permitiu avaliar a importância de definir corretamente o SLA conforme as necessidades do negócio, garantindo um equilíbrio entre custo e disponibilidade. A Microsoft Azure, com sua infraestrutura global e serviços gerenciados, proporciona suporte para alcançar altos níveis de disponibilidade, sendo uma excelente escolha para o desenvolvimento de APIs seguras e escaláveis.

