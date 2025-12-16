# Auten Booking Page 📅

Landing page responsiva e minimalista para agendamento de calls de 15 minutos da Auten Technologies, integrada com Cal.com.

![Preview](preview.png)

## ✨ Características

- 🎨 **Design Minimalista** - Interface limpa e profissional com foco na conversão
- 📱 **Totalmente Responsivo** - Adaptado para desktop, tablet e mobile
- ⚡ **Animações Suaves** - Transições e efeitos que melhoram a experiência do usuário
- 🔗 **Integração Cal.com** - Sistema de agendamento robusto e confiável
- 🎯 **Social Proof** - Avatar group mostrando credibilidade (80+ startups)
- 🟢 **Indicador de Disponibilidade** - Pulso animado mostrando vagas disponíveis
- 🌐 **Multi-idioma** - Suporte para português e inglês

## 🚀 Demo

[Ver Demo ao Vivo](https://seu-dominio.com)

## 📋 Funcionalidades

- Avatar group com efeito hover interativo
- Indicador de disponibilidade com animação de pulso
- Links diretos para Telegram e WhatsApp
- Calendário integrado com Cal.com
- Animação de entrada fade-in suave
- Design adaptável para diferentes tamanhos de tela

## 🛠️ Tecnologias

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- JavaScript (Vanilla)
- [Cal.com](https://cal.com) - Sistema de agendamento
- Google Fonts (Inter)

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/skale-booking-page.git
```

2. Navegue até o diretório:
```bash
cd skale-booking-page
```

3. Abra o arquivo `index.html` no seu navegador ou use um servidor local:
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server
```

## ⚙️ Configuração

### Personalizando o Cal.com

Edite a URL do iframe para apontar para sua conta Cal.com:

```html
<iframe 
    src="https://app.cal.com/SEU-USUARIO/SEU-EVENTO?embed=quick-chat&layout=month_view&theme=light&embedType=inline">
</iframe>
```

### Alterando Links Sociais

Atualize os links do Telegram e WhatsApp no HTML:

```html
<a href="https://t.me/SEU-USUARIO" target="_blank" rel="noopener">Telegram</a>
<a href="https://wa.me/SEU-NUMERO" target="_blank" rel="noopener">WhatsApp</a>
```

### Customizando Cores

Edite as variáveis CSS no `:root`:

```css
:root {
    --bg-color: rgb(249, 249, 249);
    --card-bg: rgb(244, 244, 244);
    --text-primary: rgb(56, 56, 56);
    --text-secondary: rgba(0, 0, 0, 0.5);
    --accent-orange: rgb(255, 92, 0);
    --border-color: rgb(251, 251, 248);
}
```

## 📱 Responsividade

A página é otimizada para três breakpoints principais:

- **Desktop**: > 1200px
- **Tablet**: 820px - 1199px
- **Mobile**: < 819px

## 🎨 Estrutura de Design

```
├── Hero Section
│   ├── Avatar Group (com hover effect)
│   ├── Heading Principal
│   ├── Descrição com Links
│   └── Indicador de Disponibilidade
└── Calendar Section
    └── Cal.com Embed
```

## 🔧 Customização Avançada

### Animações

Ajuste a duração e timing das animações:

```css
.hero-section {
    animation: fadeInUp 1.6s cubic-bezier(0.44, 0, 0.56, 1);
}
```

### Avatar Group

Adicione ou remova avatares editando a estrutura HTML:

```html
<div class="avatar-item">
    <div class="avatar">
        <img src="URL-DA-IMAGEM" alt="">
    </div>
</div>
```

## 📄 Estrutura de Arquivos

```
skale-booking-page/
├── index.html          # Arquivo principal
├── README.md           # Este arquivo
└── preview.png         # Screenshot da página (opcional)
```

## 🌐 Deploy

### Vercel

1. Instale o Vercel CLI:
```bash
npm i -g vercel
```

2. Execute:
```bash
vercel
```

### Netlify

1. Arraste e solte a pasta no [Netlify Drop](https://app.netlify.com/drop)

### GitHub Pages

1. Vá em Settings > Pages
2. Selecione a branch `main` e a pasta `root`
3. Clique em Save

## 🐛 Problemas Conhecidos

- O iframe do Cal.com pode levar alguns segundos para carregar completamente
- Em conexões lentas, pode haver um breve flash do skeleton loader

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📧 Contato

Auten Technologies - [@autentechnologies](https://twitter.com/autentechnologies)

Link do Projeto: [https://github.com/seu-usuario/auten-booking-page](https://github.com/seu-usuario/auten-booking-page)

## 🙏 Agradecimentos

- [Cal.com](https://cal.com) - Sistema de agendamento
- [Google Fonts](https://fonts.google.com) - Fonte Inter
- [Framer](https://framer.com) - Inspiração de design

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no GitHub!
