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

# Lista pra mim

  O Lista pra mim©, é um app que vai revolucionar a forma como você faz compras. Quanto mais você usar o Lista pra mim, mais rápido vai ser gerar novas listas de compras. E você ainda pode economizar anotando preços e locais de compra. Depois é só deixar o Lista pra mim© indicar o melhor lugar para você fazer suas compras.
