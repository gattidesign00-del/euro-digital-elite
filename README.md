# Euro Digital Elite

Landing page para venda de produtos digitais nos mercados europeus.

## Deploy na Vercel

Este projeto está pronto para deploy na Vercel.

### Como fazer o deploy:

1. **Opção 1 - Interface Web (Mais Fácil)**:
   - Acesse [vercel.com](https://vercel.com)
   - Clique em "Add New" → "Project"
   - Arraste esta pasta para a área de upload
   - Clique em "Deploy"

2. **Opção 2 - Via CLI**:
   ```bash
   npm install -g vercel
   vercel login
   vercel
   ```

### Estrutura do Projeto

```
.
├── index.html          # Página principal (cópia do Euro Digital Elite.html)
├── Euro Digital Elite.html  # Arquivo original
├── vercel.json        # Configuração da Vercel
├── package.json       # Metadados do projeto
└── README.md          # Este arquivo
```

### Importante

Antes do deploy, certifique-se de:
- [ ] Atualizar o número do WhatsApp (linha 350 do index.html)
- [ ] Atualizar os links de pagamento Stripe
- [ ] Verificar se todas as imagens estão acessíveis

### Após o Deploy

A Vercel fornecerá:
- URL de produção (ex: `seu-projeto.vercel.app`)
- Preview URLs para cada commit
- SSL/HTTPS automático
- CDN global

### Domínio Personalizado

Para adicionar um domínio personalizado:
1. Acesse o dashboard do projeto na Vercel
2. Settings → Domains
3. Adicione seu domínio e siga as instruções DNS
