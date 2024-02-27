Assistente Virtual em Python
Este projeto consiste na criação de um assistente virtual personalizado, similar à Alexa, utilizando Python. O assistente é capaz de realizar diversas tarefas, como informar as horas, buscar informações na Wikipedia, e tocar músicas no YouTube, através de comandos de voz.

Funcionalidades
Informar a hora atual: Ao dizer "que horas são", o assistente responde com a hora atual.
Pesquisar na Wikipedia: Dizendo "procure por" seguido do tópico, o assistente busca na Wikipedia e fornece um resumo da informação.
Tocar música no YouTube: Ao dizer "toque" seguido do nome da música, o assistente utiliza o PyWhatKit para tocar a música correspondente no YouTube.
Tecnologias Utilizadas

SpeechRecognition: Para reconhecimento de voz.
pyttsx3: Para conversão de texto em fala.
PyAudio: Para acesso ao microfone.
PyWhatKit: Para interagir com o WhatsApp, abrir o YouTube, entre outros.
Wikipedia: Para acessar e buscar informações na Wikipedia.

Instalação
Para executar este projeto, é necessário instalar as dependências mencionadas. Você pode instalá-las usando o seguinte comando:

pip install SpeechRecognition pyttsx3 PyAudio pywhatkit wikipedia

Como Usar
Inicialize o assistente virtual: Execute o script para iniciar o assistente. Ele ficará aguardando por comandos de voz.
Fale o seu comando: Diga "horas" para saber a hora atual, "procure por" seguido de um tópico para buscar na Wikipedia, ou "toque" seguido do nome da música para tocar no YouTube.
Aguarde a resposta: O assistente processará o seu comando e responderá de acordo.
Exemplo de Comando

"Que horas são?" - O assistente responderá com a hora atual.
"Procure por Inteligência Artificial" - O assistente fornecerá um resumo sobre Inteligência Artificial da Wikipedia.
"Toque Imagine Dragons" - O assistente iniciará a reprodução de uma música do Imagine Dragons no YouTube.

Notas
Microfone: Certifique-se de que o seu microfone esteja funcionando corretamente para que o assistente possa receber os comandos de voz.
Conexão com a Internet: Uma conexão estável com a internet é necessária para buscar informações e tocar músicas online.
Este projeto é uma forma divertida e educacional de explorar a programação em Python e a criação de assistentes virtuais personalizados. Experimente adicionar novas funcionalidades conforme a sua necessidade ou curiosidade!
