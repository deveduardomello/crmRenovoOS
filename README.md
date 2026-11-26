### CRM Renovo OS

Desenvolvi este sistema de CRM com quadro Kanban interativo (drag and drop) para resolver uma dor operacional real: centralizar e organizar o funil de prospecção comercial da agência Renovo, substituindo controles manuais por uma ferramenta web ágil e feita sob medida para a rotina da operação.

Arquitetura e Escolhas Técnicas:

Java & Spring Boot: Escolhidos para o núcleo do back-end pela robustez, segurança e facilidade na estruturação das regras de negócio, validações e persistência do fluxo de etapas dos leads.

Spring Data JPA / Hibernate: Utilizado para mapear o modelo relacional para objetos Java de forma limpa, acelerando o desenvolvimento das operações de CRUD e a movimentação dos cards entre as colunas do funil.

MySQL: Adotado como banco de dados relacional para garantir integridade transacional, consistência nos registros de clientes e histórico seguro das negociações.

Thymeleaf, HTML, CSS e JavaScript: O Thymeleaf foi escolhido para renderização server-side integrada ao Spring, facilitando o reaproveitamento de layouts e componentes. No front-end, utilizei JavaScript puro com HTML e CSS para implementar a dinâmica fluida de drag and drop e a atualização visual imediata das colunas sem sobrecarga de frameworks pesados.

Infraestrutura Self-Hosted (ZimaOS): Para manter o sistema operando continuamente com custo zero de nuvem, configurei e realizei o deploy da aplicação em um servidor caseiro dedicado rodando em um container Docker no ZimaOS (Intel Core i5 de 3ª geração, 8GB RAM), onde o CRM roda de forma estável em produção junto a outros serviços internos.

Produtividade e Uso de IA no Desenvolvimento:
Para otimizar o tempo de entrega sem abrir mão da qualidade arquitetural, utilizei ferramentas de Inteligência Artificial como copiloto para acelerar a geração de boilerplate de front-end (HTML/CSS/JS). Todo o direcionamento da arquitetura, separação de responsabilidades entre arquivos, integração com o back-end Java e ajustes finos de código foram conduzidos e revisados manualmente por mim.
