# Recicla-tec

Projeto web educativo para cadastro de lixo eletrônico (E-lixo), desenvolvido para apoiar a campanha de descarte consciente do CEEP Cianorte.

## Sobre o projeto

O Recicla-tec é uma página web estática com formulário de registro de equipamentos eletrônicos para:

- incentivar o descarte correto;
- facilitar a doação de equipamentos ainda funcionais;
- apoiar ações sustentáveis no ambiente escolar e na comunidade.

A interface foi construída com HTML e CSS, com foco em simplicidade, clareza visual e facilidade de uso.

## Funcionalidades atuais

- Cabeçalho com identidade visual da instituição;
- Seção principal com chamada da campanha;
- Formulário de cadastro com campos para:
  - nome do participante;
  - contato (e-mail ou WhatsApp);
  - tipo de equipamento;
  - estado do equipamento;
  - descrição adicional;
- Botão de envio do formulário;
- Rodapé com identificação do projeto.

Observação: o formulário envia dados para `processar_descartar.php`, mas esse arquivo de backend não está presente no repositório atualmente.

## Estrutura do repositório

```text
recicla-tec/
├── CEEPlogobrasao-main/          # imagens e logos da instituição
├── index.html                    # estrutura principal da página
├── style.css                     # estilos da interface
├── site.webmanifest              # manifesto do site
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── LICENSE
└── README.md
```

## Tecnologias utilizadas

- HTML5
- CSS3

## Como executar localmente

1. Clone o repositório:

```bash
git clone https://github.com/BryanonSchool/recicla-tec.git
```

2. Acesse a pasta do projeto:

```bash
cd recicla-tec
```

3. Abra o arquivo `index.html` no navegador.

Dica: você pode usar a extensão Live Server no VS Code para facilitar os testes.

## Créditos

Projeto desenvolvido pelos estudantes do 2ºE do  
Centro Estadual de Educação Profissional (CEEP) – Cianorte.