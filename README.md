# Teste Técnico - Beon 👩‍💻

Este repositório contém o resultado do teste técnico realizado para a vaga de Desenvolvedor Front-End na empresa Beon. O teste consistia em reproduzir uma estilização detalhada fornecida pela empresa em um arquivo Figma, com fidelidade aos detalhes e sem alterar o HTML fornecido.

Foi necessário criar o layout para desktop e para mobile, especificamente para o modelo iPhone X.


![Captura de tela de 2023-03-16 13-32-31](https://user-images.githubusercontent.com/99517204/225688861-e7e28f2d-6e55-47a4-83f3-b4d9a2d743e8.png)


## Tecnologias utilizadas

* SASS
* CSS
* HTML

## Como rodar o projeto na sua máquina


### 1. Pelo terminal, navegue até o local onde deseja clonar o repositório e utilize o git clone:
```
git clone git@github.com:Helena-Rodrigues-Figueiredo/bn-teste-customizacao-componentes-helena.git
```

### 2. Acesse a pasta 'bn-teste-customizacao-componentes-helena'
```
cd bn-teste-customizacao-componentes-helena
```

### 3. Pelo VSCode, você pode utilizar a extensão Live Share para visualizar a aplicação;

```
code .
```
<br>

⚠️ Este repositório já contém tanto os arquivos SASS quanto o arquivo CSS compilado. Caso não queira realizar nenhuma alteração no SASS, não será necessário seguir os próximos passos.
<br><br>

### 4. Para instalar o SASS em sua máquina digite a seguinte linha de comando (é necessário já ter o Node.js e o NPM):

```
npm install -g sass
```

### 5. Para o SASS ficar em modo de observação para as mudanças realizadas, digite o comando:

```
sass --watch sass/styles.scss:css/styles.css
```
