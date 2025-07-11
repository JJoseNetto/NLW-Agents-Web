# NLW Agents – Frontend

Este é o frontend do projeto **NLW Agents**, desenvolvido durante o evento **Next Level Week (NLW)** promovido pela Rocketseat. A aplicação é construída com **React**, **Vite**, **Tailwind CSS** e outras bibliotecas modernas da comunidade.

## 🚀 Tecnologias Utilizadas

- **React 19**
- **Vite**
- **TypeScript**
- **Tailwind CSS 4**
- **Radix UI**
- **Lucide React** (ícones)
- **React Router DOM v7**
- **React Query (TanStack)**
- **Class Variance Authority**, `clsx`, `tailwind-merge`
- **Biome** (formatação e lint)
- **Animate CSS (tw-animate-css)**

## 🧱 Padrões e Estrutura

- **Componentização com Radix e Tailwind**
- **Gerenciamento de estado assíncrono com React Query**
- **Arquitetura baseada em componentes reutilizáveis (`components/`)**
- **Uso de variáveis utilitárias com `clsx`, `tailwind-merge` e `cva`**
- **Boas práticas de tipagem com TypeScript**
- **Scripts e ambiente definidos via `vite.config.ts` e `tsconfig.*.json`**

## ⚙️ Setup e Execução

### Pré-requisitos

- Node.js 18+
- PNPM

### Instalação e execução

```bash
# Instale as dependências
pnpm install

# Rode o projeto em modo de desenvolvimento
pnpm dev
```
### Build para produção
```bash
# Gera os arquivos otimizados
pnpm build
```
### Pré-visualização do build
```bash
# Visualiza a versão de produção localmente
pnpm preview
```

### 🧪 Scripts disponíveis
```bash
pnpm dev       # Executa o Vite em modo desenvolvimento
pnpm build     # Compila o projeto para produção
pnpm preview   # Roda uma prévia do build gerado
```
### 📁 Outras ferramentas
- **Biome para lint e formatação**

- **tw-animate-css para animações com utilitários Tailwind**

### 📝 Licença
- **Projeto com fins educacionais, desenvolvido durante o NLW da Rocketseat.**