# rockInRio-ERD
Entity Relationship Diagram (ERD), mapping and Data Dictionary

Deve ser incluido a regra de "cruzar mer com no mínimo 6 entidades, mapeamento e dicionário de dados" na organização de um evento como o Rock in Rio, vamos adaptar a ideia para se alinhar à gestão de informações essenciais ao evento. Isso pode envolver o mapeamento de dados-chave sobre os participantes e setores do evento, integrando o relacionamento entre diferentes entidades (pessoas, locais, atividades, etc.). Esta é uma versão adaptada para as regras de negócio:

---

*Regras de Negócio para o Rock in Rio: Mapeamento e Dicionário de Dados*

1. *Mapeamento de Entidades do Evento*
   - *Cruzamento de Mínimo de 6 Entidades*: No sistema de gerenciamento do Rock in Rio, deve-se cruzar no mínimo 6 entidades principais, como:
     - *Participantes*: Dados sobre os visitantes, público-alvo e suas informações de acesso.
     - *Artistas*: Dados de cada artista ou banda, incluindo horários, preferências e localização dos shows.
     - *Funcionários e Voluntários*: Informações dos colaboradores que trabalham no evento, suas funções e áreas de atuação.
     - *Fornecedores*: Dados dos fornecedores de alimentos, bebidas, serviços técnicos, entre outros.
     - *Locais*: Áreas específicas do evento, como palco principal, backstage, área de alimentação, zonas VIP, entre outras.
     - *Equipamentos*: Inventário e localização de equipamentos críticos para o evento, como sistemas de som, iluminação e estruturas de palco.
  
2. *Dicionário de Dados*
   - *Definição de Termos e Atributos*: Para cada entidade, criar um dicionário de dados que contenha:
     - *Participantes*: Nome, idade, tipo de ingresso, zona de acesso, etc.
     - *Artistas*: Nome, horário de apresentação, requisitos técnicos, tipo de palco, etc.
     - *Funcionários*: Nome, cargo, área de atuação, turno, identificação de segurança, etc.
     - *Fornecedores*: Nome da empresa, tipo de serviço, horário de operação, contato de emergência.
     - *Locais*: Nome do local, capacidade, acesso restrito, ponto de apoio, e medidas de segurança.
     - *Equipamentos*: Tipo de equipamento, local de instalação, responsável, e status de funcionamento.

3. *Integração e Consulta de Dados*
   - O sistema de dados deve permitir *consultas rápidas* e *integração* entre as entidades, possibilitando o cruzamento de informações. Exemplo: relacionar artistas com seus horários e requisitos técnicos, ou fornecedores com suas zonas de operação.

4. *Mapeamento Relacional*
   - Estabelecer um *Modelo Entidade-Relacionamento (MER)* que mostre as conexões entre as entidades. Por exemplo:
     - Um artista pode estar relacionado a um local específico (palco) e a um fornecedor (técnico de som).
     - Participantes podem estar relacionados a zonas de acesso específicas e ao tipo de ingresso.
  
5. *Segurança e Acessibilidade dos Dados*
   - Definir níveis de acesso para cada tipo de dado, garantindo que apenas pessoal autorizado visualize informações sensíveis (e.g., artistas e suas exigências específicas).
   - Assegurar que o dicionário de dados seja atualizado e acessível em tempo real para todos os setores responsáveis durante o evento.
