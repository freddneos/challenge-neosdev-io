## Desafio NeosDev.IO

### Desafio para Trainees NeosDev.io (Consultoria de Desenvolvimento de Produtos de Software e MVPs)

Desenvolver um gerador de links para o WhatsApp que seja funcional, permitindo que ao ser clicado, abra o aplicativo WhatsApp ou WhatsApp Web (dependendo de onde for aberto o link, seja em um smartphone ou navegador web), iniciando uma nova conversa.

### Requisitos Funcionais

- Permitir a inserção do número de telefone (+351999999999) ou (+552199999999).
- Digitar a mensagem no formato de texto simples.
- Ter um botão "Gerar Link".
- Exibir o link gerado na tela (ou através de um Alert/Modal) para que o usuário possa copiá-lo.
- Exibir uma lista de links gerados por aquele usuário (salvos no local storage).
- Permitir a exclusão dos links salvos.

### Requisitos Técnicos

- Desenvolver a aplicação utilizando React + JavaScript com Vite.
- Utilizar hooks.
- Utilizar State.
- Utilizar Git e GitHub.
- Ser uma SPA (Single Page Application).
- Escrever código bem escrito e organizado.
- Utilizar Material UI ou Tailwind CSS para estilização.

### Regras

- É permitido utilizar o ChatGPT.
- É permitido buscar ajuda externa (apenas ajuda, sem que façam o trabalho por você).

### O que Será Avaliado

- Entrega dentro do prazo.
- Código funcional, sem bugs.
- Design bem elaborado.
- Projeto entregue através do GitHub (repositório público com o código do projeto).

### Avaliação

- Se o seu código for avaliado positivamente, você passará para a próxima etapa do processo.
- Live Coding (uma sessão ao vivo onde você explicará o que fez, o porquê fez e eu solicitarei ajustes para serem feitos junto comigo online).
- Portanto, fique atento ao uso da inteligência artificial, pois haverá Live Coding!

### Como Gerar um Link

    https://api.whatsapp.com/send?phone=SEUNUMERO.
    
    Lembre-se de incluir o código do país e do estado ao digitar seu número.
    
    Para criar um link com mensagem automática:
    Se deseja adicionar uma mensagem automática que será exibida quando alguém abrir o link, 
    inclua "&text=SuaMensagem" ao final da URL. 
    
    Veja como fica: https://api.whatsapp.com/send?phone=SEUNUMERO&text=SuaMensagem.
    
    Substitua "SuaMensagem" pelo texto desejado. Caso a mensagem contenha espaços, 
    substitua-os pelo código "%20".

    
## Sugestão de Design :
### Apenas sugestão pode ser feito de outra forma qualquer dentro dos requisitos funcionais :

<img width="1170" alt="image" src="https://github.com/freddneos/challenge-neosdev-io/assets/36821426/e0f32e12-1707-435f-bdbc-001995018f68">


