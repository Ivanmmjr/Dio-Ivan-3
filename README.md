Controle e Versionamento de Código no Azure Databricks

Este README documenta o processo de controle de versão e integração com Git em notebooks do Azure Databricks. É destinado a auxiliar equipes de dados, engenheiros e analistas na organização e rastreabilidade de seus códigos.

📁 1. Histórico de Versões Interno do Notebook

O Azure Databricks salva automaticamente versões anteriores de notebooks.

Como acessar:

Abra o notebook desejado

Clique no ícone de "Revision History" na barra lateral direita



Recursos:

Comparar diferenças entre versões

Restaurar versões anteriores

Ver autores e datas de modificação

🔍 2. Integração com Git (Repos)

O Databricks permite integrar repositórios Git, como GitHub, Azure DevOps, GitLab e Bitbucket.

Configuração:

Acesse User Settings > aba Git Integration

Escolha seu provedor Git e conecte sua conta



Clonar um Repositório:

Acesse Repos no menu lateral

Clique em Clone Repo e insira a URL do repositório



Operações Git Disponíveis:

Criar/alternar branches

Commit de notebooks com mensagem

Pull/push para o repositório remoto



⚖️ 3. Fluxo de Trabalho Recomendado

1. Clone o repo Git no Databricks
2. Crie uma branch de feature
3. Edite e salve o notebook
4. Commit com mensagem clara
5. Pull para garantir sincronização
6. Push para o repositório remoto
7. Crie um Pull Request no GitHub/Azure DevOps

💡 4. Boas Práticas

Sempre vincule notebooks a repositórios Git

Use mensagens de commit claras e consistentes

Evite edições simultâneas em notebooks compartilhados

Faça pull antes de editar

Utilize branches para novas funcionalidades e correções

📄 Recursos

Documentação oficial: Databricks Repos

Integração Git: Version Control Notebooks
