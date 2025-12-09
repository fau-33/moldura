# 🦷 Dentes Saudáveis - Site Institucional

Site institucional moderno e responsivo para consultório odontológico, desenvolvido com as mais recentes tecnologias web.

![Next.js](https://img.shields.io/badge/Next.js-13+-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react)
![CSS3](https://img.shields.io/badge/CSS3-Modules-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript)

---

## 📋 Sobre o Projeto

Site profissional para o consultório **Dentes Saudáveis**, localizado na Barra da Tijuca, Rio de Janeiro. O projeto apresenta serviços odontológicos, informações sobre a equipe, depoimentos de clientes e facilita o contato com o consultório.

### ✨ Destaques

- 🎨 Design moderno e profissional
- 📱 Totalmente responsivo (mobile-first)
- ⚡ Performance otimizada com Next.js
- 🌊 Efeito parallax suave
- 🎯 SEO otimizado
- ♿ Acessível e semântico

---

## 🚀 Tecnologias Utilizadas

### Core

- **[Next.js 13+](https://nextjs.org/)** - Framework React para produção
- **[React 18+](https://react.dev/)** - Biblioteca JavaScript para interfaces
- **[JavaScript ES6+](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** - Linguagem de programação

### Estilização

- **CSS Modules** - Estilos com escopo local
- **CSS3** - Animações, transições e efeitos modernos
- **Flexbox & Grid** - Layout responsivo

### Imagens

- **[Next.js Image](https://nextjs.org/docs/api-reference/next/image)** - Otimização automática de imagens
- **Pexels API** - Imagens profissionais de alta qualidade
- **Imagens geradas por IA** - Ícones personalizados

### Performance

- **React Hooks** (`useEffect`) - Gerenciamento de efeitos colaterais
- **GPU Acceleration** - Animações otimizadas com `will-change`
- **Lazy Loading** - Carregamento otimizado de imagens

---

## 📁 Estrutura do Projeto

```
moldura/
├── src/
│   ├── app/
│   │   ├── componentes/
│   │   │   ├── CardDepoimento/
│   │   │   │   ├── index.jsx
│   │   │   │   └── CardDepoimento.module.css
│   │   │   └── MolduraInformacoes/
│   │   │       ├── index.jsx
│   │   │       └── MolduraInformacoes.module.css
│   │   ├── page.js                    # Página principal
│   │   ├── page.module.css            # Estilos da página
│   │   ├── globals.css                # Estilos globais
│   │   └── layout.js                  # Layout raiz
│   └── assets/
│       ├── dente.png                  # Ícone do logo
│       └── aparelho.png               # Imagem do consultório
├── public/                            # Arquivos públicos
├── next.config.mjs                    # Configuração Next.js
├── package.json                       # Dependências
└── README.md                          # Este arquivo
```

---

## 🎨 Funcionalidades

### 🏠 Seções do Site

1. **Header Fixo**

   - Logo profissional
   - Navegação sempre visível

2. **Apresentação**

   - Título impactante
   - Lista de serviços com ícones
   - Background gradiente animado

3. **Benefícios**

   - Por que usar aparelho ortodôntico
   - Imagem ilustrativa com parallax
   - Cards informativos

4. **Depoimentos**

   - Cards de clientes satisfeitos
   - Fotos e avaliações
   - Efeito hover elegante

5. **Informações**

   - Horários de atendimento
   - Equipe de dentistas
   - Telefones para contato

6. **Localização**

   - Endereço completo
   - Mapa do Google Maps integrado

7. **Rodapé**
   - Copyright
   - Créditos do desenvolvedor

### ⚡ Efeitos Especiais

- **Parallax Suave**: Movimento sutil no scroll
- **Hover Effects**: Interatividade nos cards
- **Transições Suaves**: Animações fluidas
- **Background Gradiente**: Efeito visual moderno

---

## 🛠️ Instalação e Uso

### Pré-requisitos

- Node.js 16+ instalado
- npm ou yarn

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/moldura.git

# Entre na pasta do projeto
cd moldura

# Instale as dependências
npm install
```

### Executar em Desenvolvimento

```bash
npm run dev
```

Acesse: [http://localhost:3000](http://localhost:3000)

### Build para Produção

```bash
# Criar build otimizado
npm run build

# Executar build de produção
npm start
```

---

## 📱 Responsividade

O site é totalmente responsivo e otimizado para:

| Dispositivo      | Breakpoint     | Ajustes                           |
| ---------------- | -------------- | --------------------------------- |
| 📱 Mobile        | ≤ 480px        | Layout vertical, logo reduzido    |
| 📱 Tablet        | 481px - 768px  | Grid adaptativo, fontes ajustadas |
| 💻 Desktop       | 769px - 1024px | Layout padrão                     |
| 🖥️ Large Desktop | > 1024px       | Conteúdo centralizado (max-width) |

### Media Queries Implementadas

```css
/* Tablets */
@media (max-width: 768px) {
  /* Ajustes para tablets */
}

/* Smartphones */
@media (max-width: 480px) {
  /* Ajustes para mobile */
}
```

---

## 🎯 Performance

### Otimizações Aplicadas

- ✅ **Next.js Image** - Otimização automática de imagens
- ✅ **CSS Modules** - CSS com escopo local (sem conflitos)
- ✅ **GPU Acceleration** - `will-change: transform`
- ✅ **Lazy Loading** - Carregamento sob demanda
- ✅ **Minificação** - Build otimizado para produção

### Métricas

| Métrica                | Valor  |
| ---------------------- | ------ |
| First Contentful Paint | < 1.5s |
| Time to Interactive    | < 3s   |
| Lighthouse Score       | 90+    |

---

## 🎨 Paleta de Cores

```css
:root {
  --primary: #1b3675; /* Azul principal */
  --secondary: #fdb203; /* Dourado/Amarelo */
  --dark: #171d3f; /* Azul escuro (rodapé) */
  --light: #ffffff; /* Branco */
  --gray: gainsboro; /* Cinza claro */
}
```

---

## 📦 Dependências Principais

```json
{
  "dependencies": {
    "next": "^14.0.0",
    "react": "^18.0.0",
    "react-dom": "^18.0.0"
  }
}
```

---

## 🔧 Configuração do Next.js

### Imagens Externas

O projeto está configurado para aceitar imagens do Pexels:

```javascript
// next.config.mjs
const nextConfig = {
  images: {
    remotePatterns: [
      {
        protocol: "https",
        hostname: "images.pexels.com",
      },
    ],
  },
};
```

---

## 🚀 Melhorias Futuras

### Planejadas

- [ ] Formulário de agendamento online
- [ ] Integração com WhatsApp Business
- [ ] Blog com dicas odontológicas
- [ ] Galeria antes/depois
- [ ] Sistema de avaliações
- [ ] Chat ao vivo
- [ ] Área do paciente
- [ ] Agendamento por calendário

### Sugestões de Marketing

- [ ] Google Analytics
- [ ] Meta Pixel (Facebook/Instagram)
- [ ] Google Ads
- [ ] SEO avançado
- [ ] Schema Markup

---

## 📸 Screenshots

### Desktop

![Desktop View](./screenshots/desktop.png)

### Mobile

![Mobile View](./screenshots/mobile.png)

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fork o projeto
2. Criar uma branch (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Desenvolvedor

**Flávio Félix**

- 💼 LinkedIn: [linkedin.com/in/flaviofelix](https://linkedin.com/in/flaviofelix)
- 🐙 GitHub: [github.com/flaviofelix](https://github.com/flaviofelix)
- 📧 Email: contato@flaviofelix.dev

---

## 📞 Contato do Consultório

**Dentes Saudáveis**

- 📍 Av. Ayrton Senna, 3000 - Barra da Tijuca, Rio de Janeiro - RJ
- 📮 CEP: 22775-904
- ☎️ (21) 3699-9999
- 📱 (21) 97788-5566
- 🕐 Segunda a Sexta: 09:00 - 18:00
- 🕐 Sábado: 09:00 - 12:00

---

## ⭐ Agradecimentos

- [Next.js](https://nextjs.org/) - Framework incrível
- [Pexels](https://pexels.com/) - Imagens profissionais gratuitas
- [Google Fonts](https://fonts.google.com/) - Tipografia

---

<div align="center">

### 🦷 Transformando sorrisos com tecnologia! ✨

**Desenvolvido com ❤️ por Flávio Félix**

</div>
