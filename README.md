
# Bem-vindo ao desafio DevOps

Este desafio é destinado a candidatos que sejam iniciantes na área e não é necessário ter conhecimento prévio das linguagens utilizadas nos projetos. O objetivo é ler sobre como é feito o build no README e aplicar no CI do Github Actions ou na plataforma de sua preferência.

# Requisitos para desafio

1. Ferramentas como docker e docker-compose
2. Conhecimento básico de lógica de programação e sistemas
3. Link do projeto para realizar o desafio:
	* Back end: [Projeto php symfony](./services/backend)
4. Plataforma de CI/CD (Github Actions)


## Como realizar o desafio

### Sistema a ser executado ( olhar na pasta service e escolhe um )
Uma aplicação feita em php com framework symfony. A aplicação deve ser feito build de docker e automatizar com CI/CD

#### Passos:
1. Baseado no README.md que tem todos passos para fazer build, criar um dockerFile
2. Criar docker-compose baseado no diagrama que estar no README.md
	* Por exemplo se for back o docker-compose subir um banco de dados e redis. No front é uma fake api com json 
3. Implementar via CI o passo a passo de fazer build do docker e enviar para docker hub a cada commit que enviar para o repositório 
4. No seu dockerFile, docker-compose.yml e outros que voce criou, faça comentarios documentando o que fez e entende (Opcional)
### O desafio será avaliado com base em:

* Funcionalidade da automação do build
* Conhecimento das ferramentas e como foi utilizadas
* Funcionalidade e qualidade de seu codigo
* O que for opcional não é obrigatorio

Boa sorte e divirta-se!
