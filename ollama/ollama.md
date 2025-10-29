Commands used: 
git clone https://github.com/laurazang27/qtm350-quiz03
cd qtm350-quiz03
mkdir ollama
cd ollama
touch Modelfile
touch ollama.md
ollama pull gemma3:270m
ollama create sarcastic -f Modelfile
ollama run sarcastic


Question: 