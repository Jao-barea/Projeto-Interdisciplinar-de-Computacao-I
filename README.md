# G.S Engenharia Civil

Projeto acadêmico do PIC I que apresenta os serviços de uma empresa fictícia de engenharia civil e oferece recursos demonstrativos para clientes e para o engenheiro.

## Integrantes

- Pedro Rebechi Toledo
- João Pedro Barea da Silva
- Lucas Vinícius Carraro Defavari
- Matheus Packer Canale

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- C (versão de terminal)
- `localStorage` do navegador, para salvar localmente os dados da demonstração

## Funcionalidades

### Site

- Apresentação da empresa, dos serviços e do portfólio.
- Simulador de estimativa de custo por tipo de construção e área.
- Formulário de proposta e seleção de pacotes de obra.
- Área do cliente para consultar obras, etapas, progresso e anotações.
- Portal demonstrativo do engenheiro para cadastrar clientes e obras, registrar anotações, atualizar o andamento e aprovar propostas.
- Formulário de contato.
- Alternância entre tema claro e escuro.

### Programa de terminal em C

- Menu com informações da empresa, serviços, portfólio e contato.
- Estimativa de custo da obra conforme o tipo de construção e a área informada.
- Validação dos dados digitados.

## Requisitos

- **Site:** navegador moderno. Não é necessário instalar dependências.
- **Programa em C:** compilador C, como GCC ou MinGW-w64 no Windows.
- **Imagens:** conexão com a internet para carregar as imagens do Unsplash.

## Instalação e execução do site

1. Clone o repositório:

   ```bash
   git clone https://github.com/Jao-barea/Projeto-Interdisciplinar-de-Computa-o-I.git
   ```

2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador. Também é possível executar o site usando a extensão Live Server no Visual Studio Code.
4. Mantenha `index.html`, `style.css` e `script.js` na mesma pasta.

## Compilar e executar o programa em C

Na pasta onde está o arquivo `main.c`, compile com GCC:

```bash
gcc main.c -o gs-engenharia
```

No Windows, execute:

```powershell
.\gs-engenharia.exe
```

No Linux ou macOS, execute:

```bash
./gs-engenharia
```

## Dados e limitações da demonstração

O site salva clientes, obras e propostas no `localStorage` do navegador utilizado. Esses dados não são enviados a um servidor nem compartilhados entre navegadores ou computadores.

O portal do engenheiro é demonstrativo e utiliza credenciais fixas no código:

- **Usuário:** `gsantos`
- **Senha:** `1234`

Essas credenciais não devem ser usadas para proteger dados reais.

Os formulários de contato e de proposta também são demonstrativos. Eles não enviam mensagens ou pedidos para um serviço externo.

## Imagens e vídeo de apresentação

As imagens do site são carregadas de endereços do Unsplash. Adicione capturas de tela do projeto e o link do vídeo de apresentação quando estiverem disponíveis.
Link do vídeo: https://drive.google.com/file/d/1yObnfp6ddgocbe9MpLKXsLy7TSyHNc8P/view?usp=sharing

## Repositório

[Projeto G.S Engenharia Civil no GitHub](https://github.com/Jao-barea/Projeto-Interdisciplinar-de-Computa-o-I)
