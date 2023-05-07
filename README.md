# fullcycle-docker-desafio-go
Repositório para publicação da resolução do desafio proposto no curso Full Cycle 3.0

# Descrição do Desafio #

Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. 

- Quando executarmos: docker run user/fullcycle
- Temos que ter o seguinte resultado: Full Cycle Rocks!!
- A imagem de nosso projeto Go precisa ter menos de 2MB =)

 [IMAGEM NO DOCKERHUB](https://hub.docker.com/repository/docker/leobower/fullcycle/general)
  
# Pull #
```
docker pull leobower/fullcycle
 ```
# Run #
```
docker run --rm leobower/fullcycle
 ```
 
 ├── src
│   ├── controller
│   │   ├── **/*.css
│   ├── views
│   ├── model
│   ├── index.js
├── public
│   ├── css
│   │   ├── **/*.css
│   ├── images
│   ├── js
│   ├── index.html
├── dist (or build
├── node_modules
├── package.json
├── package-lock.json 
└── .gitignore
  ├── src
│   ├── controller
│   │   ├── **/*.css
│   ├── views
│   ├── model
│   ├── index.js
├── public
│   ├── css
│   │   ├── **/*.css
│   ├── images
│   ├── js
│   ├── index.html
├── dist (or build
├── node_modules
├── package.json
├── package-lock.json 
└── .gitignore
