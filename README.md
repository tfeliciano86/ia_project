# ia_project
Projeto da imersão
Assistente Virtual para Auxílio na Tragédia do Rio Grande do Sul
Descrição
Este projeto Python tem como objetivo fornecer um assistente virtual baseado em inteligência artificial (IA) que conecta pessoas que precisam de ajuda com aquelas que podem ajudar durante a tragédia do Rio Grande do Sul. O assistente virtual usa processamento de linguagem natural (PNL) para entender as necessidades do usuário e conectá-lo a voluntários relevantes na sua região.
Funcionalidades
Entrada do usuário: O usuário fornece seu nome, cidade (escolhendo entre uma lista de cidades do Rio Grande do Sul) e o tipo de ajuda necessária (Sede, Fome, Roupas ou Médica).
Processamento de linguagem natural: O sistema identifica a necessidade do usuário e sua localização.
Correspondência: O assistente virtual busca em uma base de dados de voluntários e encontra aqueles que podem ajudar na cidade do usuário e com o tipo de necessidade especificada.
Comunicação: O sistema exibe os dados de contato dos voluntários que podem ajudar e simula o envio de uma mensagem com os dados do usuário para cada voluntário.
Tecnologias Utilizadas
Python
NLTK (Natural Language Toolkit) - Para processamento de linguagem natural
scikit-learn - Para extração de características e similaridade de texto
Como usar
Instale as bibliotecas necessárias:
pip install nltk sklearn
Baixe o código:
Salve o código Python em um arquivo chamado assistente_rs.py.
Execute o script:
Abra o terminal e execute o comando:
python assistente_rs.py
Siga as instruções na tela:
O programa irá pedir seu nome, cidade e o tipo de ajuda que você precisa. Em seguida, ele exibirá os dados de contato dos voluntários que podem ajudar.
Limitações
A base de dados de voluntários é apenas um exemplo e precisa ser preenchida com dados reais.
A lógica de envio de mensagens é simulada e precisa ser implementada usando uma biblioteca ou API de comunicação real (por exemplo, para enviar emails ou SMS).
A interface do usuário é básica e pode ser melhorada com uma interface gráfica.
O sistema não aborda questões de segurança e privacidade de dados, o que é crucial em uma aplicação real.
Próximos Passos
Integrar uma API de mensagens para enviar notificações reais aos voluntários.
Implementar uma interface gráfica de usuário.
Implementar um sistema de login e gerenciamento de usuários.
Adicionar recursos de segurança e privacidade de dados.
Expandir a base de dados de voluntários e necessidades.
Contribuições
Contribuições para este projeto são bem-vindas! Se você gostaria de contribuir, por favor, bifurque o repositório e envie um pull request.
Licença
Este projeto está sob a licença MIT.
