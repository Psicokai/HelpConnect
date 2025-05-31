# 🧡 HelpConnect

**Protótipo de Alta Fidelidade** de um sistema web para organizar o apadrinhamento de crianças em datas festivas, voltado à ONG Vivenda da Criança.

## 📌 Sobre o Projeto

O **HelpConnect** é um **protótipo funcional de alta fidelidade**, desenvolvido com foco em UX e acessibilidade, que simula o processo de apadrinhamento entre padrinhos e crianças em situação de vulnerabilidade social.

Criado como parte de um projeto acadêmico, o sistema representa uma proposta viável para substituir o processo atual da ONG, que é feito com planilhas, cadernos ou arquivos Word.

## 👨‍👩‍👧 Público-Alvo

- **Padrinhos:** pessoas que desejam contribuir com kits ou valores.
- **Orientadores da ONG:** profissionais que gerenciam o processo de apadrinhamento.
- **Doadores Anônimos:** que preferem contribuir sem identificação.

## 🚀 Funcionalidades do Protótipo

### Para Padrinhos
- Cadastro com validação de dados
- Visualização de crianças com filtros por idade e gênero
- Apadrinhamento com opção anônima
- Emissão de comprovante após a confirmação

### Para Orientadores
- Cadastro e edição de perfis de crianças
- Atualização de status (apadrinhada/não apadrinhada)
- Geração de relatórios
- Termo de uso com política de segurança

### Extras
- Doação anônima via PIX (QR Code)
- Modal de termos antes de ações críticas
- Compatível com teclado e leitores de tela

## 🛠️ Tecnologias Utilizadas

- **HTML5**, **CSS3**, **JavaScript**
- **Bootstrap 5** para responsividade
- **Google Fonts** e **Font Awesome**
- **VS Code** como editor
- Design responsivo adaptado a dispositivos móveis

## 🧱 Estrutura de Arquivos

```bash
📁 HelpConnect/
├── home.html                  # Tela de entrada
├── orientador.html            # Painel de orientadores
├── padrinho.html              # Painel de padrinhos
├── anonimo.html               # Doação anônima
├── Imagens/                   # Logotipo e QR Code
└── README.md                  # Este arquivo
````

## 🔐 Segurança e Conformidade

Embora seja um protótipo, o projeto foi estruturado conforme os principais requisitos legais e técnicos:

* Conformidade com a **LGPD**, **ECA** e **CDC**
* Princípios da **ISO 27001**
* Termos de uso e política de privacidade
* Dados sensíveis apenas visíveis a usuários autorizados

## 🧑‍⚖️ Licença

Projeto acadêmico (sem fins comerciais), desenvolvido por Leonardo Kaique e Pedro Vinicius, da turma 5NB, para a disciplina Projeto Integrador V.

---

## 📷 Protótipo

Este protótipo pode ser navegado localmente abrindo os arquivos HTML em navegador moderno. Não requer backend nem banco de dados.

## 🌍 ONG Parceira

**Vivenda da Criança**
📍 São Paulo - SP
🌐 [vivendadacrianca.com.br](https://www.vivendadacrianca.com.br/)
📧 [vivendadacrianca@terra.com.br](mailto:vivendadacrianca@terra.com.br)

---

## ✨ Possíveis Evoluções

* Integração com API para autenticação e persistência
* Implementação de banco de dados seguro
* Campanhas personalizadas por data comemorativa
* Pagamentos com cartão ou boleto
* Expansão para outras causas sociais (ex: idosos, animais)
