<h1 align="center">Fundamentos de Bootstrap 4</h1> 

## 📖Projeto

Para todos aqueles que estão iniciando a caminhada no meio Dev e sentem dificuldade de entender o conteúdo ou o que cada coisa faz.

Ao clonar esse repositório  tenha a curiosidade de ir mudando algumas coisas como os containers, resoluções e elementos.

<br/>

## 🔧Pré-requisitos

- [Visual Studio Code](https://code.visualstudio.com/?wt.mc_id=vscom_downloads)
- [Bootstrap](https://getbootstrap.com/)  _<< download opcional, possui tudo o que precisamos no site_

<br/>

## 💻Instalação, execução e desenvolvimento

#### Visual Studio Code:

_Após baixar o Visual Studio realize as seguintes etapas:_ 

- Abra o Folder onde salvou esse projeto

#### Bootstrap
Essa parte já esstá feita mas deixarei o processo caso queira tentar tambem!

<br/>

## ✍Processo

_Como eu fiz para adicionar o bootstrap:_


```
<!DOCTYPE html> 

<html> 

<head> 

    <title>Bootstrap Fundamentos</title> 

    <!-- AQUI ADD A PARTE DO CSS DO BOOTSTRAP --> 

</head> 

<body> 

    <p>Bem-vindo ao Fundamentos via CDN (Content Delivery Network)</p> 

    <!-- AQUI ADD A PARTE DE JS DO BOOTSTRAP --> 

 </body> 

</html> 
```
_No site do bootstrap possui os sripts que deve copiar:_ _https://getbootstrap.com/docs/4.4/getting-started/introduction/_

_Observação: Você deve colocar os scripts js por último por "n" motivos, um deles é  porque o browser não vai renderizar a página enquanto ele não baixar o css & o script do js deve estar na ordem exata, se não, não irá funcionar._

_Resumindo só segue o modelo (padrão)._

<br/>

## 📝Estruturas & Definições
- As estruturas precisam estar dentro de um container

#### Containers:
É um elemento que vai conter dentro todos os outros elementos. Ele armazena as “div’s”.

O sistema de Grid (grade em português) no Bootstrap ajuda a alinhar o texto lado a lado e usa uma série de contêineres, linhas e colunas. O sistema Grid no Bootstrap usa ems e rems para definir a maioria dos tamanhos, enquanto os pxs são usados ​​para pontos de interrupção da grade e larguras de contêiner. O sistema de grade de inicialização permite até 12 colunas na página.

![Banana](https://media.geeksforgeeks.org/wp-content/uploads/Bootstrap-part-2.png)

_Ele literalmente tem a forma de um container ^^_

##### Existem principalmente cinco classes no sistema de grade que estão listadas abaixo:

###### Tambem chamados de Breakpoints.

.col- Extra Small ( < 576 px )
.col-sm- Small ( >= 576 px )
.col-md- Medium ( >= 768 px )
.col-lg- Large ( >= 992 px )
.col-xl- Extra Large ( >= 1200 px )
###  
_Essa formatação é diferente em mobile!_

<br/>

## 🏃‍♀️Alguns atalhos interessantes:

Para comentar >> SHIFT + ALT + A

Para formatar documento(a visualização do código organizada em tela) >> SHIFT + ALT + F ou CTRL + ;

<br/>

## 💁‍♀️Agradecimentos:
###### Por proporcionarem alguns cursos gratuitos: (https://www.treinaweb.com.br/) 

###### Por publicar um conteúdo interessante:  (https://www.geeksforgeeks.org/meaning-of-numbers-in-col-md-4-col-xs-1-col-lg-2-in-bootstrap/)

Feito com 💜 by [Soonas](https://www.linkedin.com/in/soonas/)