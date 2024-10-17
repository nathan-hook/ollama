Fabric Install

https://github.com/danielmiessler/fabric

$ docker build -t fabric -f Dockerfile-fabric .

$ docker container run --network ollama_default --name fabric --rm -it fabric bash

curl http://ollama:11434
go install github.com/danielmiessler/fabric@latest
fabric --setup
yt
fabric
fabric --help
go install github.com/danielmiessler/yt@latest

fabric --updatepatterns

cat brown-fox.txt | fabric --stream --pattern extract_wisdom

echo "print('hello world')" | fabric --stream --pattern explain_code

/root/.config/fabric/.env




# curl http://ollama:11434/api/tags
{"models":[{"name":"chanwit/flux-7b:v0.1","model":"chanwit/flux-7b:v0.1","modified_at":"2024-08-19T18:30:52.261489001Z","size":4368440216,"digest":"7d07c8697a20ce28e5386e60960fb5ffc2ef7fc993e2630ea608054fc6a8419f","details":{"parent_model":"","format":"gguf","family":"llama","families":["llama"],"parameter_size":"7B","quantization_level":"Q4_K_M"}},{"name":"llama3.1:latest","model":"llama3.1:latest","modified_at":"2024-08-09T20:28:28.214318013Z","size":4661230977,"digest":"91ab477bec9d27086a119e33c471ae7afbd786cc4fbd8f38d8af0a0b949d53aa","details":{"parent_model":"","format":"gguf","family":"llama","families":["llama"],"parameter_size":"8.0B","quantization_level":"Q4_0"}}]}


curl -v http://ollama:11434/api/generate -d '{
  "model": "llama3.1:latest",
  "prompt": "Why is the sky blue?",
  "stream": false
}'