# 🚀 Caso de Estudo: Intranet Mercadótica

Este repositório documenta o desenvolvimento da **Intranet Mercadótica**, uma plataforma centralizada projetada para otimizar a comunicação interna entre marketing, suporte, lideranças, colaboradores e franqueados.

> **Nota:** Por razões de confidencialidade e propriedade intelectual vinculadas ao meu trabalho no Grupo Mercadótica, o código-fonte original deste projeto é privado. Dados sensíveis foram omitidos para preservar a integridade corporativa.

---

## 📝 Visão Geral do Projeto

A Intranet atua como um ponto único de acesso para informações institucionais e suporte técnico, reduzindo ruídos de comunicação e aumentando a eficiência operacional. O sistema é dividido em dois ambientes:

1.  **Ambiente Administrativo (Admin):** Voltado para gestão e publicação de conteúdos.
2.  **Ambiente de Colaboradores/Franqueados:** Destinado ao consumo de informações e interação com o suporte.

## 🛠️ Tecnologias Utilizadas

* **Backend:** Node.js com TypeScript.
* **ORM & Banco de Dados:** Prisma ORM conectado ao PostgreSQL.
* **Frontend:** React + Vite com TypeScript.
* **Estilização:** Styled Components e CSS (design responsivo e moderno).
* **Comunicação Real-time:** WebSocket via Socket.IO.
* **Ferramentas:** Postman (validação de APIs) e integração de Chatbot.

---

## 💡 Minha Atuação e Responsabilidades

Tive uma participação ativa em todo o ciclo de vida do projeto, tanto no Core do sistema quanto na interface:

### Backend & Dados
* Definição e implementação de entidades, variáveis e relacionamentos no banco de dados via Prisma.
* Criação e validação de rotas da API e garantia da integridade das operações.
* Implementação da lógica de comunicação em tempo real para o chat suporte.

### Frontend & Integração
* Desenho e implementação das interfaces das abas do sistema.
* Desenvolvimento da estrutura visual e funcional do chat em tempo real.
* Integração completa do frontend com o backend, assegurando que as regras de negócio fossem respeitadas na interface.

---

## 🏗️ Estrutura do Sistema (Módulos)

### Ambiente Administrativo
O painel de gestão inclui módulos especializados para uma organização eficiente:
* **Usuários:** Cadastro de Usuários.
* **Treinamentos:** Cadastro de treinamentos para os colaboradores.
* **Vídeos:** Cadastro de Vídeos.
* **Pesquisas (Enquetes):** Coleta de feedback interno.
* **Arquivos:** Gestão de documentos e vídeos com **níveis de acesso por perfil** (gerente, franqueado ou colaborador).
* **Comunicados Urgentes:** Sistema de popup obrigatório que exige confirmação de leitura antes de liberar o uso da plataforma.
* **FAQ e Álbuns:** Central de dúvidas e registros de eventos/mídia.
* **Logs e Relatórios:** Monitoramento de acessos e histórico detalhado de conversas do chat.

### Ambiente de Colaboradores
* Acesso organizado a todo o conteúdo conforme permissões.
* **Chat Inteligente:** Interação inicial com um chatbot para localização rápida de arquivos.
* **Suporte Direto:** Transição fluida para atendimento humano em tempo real via Socket.IO quando necessário.

---

## ⚙️ Como Rodar o Projeto (Configuração Técnica)

Este guia descreve como preparar o ambiente para uma aplicação com esta stack:

### 1. Pré-requisitos
* Node.js (v18+) e NPM/Yarn.
* Instância do PostgreSQL.

### 2. Configuração do Backend
No diretório `/backend`, crie um arquivo `.env`:
```env
DATABASE_URL="postgresql://usuario:senha@localhost:5432/intranet_db"
PORT=3333

```

Instale e execute:

```bash
npm install
npx prisma migrate dev
npm run dev

```

### 3. Configuração do Frontend

No diretório `/frontend`, instale as dependências e inicie o Vite:

```bash
npm install
npm run dev

```

---

## 📈 Resultados e Impacto Operacional

A implementação trouxe ganhos mensuráveis de eficiência para a Mercadótica:

* **Agilidade no Suporte:** O tempo médio de resposta, que era de **40 minutos** (via WhatsApp/Skype), caiu para apenas **6 minutos** dentro da plataforma.
* **Adoção em Massa:** Registrou mais de **200 acessos nas primeiras duas semanas**.
* **Engajamento a Longo Prazo:** Após um ano, a plataforma ultrapassou a marca de **2.000 acessos**, consolidando-se como a ferramenta estratégica de comunicação da empresa.

---

**Desenvolvido por Gervásio Cardoso** [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/gerv%C3%A1sio-cardoso/) | [GitHub](https://www.google.com/search?q=https://github.com/Gervasss)

## 📸 Demonstração 


Ambiente Admin 
---

Dashboard:

<img width="886" height="419" alt="image" src="https://github.com/user-attachments/assets/6b2645ad-a709-42a3-b4a3-f510b8dbb16e" />

Notícias:

<img width="886" height="424" alt="image" src="https://github.com/user-attachments/assets/4f6ed9bb-98a3-45eb-91f7-1ac3f7206a55" />

Pesquisas (enquetes):

<img width="886" height="420" alt="image" src="https://github.com/user-attachments/assets/173b6632-968e-4b7c-970e-7df01fa56acd" />

Arquivos: 

<img width="886" height="427" alt="image" src="https://github.com/user-attachments/assets/05f467ba-f37b-4ace-8d29-050634fac092" />

Comunicados: 

<img width="886" height="426" alt="image" src="https://github.com/user-attachments/assets/9bb4414c-0652-4f9c-8322-d0859d0b894a" />

Álbuns de fotos:

<img width="886" height="418" alt="image" src="https://github.com/user-attachments/assets/06890c14-ae96-4789-8aab-27d27c1d7bac" />


FAQ:

<img width="886" height="418" alt="image" src="https://github.com/user-attachments/assets/eeb9c4d2-293a-4189-910e-6e213c2a45c0" />

Logs:

<img width="886" height="426" alt="image" src="https://github.com/user-attachments/assets/5fc98781-0fe6-4249-8d20-5450e6bd8c4b" />

Usuários: 

<img width="886" height="426" alt="image" src="https://github.com/user-attachments/assets/3d6099b4-fd1d-41f2-a7fa-2af18f0a44cf" />

Relatórios de atendimentos:

<img width="886" height="424" alt="image" src="https://github.com/user-attachments/assets/5626be2e-c3c3-4046-a8fe-f7deae78e5df" />

Chamados:

<img width="886" height="424" alt="image" src="https://github.com/user-attachments/assets/e3a728de-c02c-4847-95dc-6ce4f3b5f907" />

Treinamentos:

<img width="845" height="423" alt="image" src="https://github.com/user-attachments/assets/afab4655-9ff8-4ed9-b9ba-d892659a30dc" />

Vídeos:

<img width="886" height="421" alt="image" src="https://github.com/user-attachments/assets/3cfec8a3-81da-4483-bea8-47e2ae4aaf00" />



Ambiente de Colaboradores e Franqueados
---

Vídeos:

<img width="886" height="425" alt="image" src="https://github.com/user-attachments/assets/cadf0ec3-6c17-432b-b9fe-b3387e338358" />

Fotos:

<img width="886" height="422" alt="image" src="https://github.com/user-attachments/assets/75b13e7c-af16-4cb9-975e-a5929587eef8" />

Comunicados:

<img width="886" height="419" alt="image" src="https://github.com/user-attachments/assets/83e6d115-0bc0-445e-bfd5-4d17bfa60db4" />

Treinamentos:

<img width="886" height="425" alt="image" src="https://github.com/user-attachments/assets/3e58548a-9ced-4f7d-9b0d-b5da57ec3d9a" />


Notícias:

<img width="886" height="422" alt="image" src="https://github.com/user-attachments/assets/3b2a53c4-e917-4c76-b42c-c25f194a7fdf" />

<img width="886" height="394" alt="image" src="https://github.com/user-attachments/assets/90003aea-a4bf-43dc-9742-3a13257ba137" />

Arquivos:

<img width="886" height="427" alt="image" src="https://github.com/user-attachments/assets/03a57436-d8da-4df0-a4b7-cfc7bf3f6a4d" />


FAQ:

<img width="886" height="424" alt="image" src="https://github.com/user-attachments/assets/5273245b-7d79-41c1-a7ea-eb436672fdee" />

ChatBot:

<img width="886" height="426" alt="image" src="https://github.com/user-attachments/assets/58e0be15-1756-481c-aca7-de861e24710b" />

Chat com suporte ativo:

<img width="886" height="424" alt="image" src="https://github.com/user-attachments/assets/3a22a003-110c-45ba-a946-3433579873c0" />









