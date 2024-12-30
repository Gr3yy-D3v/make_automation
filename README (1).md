
# Automação de Análise de Sentimento e Dicas de Melhoria


Este projeto automatiza a análise de feedbacks de clientes, utilizando a **API da OpenAI** para classificar sentimentos (positivo, negativo ou neutro) e gerar sugestões de melhoria para os aspectos mencionados nos feedbacks negativos ou neutros. O fluxo também permite que o feedback seja direcionado para as equipes apropriadas.


# Como Funciona a Lógica

A automação segue os seguintes passos:

1. **Recepção do Feedback**: O feedback do cliente é coletado a partir de um **Google Form** (ou outra fonte configurada).

2. **Análise de Sentimento**: O feedback é enviado para a OpenAI para classificar o sentimento (positivo, negativo ou neutro).

3. **Sugestões de Melhoria**: Se o feedback for negativo ou neutro, a IA gera sugestões práticas para melhorar o aspecto mencionado no feedback.

4. **Roteamento**: Com base na análise de sentimento, o feedback é enviado para a equipe correta:
- **Feedback Positivo**: Direcionado para equipes de Marketing ou Vendas.
- **Feedback Negativo**: Direcionado para Suporte ou Qualidade, com as sugestões de melhoria.
- **Feedback Neutro**: Pode ser direcionado para Pesquisa de Mercado ou Análise de Dados.

# Instruções para abrir o projeto no make
1. **Clonar o Repositório**:
- Clone o repositório para o seu computador ou faça o download do arquivo ````blueprint.json```` do projeto.
2. **Acessar o Make**:
- Acesse a plataforma **Make** em https://www.make.com.
3. **Criar um Novo Cenário**:
- No painel principal do Make, clique em "**Criar um novo cenário**" para iniciar um novo projeto.
4. **Importar o Blueprint**:
- Na tela de criação de cenário, vá até o canto inferior direito e clique nos **três pontinhos** (configurações).
- Selecione a opção "**Importar**".
- No campo de importação, escolha o arquivo ````blueprint.json```` que você clonou ou baixou.
5. **Configuração Final**:
- Após a importação, o Make irá carregar todos os módulos e configurações definidas no blueprint.
- Conecte suas contas necessárias (Google Forms, OpenAI, etc.) e revise os módulos para garantir que tudo está configurado corretamente.
- Execute o cenário para começar a processar os feedbacks!