🔮 Adivinhe o Número (Guess the Number)
Este é um jogo clássico de adivinhação desenvolvido como um projeto full-stack leve, utilizando a hospedagem gratuita do Netlify e o banco de dados em tempo real Google Firestore (Firebase) para registrar os recordes.

O objetivo é simples: adivinhar um número secreto entre 1 e 100 com o menor número de tentativas possível. Você tem um limite de 10 chances.

🚀 Acesso Rápido
O jogo está publicado e pronto para ser jogado!

Clique aqui para jogar agora!

🕹️ Como Jogar
O jogo escolhe aleatoriamente um número secreto entre 1 e 100.

Você tem 10 tentativas para acertar.

Selecione um número no menu dropdown e clique em "Dar Palpite".

O jogo fornecerá feedback após cada palpite:

Muito Alto: O número secreto é menor.

Muito Baixo: O número secreto é maior.

Vitória: Se você adivinhar o número, será solicitado o seu nickname para registrar sua pontuação no Placar Global.

O placar exibe os 10 melhores jogadores com base no menor número de tentativas.

💻 Tecnologias Utilizadas
Este projeto demonstra a construção de um aplicativo web moderno, responsivo e com persistência de dados, tudo em um único arquivo index.html.

Tecnologia

Função

HTML5 / JavaScript

Estrutura principal e lógica do jogo.

Tailwind CSS

Framework CSS utilitário para design responsivo e moderno.

Netlify

Hospedagem e Implantação Contínua (CI/CD) via GitHub.

Firebase Firestore

Banco de dados NoSQL para salvar e exibir o Placar Global de Recordes em tempo real.

🌟 Recursos Principais
Placar Global de Recordes: Salva os melhores scores (menor número de tentativas) no banco de dados.

Seleção por Lista: Evita que o jogador adivinhe o mesmo número duas vezes.

Design Responsivo: Layout otimizado para celulares, tablets e desktops.

⚙️ Configuração Local
Se você deseja rodar este projeto ou contribuir localmente:

Clone o repositório:

git clone https://github.com/pretinhate/Adivinhe-um-numero
Abra o arquivo index.html diretamente no seu navegador.

Nota: O placar de recordes só funcionará corretamente se o projeto estiver configurado com as chaves do Firebase (que já estão embutidas no ambiente do Netlify/Canvas).

Desenvolvido como um projeto de demonstração e aprendizado.
