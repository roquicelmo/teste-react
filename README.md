# <div align="center">Marvel Heroes Explorer <img src="https://raw.githubusercontent.com/roquicelmo/marvel-heroes-explorer/main/public/marvel-icon.png" width="30"></div>

<div align="center">
  <img src="https://img.shields.io/badge/Next.js-13+-black?logo=next.js" height="24" alt="Next.js Version">
  <img src="https://img.shields.io/badge/React-18-blue?logo=react" alt="React Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</div>

<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/roquicelmo/marvel-heroes-explorer/main/public/screenshot.png" width="800" alt="App Screenshot">
</div>

## ✨ Features

| Funcionalidade       | Descrição                                                                 |
|----------------------|---------------------------------------------------------------------------|
| 🔍 Busca Avançada    | Filtre heróis por nome                                                   |
| ⭐ Favoritos         | Armazena localmente seus personagens favoritos                           |
| 📱 Responsivo        | Design adaptável para todos os dispositivos                               |
| 📊 Paginação         | Navegação intuitiva entre páginas de resultados                          |
| 🎨 Detalhes Completos| Visualização detalhada com comics, séries e histórias                    |

## 🚀 Quick Start

```bash
# Clone o repositório
git clone https://github.com/roquicelmo/marvel-heroes-explorer.git

# Instale as dependências
npm install

# Configure as chaves da API Marvel
echo "NEXT_PUBLIC_MARVEL_PUBLIC_KEY=sua_chave_publica" > .env.local
echo "NEXT_PUBLIC_MARVEL_PRIVATE_KEY=sua_chave_privada" >> .env.local

# Inicie o servidor
npm run dev
