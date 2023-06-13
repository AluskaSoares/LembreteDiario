# LembreteDiarioBackend API - Lembretes
Esse projeto é uma API web simples para criar lembretes para uso do dia a dia. Os usuários podem enviar detalhes sobre o determinado lembrete por meio de solicitações POST e as informações enviadas são exibidas em uma página HTML para visualização e referência.


Pré-requisitos
Node.js instalado;
Gerenciador de pacotes npm;

Como executar o projeto
Clone o repositório para sua máquina local.
É necessário navegar até o diretório raiz do projeto.
Instale as dependências do projeto executando o comando npm install.
Também é necessário que o servidor esteja executando o comando npm start.

Agora acesse o aplicativo no seu navegador em http://localhost:3002.

Funcionalidades
Exibe os detalhes do lembrete em uma página web após o envio da solicitação POST.
Também permite solicitações POST com os detalhes do lembrete, como data, hora, minuto e frequência do lembrete (se vai lembrar apenas uma vez na semana ou mais de uma vez) 

Como usar
Use uma ferramenta de API, como o Postman, para enviar uma solicitação POST para http://localhost:3002/dados com os seguintes dados no corpo da solicitação:
-Lembrete: Nome do lembrete
-Data: data do lembrete
-Hora: hora do lembrete
-Minuto: minuto do lembrete
-Frequência: frequência semanal do lembrete 

Após enviar a solicitação POST, você receberá uma resposta com os detalhes do lembrete em uma página web.

Dupla
Aluska Soares(@AluskaSoares)
Igor Silva(@igorslira)
