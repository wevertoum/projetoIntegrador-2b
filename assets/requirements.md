#### Requisitos Funcionais (o que o sistema faz)

1. O organizador (Lucas) deve poder fazer login na plataforma.
2. O organizador deve cadastrar um evento com nome, data, número de vagas, valor da inscrição e configuração de quartos (N quartos, N leitos por quarto, gênero).
3. O acampante (Ana) deve se cadastrar na plataforma com nome, e-mail e gênero antes de participar de eventos.
4. O acampante deve acessar o evento por um link e visualizar suas informações (nome, data, vagas, valor).
5. O acampante deve se inscrever no evento, informando forma de pagamento, e escolher um leito em um quarto compatível com seu gênero.
6. O sistema deve exibir os quartos disponíveis, leitos livres e nomes dos ocupantes durante a escolha.
7. O sistema deve verificar se há vagas e leitos disponíveis antes de confirmar a inscrição.
8. O sistema deve enviar um e-mail de confirmação ao acampante após a inscrição, incluindo detalhes do quarto e leito.
9. O organizador deve visualizar a lista de inscritos, com quartos e leitos ocupados, e exportá-la em formato CSV.
10. O supervisor (Pastor João) deve visualizar os detalhes do evento, lista de inscritos e ocupação dos quartos.
11. O sistema deve enviar lembretes automáticos por e-mail aos acampantes alguns dias antes do evento.

#### Requisitos Não Funcionais (restrições)

1. O sistema deve ser acessível por navegadores web (Chrome, Firefox).
2. A interface deve ser simples e intuitiva para usuários com pouca experiência tecnológica.
3. O sistema deve responder em até 3 segundos para ações como inscrição, cadastro ou escolha de leito.
4. Os dados devem ser armazenados com segurança (ex.: senhas criptografadas, gênero protegido).
5. O sistema deve garantir que acampantes só escolham quartos compatíveis com seu gênero registrado.
