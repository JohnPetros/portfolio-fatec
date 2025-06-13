# portfolio-fatec

Portfolio Fatec - João Pedro Carvalho dos Santos

Desenvolvedor Full-Stack e estudante do 3º semestre em Desenvolvimento de Sistemas na FATEC São José dos Campos - Prof. Jessen Vidal.

## Sobre mim

Técnico em Desenvolvimento de Sistemas na Etec - Professora Ilza Nascimento Pintus, graduando em Desenvolvimento de Software Multiplataforma na FATEC São José dos Campos e atualmente desenvolvedor Full Stack estagiário pela [Design Líquido](https://www.designliquido.com.br/).

Ao longo de dois anos de experiência profissional em desenvolvimento web e mobile, incluindo minha atuação como freelancer, desenvolvi e otimizei diversas soluções. Dentre elas, destaco a criação de um [blog de notícias](https://github.com/JohnPetros/pulo-do-gato-news) e um sistema de e-commerce completo [(site e aplicativo mobile)](https://github.com/JohnPetros/sertton). Nessas experiências, aprofundei meu conhecimento em aplicar conceitos técnicos com foco em SEO, UX e na implantação de sistemas em produção, além de explorar o desenvolvimento serverless.

Além disso, sou um entusiasta e colaborador ativo em projetos open source. Destaco minha participação no [Delégua](https://www.designliquido.com.br), uma linguagem de programação 100% em português baseada em TypeScript. Inclusive, utilizei o Delégua no meu TCC da ETEC, a plataforma [StarDust](https://github.com/JohnPetros/stardust), desenvolvida para o ensino de lógica de programação para iniciantes.

Estou sempre em busca de novos desafios que me permitam aplicar e expandir minhas habilidades em todo o stack de desenvolvimento, contribuindo para projetos inovadores e de impacto.

- LinkedIn
- Github
- Gmail

## Projetos

### Smart Farming

1º Semestre - 1/2024

Cliente: [Faculdade de Tecnologia de São José dos Campos](https://fatecsjc-prd.azurewebsites.net)

O Smart Farming é uma aplicação web desenvolvida para auxiliar o monitoramento de estufa inteligente mantida pela Fatec de São José dos Campos. Seu objetivo é simplificar a gestão, fornecendo ferramentas para a coleta e visualização de dados de sensores (como temperatura, umidade e pH), a execução de check-lists de manutenção, a geração de relatórios detalhados e o controle de acesso administrativo. Isso permite uma gestão mais eficiente e automatizada do ambiente agrícola controlado.

#### Principais funcionalidades

O aplicativo foi estruturado em três funcionalidades principais para atender aos objetivos propostos: 
- Gerenciamento de Sensores
- Checklist 
- Plantas

##### Gerenciamento de Sensores

A seção de Gerenciamento de Sensores oferece ao usuário controle total sobre os dados. É possível visualizar, editar e deletar informações captadas automaticamente pelos sensores ou inseri-las manualmente. Há também a opção de importar dados via arquivo CSV. Para uma análise aprofundada, os dados de umidade do ar (%), umidade do solo (%), temperatura (°C) e volume de água (mL) podem ser visualizados em um dashboard interativo contendo quatro gráficos.

##### Dashboard

<IMAGEM>

##### Formulário de registro coletado pelos sensores de forma manual

<IMAGEM>

##### Gerenciamento de Checklist

No Gerenciamento de Checklist, o usuário tem a flexibilidade de registrar novos dados através de um formulário interno, bem como editar, deletar e importar informações via arquivo CSV. Todos os registros podem ser facilmente visualizados em uma tabela paginada, facilitando a navegação e a consulta.

<IMAGEM>

##### Gerenciamento de Plantas

Por fim, no Gerenciamento de Plantas, o usuário pode administrar todas as plantas da estufa. É possível criar novos registros, editá-los, desativá-los quando necessário e visualizar a lista completa de plantas cadastradas.

<IMAGEM>

#### Arquitetura do Projeto

<IMAGEM>

O diagrama ilustra a arquitetura do sistema. Nele, dados de sensores da estufa são inicialmente armazenados em um MicroSD e, em seguida, enviados via requisições POST para o Backend da aplicação. O Frontend, acessível por administradores e outros usuários, permite a visualização desses dados em um Dashboard interativo, o registro de informações via formulário (incluindo checklists), e interage bidirecionalmente com o Backend para buscar e enviar dados. O Backend, por sua vez, é responsável por processar as requisições do Frontend e salvar/recuperar todas as informações do banco de dados MySQL, consolidando o fluxo de dados do sensor ao usuário final.

#### Tecnologias utilizadas

- [Flask](https://flask.palletsprojects.com/en/stable/): Framework escolhido para o desenvolvimento do servidor da aplicação (backend).
- [Docker](https://www.docker.com/): Essencial para a conteinerização do servidor e do banco de dados, facilitando a gestão do ambiente e a implantação.
HTML: Utilizado na estruturação dos templates da interface web.
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript): Empregado para adicionar interatividade e dinamismo à interface web.
- [ApexCharts](https://apexcharts.com/): Biblioteca implementada para a criação dos gráficos interativos presentes no dashboard.
- [Figma](https://www.figma.com/pt-br/): Ferramenta utilizada para o desenvolvimento e a prototipagem das wireframes do projeto.





