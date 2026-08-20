\# Creative OS — Codex Operating Rules



\## Objetivo do repositório



Este repositório é o sistema pessoal de organização e produção de João-oBarros.



Ele deve concentrar, organizar e versionar:



\* projetos criativos;

\* projetos acadêmicos;

\* conhecimento;

\* agentes de IA;

\* prompts;

\* templates;

\* portfólio;

\* recursos;

\* reuniões;

\* automações.



O Codex deve tratar este repositório como um sistema de longo prazo, priorizando organização, previsibilidade, segurança e facilidade de manutenção.



\---



\## Estrutura principal



A estrutura principal do repositório é:



\* `Agents/` — agentes de IA, instruções, conhecimentos e versões.

\* `Automation/` — scripts, fluxos e automações.

\* `Knowledge/` — biblioteca de conhecimento e estudos.

\* `Meetings/` — registros, pautas, decisões e materiais de reuniões.

\* `Portfolio/` — cases e materiais destinados ao portfólio.

\* `Projects/` — projetos profissionais, acadêmicos e pessoais.

\* `Prompts/` — biblioteca de prompts reutilizáveis.

\* `Resources/` — referências, recursos e materiais auxiliares.

\* `Templates/` — modelos reutilizáveis.

\* `README.md` — visão geral do Creative OS.

\* `AGENTS.md` — regras de operação do Codex.



Não alterar essa estrutura principal sem necessidade clara.



\---



\## Regras gerais



Antes de modificar qualquer arquivo:



1\. analisar o pedido;

2\. identificar quais arquivos serão afetados;

3\. preservar informações existentes;

4\. evitar alterações desnecessárias;

5\. verificar se existe um template ou padrão aplicável.



Quando houver dúvida entre criar uma nova estrutura ou utilizar uma existente, preferir reutilizar e adaptar a estrutura existente.



\---



\## Segurança de arquivos



Nunca:



\* excluir arquivos sem autorização explícita;

\* sobrescrever conteúdo importante sem necessidade;

\* mover grandes quantidades de arquivos sem justificar;

\* alterar arquivos fora deste repositório sem autorização;

\* armazenar senhas, tokens, chaves de API ou credenciais;

\* incluir informações privadas desnecessárias no Git.



Para mudanças potencialmente destrutivas, apresentar primeiro o que será alterado.



\---



\## Criação de arquivos



Utilizar nomes claros, previsíveis e descritivos.



Preferir:



`Briefing.md`



`Research.md`



`Positioning.md`



`Meeting-2026-08-19.md`



Evitar:



`arquivo1.md`



`novo.md`



`final-final.md`



`teste123.md`



Quando existirem várias versões relevantes, utilizar Git como histórico em vez de criar sucessivos arquivos `final-v2-final`.



\---



\## Markdown



Para documentação textual, utilizar Markdown sempre que não houver necessidade específica de outro formato.



Os documentos devem ter:



\* título claro;

\* hierarquia lógica de headings;

\* parágrafos legíveis;

\* listas apenas quando úteis;

\* linguagem direta;

\* estrutura fácil de navegar.



\---



\## Projetos



Cada projeto dentro de `Projects/` deve possuir uma pasta própria.



Estrutura recomendada:



`Projects/NomeDoProjeto/`



Dentro dela, quando aplicável:



\* `README.md`

\* `Briefing/`

\* `Research/`

\* `Strategy/`

\* `Brand/`

\* `Communication/`

\* `Meetings/`

\* `Deliverables/`

\* `Archive/`



Não criar todas essas pastas automaticamente se não forem necessárias.



A estrutura deve acompanhar a natureza real do projeto.



\---



\## Knowledge



`Knowledge/` deve funcionar como biblioteca pessoal.



Organizar prioritariamente por assunto, e não por origem do arquivo.



Exemplos:



\* Branding

\* Design

\* Advertising

\* Marketing

\* Communication

\* AI

\* Research

\* Books

\* Cases



Evitar duplicação de conteúdo.



Quando conteúdos diferentes abordarem o mesmo tema, considerar relacioná-los em vez de simplesmente copiá-los.



\---



\## Agents



Cada agente deve ter sua própria pasta:



`Agents/NomeDoAgente/`



Quando necessário, utilizar:



\* `README.md`

\* `Instructions.md`

\* `Knowledge/`

\* `Examples.md`

\* `Tests.md`

\* `Changelog.md`



As instruções devem separar claramente:



\* função do agente;

\* comportamento;

\* processo;

\* limites;

\* fontes de conhecimento;

\* exemplos.



\---



\## Templates



Templates devem ser genéricos e reutilizáveis.



Não incluir informações específicas de clientes ou projetos em templates globais.



Sempre que um template for utilizado em um projeto, criar uma cópia dentro do projeto antes de personalizá-lo.



\---



\## Portfólio



`Portfolio/` deve conter somente materiais que possam contribuir para apresentação profissional.



Não utilizar essa pasta como arquivo geral de projetos.



Projetos completos permanecem em `Projects/`.



O portfólio deve conter versões selecionadas, organizadas e preparadas para apresentação.



\---



\## Automação



Scripts devem:



\* possuir nomes claros;

\* ter comentários quando a lógica não for evidente;

\* evitar alterações destrutivas por padrão;

\* preferir modo de simulação quando uma operação envolver muitos arquivos;

\* registrar erros de forma compreensível.



Nunca armazenar credenciais diretamente nos scripts.



\---



\## Uso do Git



Antes de grandes alterações:



1\. verificar `git status`;

2\. entender o estado atual;

3\. evitar misturar mudanças não relacionadas.



Commits devem representar alterações coerentes.



Mensagens de commit devem explicar a mudança.



Exemplos:



`Add project template structure`



`Create branding knowledge index`



`Update Brand Strategist agent instructions`



Evitar:



`update`



`changes`



`teste`



\---



\## Comportamento esperado do Codex



O Codex deve agir como mantenedor técnico e organizacional deste sistema.



Pode:



\* criar arquivos;

\* editar arquivos;

\* organizar diretórios;

\* criar scripts;

\* padronizar estruturas;

\* detectar duplicações;

\* sugerir melhorias;

\* documentar sistemas;

\* automatizar tarefas repetitivas.



Não deve transformar espontaneamente o repositório inteiro.



Mudanças estruturais amplas devem ser propostas antes de executadas.



\---



\## Princípio central



O Creative OS deve continuar compreensível mesmo sem o Codex.



Automação não deve substituir organização.



Complexidade só deve ser adicionada quando resolver um problema real.



