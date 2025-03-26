# Azure Cognitive Search - Guia de Configuração

Para realizar uma pesquisa eficaz com o Azure Cognitive Search, precisamos seguir três etapas principais: Ingestão, Enriquecimento com IA e Exploração.

## Passos para Configurar a Busca

### 1. Abrir o Portal Azure
### 2. Acessar o Recurso Azure Services

### 3. Criar um AI Search:
- Atribuir um nome único
- Selecionar o plano básico (para teste)
- Selecionar a localização
- Clicar em "Review + Create"

### 4. Criar um Azure AI Service:
- Criar recurso
- AI + Machine Learning
- Azure AI Services:
  - Selecionar o plano de inscrição no portal
  - Nome do grupo
  - Região
  - Nome do laboratório
  - Preço gratuito
  - Clicar em "Review + Create"

### 5. Criar uma Storage Account:
- Clique em "Create"
- Básico:
  - Selecionar o plano de inscrição no portal
  - Nome do grupo
  - Região
  - Nome do laboratório (deve ser único e ter entre 3 a 20 caracteres)
  - Performance padrão (para teste)
  - Redundância do storage (LRS)
  - Clicar em "Review + Create"

### 6. Configurar o Storage Account:
- Vá em "Settings" e habilite o acesso anônimo ao blob
- Salvar

### 7. Criar um Container:
- Crie um nome
- Selecione "Container (Anonymous read access for container and blobs)"

### 8. Carregar os Arquivos no Container

### 9. Importar os Dados no AI Search:
- Abra o AI Search e importe os dados do seu Storage Account
- Selecione o tipo de informações que deseja extrair dos documentos

## Resumo

Basicamente, é necessário criar um serviço de inteligência artificial, fazer o link com a automação e, a partir disso, direcionar para um repositório. Isso permitirá fazer buscas de forma rápida e eficiente.

