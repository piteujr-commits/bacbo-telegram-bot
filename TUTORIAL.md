# Tutorial Detalhado: Como Importar do GitHub para o SquareCloud

Este tutorial passo a passo vai te mostrar como importar o repositório do bot Bac Bo do GitHub para o SquareCloud, com capturas de tela para cada etapa.

## Passo 1: Criar uma conta no GitHub (se ainda não tiver)

1. Acesse [github.com](https://github.com)
2. Clique em "Sign up" no canto superior direito
3. Siga as instruções para criar sua conta usando o email dasnevesedimilson5@gmail.com

## Passo 2: Criar um novo repositório no GitHub

1. Após fazer login, clique no ícone "+" no canto superior direito
2. Selecione "New repository"
3. Preencha as informações:
   - Nome do repositório: `bacbo-telegram-bot`
   - Descrição: `Bot para enviar sinais do jogo Bac Bo para o Telegram`
   - Visibilidade: Public
4. Clique em "Create repository"

## Passo 3: Fazer upload dos arquivos para o GitHub

1. Na página do repositório recém-criado, você verá uma área para upload
2. Clique em "uploading an existing file"
3. Arraste todos os arquivos que enviei para você ou use o seletor de arquivos
4. Clique em "Commit changes"

## Passo 4: Acessar a SquareCloud

1. Acesse [squarecloud.app](https://squarecloud.app)
2. Faça login na sua conta
3. No painel principal, clique em "Criar nova aplicação"

## Passo 5: Importar do GitHub para a SquareCloud

1. Na tela de criação de aplicação, clique no botão "Importar do Github"
2. Se for a primeira vez, você precisará autorizar a SquareCloud a acessar seu GitHub:
   - Clique em "Authorize SquareCloud"
   - Confirme sua senha do GitHub se solicitado
3. Selecione o repositório `bacbo-telegram-bot` da lista
4. A SquareCloud detectará automaticamente as configurações do arquivo squarecloud.app
5. Clique em "Enviar" para finalizar a importação

## Passo 6: Verificar a implantação

1. Após a importação, você será redirecionado para o painel da aplicação
2. Aguarde alguns minutos enquanto a SquareCloud implanta sua aplicação
3. Quando o status mudar para "Online", sua aplicação estará funcionando
4. Verifique seu grupo do Telegram para confirmar que está recebendo os sinais

## Solução de problemas comuns

### Se a aplicação não iniciar:
- Verifique os logs na aba "Logs" do painel da SquareCloud
- Certifique-se de que todos os arquivos foram corretamente enviados para o GitHub
- Verifique se o arquivo squarecloud.app está na raiz do repositório

### Se não receber mensagens no Telegram:
- Verifique se o bot está adicionado ao grupo
- Confirme se o bot tem permissões de administrador no grupo
- Verifique se o ID do chat está correto no código

## Próximos passos

Após a implantação bem-sucedida, o sistema enviará resultados do jogo Bac Bo para seu grupo do Telegram a cada 60 segundos, 24 horas por dia, 7 dias por semana.
