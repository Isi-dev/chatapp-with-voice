# Flask ChatApp with IBM STT & TTS, & OpenAI gpt5-nano

## In IBM Skills network terminal,

git clone https://github.com/Isi-dev/chatapp-with-voice

cd chatapp-with-voice

mkdir /home/project/chatapp-with-voice/certs/

cp /usr/local/share/ca-certificates/rootCA.crt /home/project/chatapp-with-voice/certs/




### Start the application:

docker build . -t voice-chatapp-powered-by-openai

docker run -p 8000:8000 voice-chatapp-powered-by-openai



