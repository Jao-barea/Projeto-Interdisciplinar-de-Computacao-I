G.S ENGENHARIA CIVIL

PROJETO INTERDISCIPLINAR DE COMPUTAÇÃO I (PIC I)


1 OBJETIVO DO PROJETO

O projeto G.S Engenharia Civil apresenta os serviços de uma empresa fictícia de engenharia civil e oferece recursos demonstrativos para clientes e para o engenheiro responsável. O sistema possui uma versão em site e uma versão de terminal desenvolvida em linguagem C.


2 INTEGRANTES

Pedro Rebechi Toledo
João Pedro Barea da Silva
Lucas Vinícius Carraro Defavari
Matheus Packer Canale


3 TECNOLOGIAS UTILIZADAS

O projeto utiliza HTML5, CSS3 e JavaScript na versão para navegador, além da linguagem C na versão de terminal. O site utiliza o armazenamento local do navegador (localStorage) para guardar os dados da demonstração.


4 FUNCIONALIDADES

4.1 Site

O site apresenta a empresa, seus serviços e um portfólio de obras. Também oferece um simulador de estimativa de custos, seleção de pacotes de obra e formulário de proposta.

A área do cliente permite consultar obras, etapas, progresso e anotações. O portal demonstrativo do engenheiro permite cadastrar clientes e obras, registrar anotações, atualizar o andamento das obras e aprovar propostas. O site também possui formulário de contato e opções de tema claro e escuro.

4.2 Programa de terminal em C

A versão de terminal apresenta informações sobre a empresa, seus serviços, o portfólio e os canais de contato. Também calcula uma estimativa de custo de obra com base no tipo de construção e na área informada, validando os dados inseridos pelo usuário.


5 REQUISITOS

Para utilizar o site, é necessário um navegador moderno. Não é preciso instalar dependências.

Para compilar o programa em C, é necessário um compilador C, como o GCC ou o MinGW-w64 no Windows.

É necessária uma conexão com a internet para carregar as imagens hospedadas no Unsplash.


6 INSTALAÇÃO E EXECUÇÃO DO SITE

O repositório pode ser obtido pelo comando:

git clone https://github.com/Jao-barea/Projeto-Interdisciplinar-de-Computa-o-I.git

Após baixar os arquivos, abra a pasta do projeto e execute o arquivo index.html em um navegador. Também é possível utilizar a extensão Live Server no Visual Studio Code.

Os arquivos index.html, style.css e script.js devem permanecer na mesma pasta.


7 COMPILAÇÃO E EXECUÇÃO DO PROGRAMA EM C

Na pasta que contém o arquivo main.c, compile o programa com o GCC:

gcc main.c -o gs-engenharia

No Windows, execute:

.\gs-engenharia.exe

No Linux ou macOS, execute:

./gs-engenharia


8 DADOS E LIMITAÇÕES DA DEMONSTRAÇÃO

O site armazena clientes, obras e propostas no localStorage do navegador utilizado. Esses dados não são enviados a um servidor e não são compartilhados entre navegadores ou computadores.

O portal do engenheiro é demonstrativo e utiliza credenciais fixas no código. O usuário é gsantos e a senha é 1234. Essas credenciais não devem ser utilizadas para proteger dados reais.

Os formulários de contato e de proposta também são demonstrativos. Eles não enviam mensagens ou pedidos para serviços externos.


9 IMAGENS E VÍDEO DE APRESENTAÇÃO

As imagens do site são carregadas de endereços do Unsplash. As capturas de tela do projeto e o link do vídeo de apresentação podem ser incluídos nesta seção quando estiverem disponíveis.


10 REPOSITÓRIO

https://github.com/Jao-barea/Projeto-Interdisciplinar-de-Computa-o-I
