<h1 align="center">Olá, eu sou o Emanoel 👋</h1>

<p align="center">
  <b>Desenvolvedor full-stack em Cuiabá/MT</b><br>
  Crio sistemas que resolvem problemas reais de pequenas empresas e escolas:<br>
  SaaS de atendimento no WhatsApp, PDV offline para cantinas e agendamento escolar.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/emanoelpassos/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:passos.patrick@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://agendaprofessor.pages.dev"><img src="https://img.shields.io/badge/Projeto_no_ar-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Projeto no ar"></a>
</p>

---

## 🚀 Projetos em destaque

### 💬 WhatsApp SaaS: atendimento e automação para empresas
Plataforma **multiempresa** para equipes atenderem clientes pelo WhatsApp num painel compartilhado.
- Filas por setor, transferência entre atendentes e conversas "minhas / fila / todas"
- **Chatbot** com menus e palavras-chave, que passa a conversa para um humano quando precisa
- Envio e recebimento de mídia (fotos, áudios, documentos), confirmação de leitura e busca
- Perfis de dono, gestor e atendente, com autenticação JWT e painel de superadmin

`TypeScript` `Node.js` `Fastify` `Prisma` `PostgreSQL` `Redis` `Next.js` `Tailwind` `Docker`

<p align="center">
  <img src="./img/whatsapp-saas-inbox.png" alt="Caixa de conversas do WhatsApp SaaS" width="100%">
</p>
<table>
  <tr>
    <td width="50%"><img src="./img/whatsapp-saas-bot.png" alt="Configuração do chatbot"><br><sub>Chatbot com menus e prévia no WhatsApp</sub></td>
    <td width="50%"><img src="./img/whatsapp-saas-login.png" alt="Tela de login"><br><sub>Tela de acesso das empresas</sub></td>
  </tr>
</table>

---

### 🍽️ Minha Cantina: PDV para cantina escolar (Android + Windows)
Sistema de ponto de venda para o dia a dia de cantinas escolares. Roda **100% offline** no tablet.
- Venda por toque, com pagamento em dinheiro, PIX, cartão ou **saldo pré-pago do aluno**
- Controle de devedores, com extrato em PDF compartilhável pelo WhatsApp
- Relatórios por período, fechamento de caixa e backup no **Google Drive**
- **Atualização automática** via GitHub Releases, com um plugin nativo em Java que instala o APK

`React` `Vite` `Capacitor` `SQLite` `Zustand` `Electron` `Java`

📩 Implantação feita por mim, sob contratação. Fale comigo pelo [LinkedIn](https://www.linkedin.com/in/emanoelpassos/) ou por [e-mail](mailto:passos.patrick@gmail.com).

<p align="center">
  <img src="./img/minha-cantina-landing.png" alt="Landing page da Minha Cantina" width="100%">
</p>
<table>
  <tr>
    <td width="50%"><img src="./img/minha-cantina-pdv.webp" alt="Tela do PDV"><br><sub>Caixa / PDV com saldo do aluno</sub></td>
    <td width="50%"><img src="./img/minha-cantina-devedores.webp" alt="Relatório de devedores"><br><sub>Relatório de devedores com histórico de consumo</sub></td>
  </tr>
</table>

---

### 📅 Agenda Professor: reuniões de pais e professores
Sistema web **em produção** num colégio. Os pais agendam, remarcam ou cancelam a reunião pelo celular informando só o CPF, sem criar conta.
- Painel da coordenação com importação da planilha da secretaria (.xlsx) e exportação para PDF
- Feito com atenção à **LGPD**: dados mínimos nas rotas públicas, limite de tentativas, Turnstile anti-robô e senhas com PBKDF2
- Roda **inteiro no plano gratuito da Cloudflare**, sem servidor próprio

`React` `TypeScript` `Tailwind` `shadcn/ui` `TanStack Query` `Hono` `Cloudflare D1` `Cloudflare Pages`

🔗 [agendaprofessor.pages.dev](https://agendaprofessor.pages.dev)

<p align="center">
  <img src="./img/agenda-professor.png" alt="Tela inicial do Agenda Professor" width="100%">
</p>

---

## 🛠️ Tecnologias

**Linguagens**<br>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">

**Front-end e mobile**<br>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
<img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white">
<img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white">
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white">

**Back-end e dados**<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white">
<img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white">
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">

**Infra e DevOps**<br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white">
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
<img src="https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">

---

<p align="center">
  💡 Aberto a projetos freelance e oportunidades. Vamos conversar!
</p>
