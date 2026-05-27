# Workshop Credencial Digital — 4blue

Aplicativo web para geração de credenciais digitais personalizadas para o Workshop Máquina de Lucros.

## 🚀 Tecnologias Utilizadas

- **React 18** com **TypeScript**
- **Vite** (Build tool)
- **Tailwind CSS** (Estilização com tokens HSL e efeitos Neon)
- **Shadcn/UI** (Componentes de interface)
- **React Hook Form + Zod** (Validação de formulários)
- **QRCode.react** (Geração dinâmica de QR Code)
- **HTML-to-Image** (Exportação da credencial para PNG)
- **Lucide React** (Ícones)
- **Sonner** (Notificações)

## 📋 Funcionalidades

- Formulário de cadastro mobile-first com validação em tempo real.
- Integração com Webhook (Google Apps Script) para registro de participantes.
- Geração de credencial VIP com design premium (Dark Mode + Neon Orange).
- QR Code dinâmico apontando para a central do participante.
- Função de download da credencial em alta resolução (3x pixel ratio).

## 🛠️ Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone <url-do-seu-repositorio>
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Para gerar a versão de produção:
   ```bash
   npm run build
   ```

## 🎨 Design System

O projeto utiliza um tema **Dark Mode** elegante:
- **Cores**: Preto puro (`#000000`) e Laranja Neon (`#FFA500`).
- **Tipografia**: Space Grotesk (Títulos) e Inter (Corpo).
- **Efeitos**: Glow radial, Glassmorphism e sombras neon.

## 🌐 Deploy (Netlify)

Este projeto está configurado para deploy automático no Netlify:
- **Build Command**: `npm run build`
- **Publish Directory**: `dist`
- **Configuração de SPA**: Já incluída via `netlify.toml`.

---
Desenvolvido para **4blue**.
