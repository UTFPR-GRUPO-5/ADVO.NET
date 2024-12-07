
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: : https://padlet.com/correab/advo-net-shrfn4leziyskryy

## 1. Introdução

***1.1.  Nome do Grupo***

Grupo 5:

Nome - Arthur Aloysio Sottile Serrarens

GitHub - https://github.com/Arthursottile
_________________________________________
Nome - Bruno Santos Correa

GitHub - https://github.com/brunoscor
_________________________________________
Nome - Fhelipe Vinicios Dechico

GitHub - https://github.com/fdechico
_________________________________________
Nome - Igor Busquim de Moraes

GitHub - https://github.com/ibusquim 
_________________________________________
Nome - Rafael Spitzer Cardoso da Silva

GitHub - https://github.com/RafaSpitz

***1.2.  Nome do Sistema***

ADVO.NET

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pelo *Grupo 5*, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema ADVO.NET é registrar clientes/funcionários, gerenciar os processos, vinculá-los e atualizar dados de escritórios de advocacia em geral. O seu diferencial é o de aproximar o cliente da situação de seus processos, tendo uma versão mobile para a clientela e também para os funcionários.

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes e escritórios de advocacia.

***1.3. Descrição dos usuários***

Os usuários são em sua maioria advogados, promotores, etc e usariam-o para checar suas agendas e casos arquivado

***Personas:***

![85679cf5-f272-455c-a643-bbc863d00b9c](https://github.com/user-attachments/assets/06e0fa83-99df-4eae-8af4-46dce47c061c)

![794779c6-f96a-48a8-b0e7-70cac42e8110](https://github.com/user-attachments/assets/65b8c416-8656-4b44-83a2-99d91b48d52f)

![6b386817-2779-4841-b693-4a1387b66c24](https://github.com/user-attachments/assets/41cd28d8-a8f2-4e6a-b0a5-458df84b91ed)

![Inserir um título](https://github.com/user-attachments/assets/5b67a3f1-7eb0-4527-a7c4-0c6bd947cadd)


***Análise da situação atual: antes da introdução de sua solução***

O escritório antes sofria com uso exagerado de papel e os registros eram feitos e organizados em pastas e planilhas, tornando muito mais difícil e demorado o método de seleção e separação dos processos.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

Depois da implementação do ADVO.NET, o escritório e os advogados coexistem de maneira mais fácil, com os processos sendo selecionados e filtrados de maneira muito mais rápida usando o sistema e largando o uso do papel desnecessário.

***Cenário: Antes***

No escritório de advocacia Almeida & Fernandes, a gestão dos processos era uma tarefa árdua e cheia de desafios. João Almeida, advogado sênior, passava horas do seu dia ligando e trocando e-mails com sua equipe para atualizar os processos. Durante as reuniões externas, ele tinha dificuldades para encontrar dados recentes e era comum haver duplicidade de informações, já que os advogados registravam dados de maneira descoordenada. A comunicação constante com os clientes sobre o andamento dos casos era desgastante e consumia um tempo valioso.

Maria Fernandes, uma empresária cliente do escritório, sentia-se perdida em meio à burocracia jurídica. Sem muito conhecimento dos procedimentos legais, ela precisava ligar frequentemente para o escritório em busca de atualizações sobre seu processo. Esse acompanhamento constante era estressante e consumia muito tempo, tanto para ela quanto para os advogados.

Rafael Santos, administrador do sistema, enfrentava dificuldades para gerenciar as permissões de acesso e garantir a segurança das informações sensíveis do escritório. A falta de um sistema centralizado aumentava o risco de falhas de segurança, e Rafael gastava muito tempo lidando com problemas técnicos e realizando atualizações manuais em cada dispositivo.

Carlos Menezes, um ex-funcionário mal-intencionado, conhecia as brechas do antigo sistema e tentava acessar informações confidenciais usando credenciais antigas. Sem um mecanismo de auditoria robusto, suas tentativas de invasão passavam despercebidas, deixando o escritório vulnerável.

***Cenário: Depois***

Com a implementação do ADVO.NET, o escritório de advocacia Almeida & Fernandes passou por uma transformação significativa. João Almeida agora acessa e atualiza os processos de qualquer lugar, de forma ágil e eficiente. A duplicidade de informações foi eliminada, já que todas as atualizações são feitas diretamente no sistema centralizado. Os clientes recebem notificações automáticas sobre o andamento dos casos, o que reduziu drasticamente a necessidade de contatos frequentes. João pode dedicar mais tempo a atividades estratégicas e de alto valor para seus clientes.

Maria Fernandes utiliza o aplicativo móvel do ADVO.NETpara acompanhar seu processo em tempo real. Com uma interface simples e intuitiva, ela entende claramente cada etapa do processo e os prazos envolvidos. As notificações automáticas a mantêm informada sem a necessidade de ligar para o escritório, tornando sua experiência muito mais tranquila e eficiente.

Rafael Santos gerencia as permissões de acesso com facilidade através do ADVO.NET.O sistema inclui autenticação multifator e auditorias regulares, garantindo a segurança dos dados. Ele recebe notificações instantâneas sobre acessos suspeitos e pode bloquear tentativas de login de contas inativas imediatamente. Com menos problemas técnicos e maior segurança, Rafael pode focar em melhorias contínuas para o sistema.

Carlos Menezes tenta acessar o sistema com credenciais antigas, mas é bloqueado imediatamente pelo ADVO.NET.Tentativas de acesso suspeito são notificadas a Rafael, que toma as devidas providências. A segurança robusta do ADVO.NETimpede que Carlos consiga informações ou cause qualquer dano ao escritório.

Com a implementação do ADVO.NET, o escritório de advocacia Almeida & Fernandes não só aprimorou a eficiência e agilidade na gestão de processos, como também ofereceu uma experiência muito mais satisfatória e segura para clientes e colaboradores

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

-O Usuário pode adicionar e modificar os processos

-O Administrador deve ser capaz de visualizar todos os processos

-O cliente deve ser capaz de visualizar apenas os processos em que está adicionado

-O escritório pode criar seu próprio perfil e adicionar clientes a processos

-O Cliente deve poder acompanhar a situação do seu processo

-Os processos devem ser armazenados no banco de dados do escritório

-O Admimistrador organizar da maneira que preferir e até arquivar processos

-O Admimistrador pode ver processos antigos e arquivados no banco de dados

-Os escritórios podem acessar o banco de dados em qualquer momento

-O aplicativo deve enviar alertas e notificações automáticas sobre atualizações de processos tanto para clientes quanto para funcionários.

***2.2. Requisitos Não Funcionais***

-O sistema deve ser intuitivo e fácil de usar por todos os tipos de usuários.

-O tempo de resposta do sistema deve ser rápido, mesmo com um grande volume de dados.

-O sistema deve ser robusto e evitar falhas ou perdas de dados.

-Deve funcionar em diversos dispositivos e sistemas operacionais.

-O sistema deve poder crescer e se adaptar conforme a demanda aumenta.

-Facilitar a manutenção e atualização do sistema com códigos bem documentados.

-Além da funcionalidade, deve incluir criptografia e outros métodos para garantir a confidencialidade e integridade dos dados.

-Acessibilidade: Deve ser acessível a pessoas com diferentes necessidades, incluindo recursos de acessibilidade.

-A aplicação deve ser facilmente transferível para diferentes ambientes de hardware e software.

-Prover documentação abrangente e suporte técnico para os usuários do sistema.

***2.3. Perguntas***

Como você atualmente adiciona e modifica processos em seu escritório?

Quão importante é para você que seus clientes possam acompanhar a situação dos seus processos online?

Você vê valor em poder criar perfis personalizados do escritório e adicionar clientes a processos específicos?

Como a capacidade de organizar e arquivar processos da maneira que preferir impactaria sua rotina administrativa?

Quão crucial é para você que o sistema seja acessível em diversos dispositivos e sistemas operacionais?

Você ou sua equipe enfrentam algum desafio com sistemas atuais em termos de usabilidade ou acessibilidade?

Como você lida com necessidades de acessibilidade para membros da equipe ou clientes com diferentes necessidades?

Quão útil seria receber alertas e notificações automáticas sobre atualizações de processos?

Como a comunicação atual com seus clientes sobre o status dos processos poderia ser melhorada?

Quais são suas principais preocupações em relação à segurança e confidencialidade dos dados no gerenciamento de processos?

Como a robustez do sistema e a prevenção de falhas ou perdas de dados influenciam sua escolha de ferramentas digitais?

Quão importante é para você ter documentação abrangente e suporte técnico disponível?

Como a facilidade de manutenção e atualização do sistema impacta sua decisão de adotar uma nova tecnologia?

Você já enfrentou problemas com lentidão ou desempenho em sistemas com grande volume de dados?

Como a capacidade do sistema de crescer e se adaptar às demandas do seu escritório influencia sua adoção?

Quão valioso é para você que o sistema possa ser facilmente transferido para diferentes ambientes de hardware e software?

Você tem planos de mudar ou atualizar a infraestrutura tecnológica do seu escritório em breve?

Quais funcionalidades você considera indispensáveis em um sistema de gestão de processos jurídicos?

Você enxerga alguma limitação nos sistemas atuais que o advo.net poderia suprir?

Estaria disposto a testar um novo sistema que promete atender a essas necessidades? Por quê?

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
