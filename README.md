# Workshop Credencial Digital — 4blue

Aplicativo web para geração de credenciais digitais personalizadas para o Workshop Máquina de Lucros.

## 🚀 Tecnologias Utilizadas

- **React 19** com **TypeScript**
- **Vite** (Build tool)
- **Tailwind CSS v4** (Estilização com tokens HSL e efeitos Neon)
- **Shadcn/UI** (Componentes de interface)
- **React Hook Form + Zod** (Validação de formulários)
- **QRCode.react** (Geração dinâmica de QR Code)
- **HTML-to-Image** (Exportação da credencial para PNG)

## 📋 Funcionalidades

- Formulário de cadastro mobile-first com validação em tempo real
- Integração com Webhook (Google Apps Script) para registro de participantes
- Geração de credencial VIP com design premium (Dark Mode + Neon Orange)
- QR Code dinâmico apontando para a central do participante
- Download da credencial em alta resolução (3x pixel ratio)

## 🛠️ Instalação e Desenvolvimento Local

```bash
# 1. Clone o repositório
git clone <url-do-seu-repositorio>

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm run dev
```

## 🌐 Deploy no GitHub Pages (Automático)

O projeto já está configurado com **GitHub Actions** para deploy automático.

### Configuração única (fazer apenas uma vez):

1. Vá em **Settings** do seu repositório no GitHub
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione **GitHub Actions**
4. Salve

Pronto! A partir de agora, toda vez que você fizer `git push` para a branch `main`, o projeto será compilado e publicado automaticamente.

### URL do projeto:
```
https://<seu-usuario>.github.io/<nome-do-repositorio>/
```

## 🏗️ Build Manual

```bash
npm run build
# Os arquivos prontos ficam na pasta /dist
```

## 🎨 Design System

- **Cores**: Preto puro (`#000000`) e Laranja Neon (`#FFA500`)
- **Tipografia**: Arial Black (Títulos) e Inter (Corpo)
- **Efeitos**: Glow radial, Glassmorphism e sombras neon

---
Desenvolvido para **4blue**.

