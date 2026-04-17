# Formulário de Matrícula — Estrelas do Amanhã

Formulário de matrícula para a escola de educação infantil **Estrelas do Amanhã**, construído com HTML puro e CSS modular.

![Preview do projeto](assets/preview.png)

## Sobre o projeto

Interface de formulário multi-seção que coleta todas as informações necessárias para a matrícula de uma criança na escola. O layout é estático, sem dependências de frameworks ou bibliotecas externas.

## Seções do formulário

- **Informações da criança** — nome completo, data de nascimento, sexo, informações médicas e upload da certidão de nascimento
- **Endereço residencial** — CEP com campos de rua, número, cidade e estado (preenchidos automaticamente)
- **Informações do responsável** — nome, telefone e e-mail
- **Opções de matrícula** — seleção de turno (manhã/tarde) e modalidade esportiva (futebol, basquete, natação, yoga, vôlei ou boxe)
- **Termos e condições** — aceite dos termos de uso e política de privacidade

## Tecnologias

- HTML5 semântico
- CSS modular (organizado por componentes em `styles/fields/`)

## Estrutura de arquivos

```
├── index.html
├── assets/
│   ├── icons/          # Ícones SVG
│   ├── Illustration.svg
│   ├── logo.svg
│   └── preview.png
└── styles/
    ├── index.css       # Ponto de entrada dos estilos
    ├── global.css      # Reset e variáveis globais
    ├── layout.css      # Estrutura da página
    ├── forms.css       # Estilos gerais do formulário
    └── fields/         # Estilos por tipo de campo
        ├── index.css
        ├── input.css
        ├── buttons.css
        ├── checkbox.css
        ├── radio.css
        └── droparea.css
```
