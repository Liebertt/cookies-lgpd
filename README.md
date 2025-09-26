# 🛡️ LGPD Privacy Console: Cookies, Publicidade e Regulação

Este é um projeto de simulação de um **Console de Gestão de Consentimento de Cookies** em conformidade com a **Lei Geral de Proteção de Dados (LGPD)** do Brasil.

O objetivo é demonstrar, de forma prática e interativa, os desafios de privacidade, segurança e regulação apresentados no documento **"Cookies, Publicidade Direcionada e LGPD"** (PDF de referência) e permitir que os usuários explorem o impacto das suas escolhas de consentimento no rastreamento de dados.

---

## 🎯 Conceito e Fundamentação

O projeto foi desenvolvido com base nos princípios centrais da LGPD, como **Finalidade**, **Necessidade** e **Livre Acesso** aos dados, e aborda o conflito central entre a **Publicidade Direcionada** (que depende de rastreamento massivo) e o **Direito à Privacidade** do titular.

### Funções Principais:

1. **Banner de Consentimento:** Simula a notificação obrigatória no primeiro acesso.

2. **Modal de Configuração:** Permite que o usuário **exerça sua autonomia** e defina quais categorias de cookies (Analytics, Marketing) ele permite.

3. **Log de Ações em Tempo Real:** Demonstra o que aconteceria nos bastidores, registrando se o rastreamento para fins de Marketing e Analytics foi **ativado** ou **bloqueado** conforme a escolha do usuário.

---

## 🚀 Como Visualizar (GitHub Pages)

Este é um projeto de arquivo único (`index.html`) e pode ser executado diretamente em qualquer navegador moderno.

### Opção 1: Clonar e Abrir Localmente

1. Clone o repositório:

   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   cd lgpd-privacy-console
   ```

2. Abra o arquivo lgpd_privacy_console.html no seu navegador.

Opção 2: Visualizar pelo GitHub Pages
Se você configurou o GitHub Pages para servir o arquivo HTML principal (ou se o renomeou para `index.html`), o console estará acessível diretamente no link da sua página (ex: `https://<seu-usuario>.github.io/lgpd-privacy-console/`).

💻 Estrutura do Projeto
O projeto é composto por um único arquivo para máxima simplicidade:

|       Arquivo             | Descrição        | Tecnologia
|---------------------------| -----------------| ------------
| `lgpd_privacy_console.html` | Contém toda a estrutura HTML,               estilização CSS e lógica JavaScript para o console de consentimento. | HTML5,<br/> Tailwind CSS,<br/> Vanilla JavaScript
| `README.md` | O presente arquivo. | Markdown


**Tecnologias Utilizadas:**
* **HTML5**: Estrutura base do aplicativo.

* **Tailwind CSS (via CDN)**: Framework utilitário para estilização rápida e responsiva.

* **Vanilla JavaScript**: Lógica para gerenciar o estado de consentimento (consentStatus), exibir/ocultar o banner/modal e registrar as ações no Log.

* **localStorage**: Usado para simular o armazenamento das preferências de consentimento do usuário.

🤝 Colaboração
Contribuições são bem-vindas! Se você tiver sugestões para aprimorar a simulação de conformidade, adicionar outros mecanismos de rastreamento (como Fingerprinting) ou melhorar a interface, sinta-se à vontade para abrir uma issue ou enviar um Pull Request.

Feito com 💙 em um ambiente de desenvolvimento interativo.
