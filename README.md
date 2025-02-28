## Pesquisa Cognitiva Usando a Azure IA.
###     Feito por Kewen Wesley.

🔍 Configuração da Pesquisa Cognitiva no Azure

Este documento descreve o passo a passo para configurar uma pesquisa cognitiva no Azure, além de apresentar insights, ferramentas que se beneficiam dessa tecnologia e aprendizados adquiridos ao longo do processo.

📌 Passo a Passo para Configurar uma Pesquisa Cognitiva no Azure

## 1️⃣ Criando um Serviço de Pesquisa Cognitiva

Acesse o Portal do Azure.

Clique em Criar um recurso.

Pesquise por Pesquisa Cognitiva do Azure e selecione a opção.

Clique em Criar e preencha os campos necessários:

Grupo de Recursos: Escolha um grupo existente ou crie um novo.

Nome do Serviço: Escolha um nome único.

Localização: Escolha uma região próxima para melhor desempenho.

Plano de Preço: Selecione Free para fins de teste.

Clique em Revisar + Criar e finalize a criação.

Após a implantação, copie a Chave de Administração e o Endpoint da API.

## 2️⃣ Criando um Índice de Pesquisa

Acesse o serviço de Pesquisa Cognitiva criado no portal.

Vá até a aba Índices e clique em Adicionar Índice.

Defina os campos principais, como:

id (chave primária)

titulo (campo pesquisável)

conteudo (texto completo pesquisável)

data_criacao (data do documento)

Salve as configurações e crie o índice.

## 3️⃣ Criando uma Fonte de Dados

Vá até a aba Origem de Dados.

Selecione a fonte de dados, como Armazenamento do Azure ou Banco de Dados SQL.

Configure a conexão com a origem e associe-a ao índice criado.

## 4️⃣ Criando um Skillset (Enriquecimento de IA)

Vá para Skillsets e clique em Criar.

Adicione habilidades de IA, como:

Extração de texto de imagens e PDFs.

Análise de sentimentos.

Detecção de entidades e palavras-chave.

Salve as configurações.

## 5️⃣ Criando um Indexador

Vá para Indexadores e clique em Criar.

Escolha a fonte de dados e o índice criado.

Defina a periodicidade da indexação.

Salve e inicie a indexação.

💡 Insights e Possibilidades

# 1️⃣ Aplicações Práticas

✅ Empresas de Documentação: Melhoria na busca de documentos internos.
✅ E-commerce: Melhor experiência de busca para produtos e recomendações.
✅ Setor Jurídico: Pesquisa otimizada em processos e contratos.
✅ Chatbots Inteligentes: Respostas mais precisas usando bases de conhecimento.

# 2️⃣ Ferramentas que se Beneficiam

🔹 Sistemas de Gestão de Conteúdo (CMS) → Melhor busca de artigos e documentos.
🔹 Portais Acadêmicos → Agiliza a busca de artigos científicos e materiais.
🔹 Suporte ao Cliente → Respostas rápidas baseadas em FAQ e documentos internos.

📊 Aprendizados Durante o Processo

🔹 A busca tradicional não é suficiente para grandes volumes de dados.
🔹 A IA melhora a pesquisa ao extrair contexto e significado dos textos.
🔹 O Azure facilita a integração com outros serviços e APIs.
🔹 Configurar corretamente os campos do índice impacta diretamente na qualidade dos resultados.

🚀 Próximos Passos

📌 Explorar a API da Pesquisa Cognitiva para buscar dados programaticamente.
📌 Criar um front-end para consumir os resultados da pesquisa de maneira intuitiva.
📌 Testar diferentes técnicas de enriquecimento de IA para melhorar os resultados.

