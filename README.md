# Capa
Título do Projeto: Plataforma de Rotulagem Colaborativa de Imagens para Ensino de IA e Aprendizagem de Máquina (Label4Learn).<br>
Nome do Estudante: Lucas Henrique da Silva.<br>
Curso: Engenharia de Software - Centro Universitário - Católica de Santa Catarina – Jaraguá do Sul, SC – Brasil<br>
Data de Entrega: 29/10/2025<br>

# Resumo
&emsp;A Label4Learn é uma plataforma web colaborativa voltada ao ensino de Inteligência Artificial e Machine Learning, que permite a criação e rotulagem de imagens em sala de aula. O projeto busca superar a dependência de datasets prontos e repetitivos, oferecendo aos estudantes a oportunidade de vivenciar a etapa mais prática e demorada da Ciência de Dados — a rotulagem. Professores podem criar projetos personalizados e acompanhar a participação dos alunos, enquanto a turma colabora na construção de datasets originais que poderão ser usados em atividades e experimentos de IA. A proposta alia aprendizado ativo, colaboração e aplicação prática, promovendo uma formação mais completa e realista para futuros engenheiros de software na Ciência de Dados.
  
# 1. Introdução
&emsp;No contexto do ensino de Engenharia de Software e Inteligência Artificial, este projeto propõe o desenvolvimento de uma plataforma web de rotulagem colaborativa de imagens, voltada para o meio acadêmico, com foco em cursos de Inteligência Artificial e Machine Learning.
  
&emsp;A proposta surge da necessidade de superar a dependência de datasets prontos e repetitivos (como Iris, Titanic e MNIST), amplamente utilizados em sala de aula, mas que não oferecem aos alunos uma experiência prática sobre a etapa mais desafiadora e demorada da Ciência de Dados: a coleta e rotulagem de dados originais.<br>
&emsp;Essa etapa é fundamental, pois a qualidade e a eficiência do processo de rotulagem impactam diretamente o desempenho dos modelos de Machine Learning — sendo impossível alcançar alta acurácia se os dados de treinamento não forem bem rotulados.
  
&emsp;Com a plataforma, professores poderão criar projetos de rotulagem específicos para suas disciplinas, enquanto os alunos, de forma colaborativa, participarão do processo de anotação. O resultado será a geração de datasets inéditos e contextualizados, que poderão ser utilizados em atividades práticas de treinamento e avaliação de modelos de IA.<br>
&emsp;Nesse sentido, a proposta busca aproximar o estudante do processo real de preparação de dados, permitindo vivenciar de forma prática a importância da qualidade dos rótulos na construção de modelos de IA mais precisos e confiáveis.
  
# 2. Descrição do Projeto
&emsp;O Label4Learn é uma plataforma web inovadora na linha de projetos com Inteligência Artificial (IA), que integra conceitos de Machine Learning e Ciência de Dados aplicados ao contexto educacional. Seu objetivo é proporcionar uma experiência prática e colaborativa no ensino de IA, permitindo que professores e alunos participem ativamente da criação de datasets personalizados.<br>

&emsp;O projeto consiste em uma Plataforma de Rotulagem Colaborativa de Imagens, na qual professores podem criar projetos específicos de rotulagem de imagens, e os alunos colaboram na anotação dos dados. Isso possibilita a geração de datasets originais, contextualizados e voltados para atividades práticas de IA, superando a dependência de conjuntos de dados prontos e genéricos, como MNIST, Iris ou Titanic.<br>

&emsp;Na prática, os professores podem desenvolver projetos de rotulagem em diversas áreas, como classificação de plantas, frutas, objetos ou resíduos, e os alunos participam colaborativamente, realizando a anotação de imagens que comporão datasets inéditos. Esses dados podem ser exportados para treinar e avaliar modelos de Machine Learning, tornando o aprendizado mais completo, participativo e próximo da realidade profissional em Ciência de Dados.<br>

&emsp;O público-alvo do Label4Learn inclui professores e estudantes de graduação em Engenharia de Software, Ciência da Computação, Sistemas de Informação e áreas correlatas, além de instituições de ensino técnico e superior que oferecem disciplinas de Inteligência Artificial e Machine Learning. Pesquisadores e iniciantes em IA que necessitam criar seus próprios datasets acadêmicos também se beneficiam da plataforma.<br>

&emsp;O projeto busca resolver problemas comuns no ensino de IA, como a dependência de datasets genéricos, a falta de vivência prática na coleta e rotulagem de dados e a dificuldade de professores em criar atividades colaborativas e reais sobre preparação de dados. Atualmente, não existem ferramentas educacionais que combinem aprendizado ativo com prática de rotulagem em sala de aula de forma acessível e didática.<br>

&emsp;O diferencial do Label4Learn está em sua concepção voltada especificamente para o ambiente educacional. Ao contrário de plataformas comerciais como Labelbox ou Supervisely, a Label4Learn permite a rotulagem colaborativa, prioriza simplicidade e usabilidade didática, e incentiva o aprendizado do ciclo completo de Machine Learning, da coleta de dados ao treinamento de modelos. A plataforma também terá caráter open source, facilitando sua adoção em diferentes instituições de ensino.<br>

&emsp;O MVP será inicialmente restrito à rotulagem de imagens, sem suporte a texto, áudio ou vídeo, e não incluirá integração direta com APIs externas de IA. A validação ocorrerá em ambiente acadêmico controlado, com grupos limitados de alunos, sendo seu uso voltado exclusivamente para fins educacionais e de pesquisa.<br>

&emsp;Do ponto de vista legal e ético, a plataforma seguirá a LGPD, utilizando apenas imagens de domínio público ou autorizadas e sem coleta de dados pessoais sensíveis. A acessibilidade será considerada de acordo com as WCAG, garantindo interfaces intuitivas e acessíveis, e a utilização de imagens seguirá diretrizes éticas em pesquisa acadêmica.<br>

&emsp;O sucesso do projeto será avaliado por meio de métricas objetivas, como o número de usuários ativos, quantidade de imagens rotuladas por projeto, tempo médio de rotulagem, taxa de concordância entre rótulos, feedback de usabilidade e satisfação dos usuários, além da aplicabilidade dos datasets gerados em projetos acadêmicos de IA.<br>

# 3. Especificação Técnica
## 3.1 Requisitos de Software
### Requisitos Funcionais (RF)
| Código | Descrição                                                                                                          | Prioridade |
| :----- | :----------------------------------------------------------------------------------------------------------------- | :--------- |
| RF01   | Permitir o cadastro e autenticação de usuários (professores e alunos).                                             | Alta       |
| RF02   | Permitir que professores criem projetos de rotulagem de imagens.                                                   | Alta       |
| RF03   | Permitir que alunos participem de projetos e realizem a rotulagem de imagens.                                      | Alta       |
| RF04   | Permitir a visualização e o acompanhamento do progresso da rotulagem.                                              | Média      |
| RF05   | Permitir o download/exportação dos datasets rotulados em formato CSV.                                              | Alta       |
| RF06   | Exibir estatísticas básicas do projeto (quantidade de imagens rotuladas, participantes, acurácia de concordância). | Média      |

### Requisitos Não-Funcionais (RNF)
| Código | Descrição                                                                            | Categoria        |
| :----- | :----------------------------------------------------------------------------------- | :--------------- |
| RNF01  | A aplicação deve ser acessível via navegador web responsivo.                         | Usabilidade      |
| RNF02  | O sistema deve suportar ao menos 50 usuários simultâneos.                            | Desempenho       |
| RNF03  | As imagens e rótulos devem ser armazenados em banco de dados seguro e versionado.    | Segurança        |
| RNF04  | As ações críticas (criação, edição, exclusão de projetos) devem exigir autenticação. | Segurança        |
| RNF05  | O tempo médio de carregamento das páginas não deve exceder 2 segundos.               | Desempenho       |
| RNF06  | O código deve seguir boas práticas de clean code e arquitetura modular (MVC).        | Manutenibilidade |
| RNF07  | A interface deve ser intuitiva e acessível, seguindo diretrizes básicas da WCAG.     | Usabilidade      |

### Representação dos Requisitos
O diagrama de casos de uso principal envolve três atores:
- Professor → cria e gerencia projetos.
- Aluno → realiza a rotulagem das imagens.
- Sistema → armazena, valida e exporta os dados rotulados.

Fluxo resumido:
- Professor cria projeto → adiciona imagens → define classes/rótulos → alunos acessam → rotulam → professor revisa → exporta dataset final.

### Aderência à Linha de Projeto – Projetos com IA
O projeto atende integralmente aos requisitos obrigatórios da linha:
- Aplica conceitos de Machine Learning e Data Labeling, parte essencial do ciclo de IA.
- Promove aprendizado prático de coleta e rotulagem de dados, essencial à Engenharia de Software aplicada à IA.

## 3.2 Considerações de Design
### Visão Inicial da Arquitetura
A arquitetura segue o padrão MVC (Model-View-Controller) com as seguintes camadas:
- Frontend (View): Interface web interativa em ReactJS.
- Backend (Controller): API em Flask (Python) responsável pela lógica de negócios e controle de fluxo.
- Banco de Dados (Model): PostgreSQL para armazenamento estruturado das informações de usuários, imagens e rótulos.
- Storage: AWS S3 (ou alternativa local) para armazenamento das imagens.

### Padrões de Arquitetura
- MVC – separação clara entre apresentação, controle e dados.
- RESTful API – comunicação entre frontend e backend.
- Arquitetura em Camadas – modularidade e facilidade de manutenção.

### Decisões e Alternativas Consideradas
- Flask foi escolhido pela simplicidade, integração com IA e fácil hospedagem acadêmica.
- React foi escolhido para melhor experiência visual e interação fluida.
- Alternativas descartadas: Django (mais robusto, mas pesado para MVP) e Vue.js (menor domínio técnico da equipe).

### Critérios de Escalabilidade, Resiliência e Segurança
- Deploy em ambiente escalável (Docker + Render ou Railway).
- Banco de dados com backup automático e controle de versão.
- Controle de acesso baseado em função (professor/aluno).
- Criptografia de senhas com bcrypt.
- Validação de entrada e sanitização de dados conforme OWASP Top 10.

## 3.3 Stack Tecnológica
| Categoria          | Tecnologia              | Justificativa                                          |
| :----------------- | :---------------------- | :----------------------------------------------------- |
| Linguagem Backend  | **Python (Flask)**      | Simplicidade e ampla integração com bibliotecas de IA. |
| Frontend           | **ReactJS**             | Framework moderno, responsivo e eficiente.             |
| Banco de Dados     | **PostgreSQL**          | Confiável, open source e robusto.                      |
| Armazenamento      | **AWS S3 / Cloudinary** | Gerenciamento de imagens e escalabilidade.             |
| Controle de Versão | **Git + GitHub**        | Colaboração e versionamento.                           |
| IDE                | **VS Code**             | Leve, multiplataforma e produtiva.                     |
| Design             | **Figma**               | Criação de mockups interativos.                        |
| Hospedagem         | **Render / Railway**    | Deploy gratuito e escalável para MVP.                  |

Licenciamento:
- Todas as tecnologias são open source (MIT, Apache 2.0, ou equivalentes).

## 3.4 Considerações de Segurança
### Riscos Identificados
- Injeção de código (SQL Injection, XSS).
- Vazamento de credenciais.
- Upload indevido de arquivos não permitidos.
- Exposição indevida de dados de usuários.

### Medidas de Mitigação
- Sanitização e validação de todas as entradas.
- Autenticação segura (JWT ou Flask-Login).
- Criptografia de senhas com bcrypt.
- Controle de permissões baseado em função (RBAC).
- Armazenamento de imagens apenas em ambientes restritos.

### Normas e Boas Práticas Seguidas
- OWASP Top 10 (prevenção de vulnerabilidades web).
- LGPD (proteção e uso ético de dados).
- Princípios de Ética em IA (UNESCO / OECD).

### Responsabilidade Ética
- Os dados utilizados (imagens) serão obtidos de bases de domínio público ou gerados academicamente.
- O sistema não processará dados pessoais, respeitando a privacidade, consentimento e finalidade educacional.

## 3.5 Conformidade e Normas Aplicáveis
| Norma / Lei                    | Aplicação no Projeto                                                                           |
| :----------------------------- | :--------------------------------------------------------------------------------------------- |
| **LGPD (Lei nº 13.709/2018)**  | Coleta mínima de dados pessoais; uso acadêmico restrito; política de consentimento e exclusão. |
| **WCAG 2.1**                   | Diretrizes básicas de acessibilidade na interface.                                             |
| **OWASP Top 10**               | Prevenção contra vulnerabilidades web comuns.                                                  |
| **UNESCO – Ética em IA**       | Compromisso com uso educacional e não discriminatório de dados.                                |
| **Creative Commons (imagens)** | Uso de imagens livres de direitos autorais.                                                    |

# 4. Próximos Passos
## 4.1. Visão Geral

O projeto Label4Learn será desenvolvido em duas etapas principais — Portfólio I e Portfólio II — correspondendo ao ciclo completo de concepção, implementação e validação da solução.<br>
O foco inicial será construir um MVP funcional (mínimo produto viável) voltado à rotulagem colaborativa de imagens no contexto acadêmico, garantindo base sólida para expansão futura.

## 4.2. Portfólio I – Planejamento e Prototipagem (Semestre Atual)
Objetivo geral: Estruturar os fundamentos conceituais, técnicos e visuais da plataforma.
| Mês / Etapa                  | Descrição da Atividade                                                                      | Entregável                                            |
| :--------------------------- | :------------------------------------------------------------------------------------------ | :---------------------------------------------------- |
| **Outubro**                  | Finalização do RFC e definição dos requisitos funcionais e não funcionais.                  | Documento RFC completo e validado.                    |
| **Outubro – Novembro**       | Desenvolvimento dos mockups no Figma e estruturação do design do sistema (arquitetura MVC). | Protótipo navegável e diagrama de arquitetura.        |
| **Novembro**                 | Implementação inicial do backend (API Flask) e configuração do banco de dados.              | API base funcional e conexão com PostgreSQL.          |
| **Dezembro**                 | Integração com o frontend (ReactJS) e teste das rotas principais.                           | MVP funcional: criação de projeto e rotulagem básica. |
| **Encerramento Portfólio I** | Apresentação do MVP parcial e relatório técnico intermediário.                              | Apresentação + relatório técnico parcial.             |

## 4.3. Portfólio II – Implementação, Testes e Entrega Final
Objetivo geral: Consolidar o MVP, incluir funcionalidades complementares e validar o uso em contexto acadêmico.
| Mês / Etapa | Descrição da Atividade                                                            | Entregável                                     |
| :---------- | :-------------------------------------------------------------------------------- | :--------------------------------------------- |
| **Março**   | Revisão da arquitetura e integração com armazenamento de imagens (S3 ou similar). | Sistema completo com upload de imagens.        |
| **Abril**   | Implementação da área do professor e módulo de estatísticas.                      | Painel administrativo e controle de rotulagem. |
| **Maio**    | Testes de usabilidade com turmas piloto e ajustes na interface.                   | Relatório de testes e refinamento do sistema.  |
| **Junho**   | Preparação da documentação final e defesa do projeto.                             | Relatório final + demonstração funcional.      |

## 4.4. Marcos de Acompanhamento (Checkpoints)
| Marco                                 | Descrição                                                | Data Prevista |
| :------------------------------------ | :------------------------------------------------------- | :------------ |
| **M1 – RFC Validado**                 | Entrega e aprovação do documento RFC completo.           | Outubro/2025  |
| **M2 – Mockup e Arquitetura Prontos** | Protótipo navegável e definição da arquitetura técnica.  | Novembro/2025 |
| **M3 – MVP Básico**                   | Plataforma com rotulagem de imagens funcional.           | Dezembro/2025 |
| **M4 – MVP Expandido**                | Sistema completo com painel do professor e estatísticas. | Abril/2026    |
| **M5 – Testes Acadêmicos**            | Uso piloto com estudantes em disciplina de IA.           | Maio/2026     |
| **M6 – Entrega Final / Defesa**       | Relatório técnico e demonstração funcional.              | Junho/2026    |

## 4.5. Próximos Passos Imediatos
- Finalizar e submeter o RFC à validação do orientador.
- Desenvolver os mockups e o diagrama de arquitetura inicial (C4 e casos de uso).
- Configurar ambiente de desenvolvimento (GitHub, Flask, PostgreSQL e React).
- Iniciar implementação do backend e integração básica para criação e rotulagem de imagens.

# 5. Referências
