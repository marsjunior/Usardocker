# Comandos simples docker

Pesquisar imagens disponiveis
```
  docker search "nome da imagem a ser pesquisada"
```
Baixar imagem 
```
  docker pull "nome da imagem"
```
Executar um contaner

```
  docker run -it "nome da imagem"
```
Salvar modificações da imagem
```
  docker commit "id do container"
```
Matar um container
```
  docker rm "id do container"
```
Matar todos os container
```
  docker rm $(docker ps -qa)
```
