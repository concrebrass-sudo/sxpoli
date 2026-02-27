# Site Polimix - Vercel

## Como fazer o deploy na Vercel:

### Opção 1 - Interface Web (Recomendado):
1. Extraia o arquivo ZIP
2. Acesse: https://vercel.com/new
3. Clique em "Browse" ou arraste a pasta **polimix-vercel** inteira
4. Aguarde o deploy finalizar
5. Pronto! O site estará funcionando

### Opção 2 - CLI:
1. Instale: `npm i -g vercel`
2. Entre na pasta extraída: `cd polimix-vercel`
3. Execute: `vercel`
4. Para produção: `vercel --prod`

## Estrutura:
```
polimix-vercel/
├── index.html       # Página principal
├── vercel.json      # Configuração da Vercel (IMPORTANTE!)
├── static/
│   ├── css/        # Estilos
│   └── js/         # JavaScript
```

## Arquivos importantes:
- **vercel.json**: Garante que todas as rotas funcionem (História, Contato, etc.)
- **index.html**: Página principal sem scripts externos
- **static/**: Todos os arquivos CSS e JavaScript do site

## Funcionalidades:
- ✅ 7 páginas completas
- ✅ Design responsivo
- ✅ Todos os botões redirecionam para WhatsApp: https://wa.me/551151041529

---
Site Polimix © 2026
