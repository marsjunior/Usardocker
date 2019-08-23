# Comandos simples docker

Pesquisar imagens disponíveis
```
  docker search "nome da imagem a ser pesquisada"
```
Baixar imagem 
```
  docker pull "nome da imagem"
```
Executar um container

```
  docker run -it "nome da imagem"
```
Salvar modificações da imagem
```
  docker commit "id do container"
```
Encerrar um container
```
  docker stop "id do container"
```
Encerrar todos os container
```
  docker stop $(docker ps -qa)
```
Deletar um container
```
  docker rm "id do container"
```
Deletar todos os container
```
  docker rm $(docker ps -qa)
```
