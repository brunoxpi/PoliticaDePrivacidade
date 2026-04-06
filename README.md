# Política de Privacidade — Anova

Página pública da Política de Privacidade da **Anova Financial Technologies Ltda.**

Em conformidade com a LGPD (Lei nº 13.709/2018) e os Meta Platform Terms.

## Estrutura

```
PoliticaDePrivacidade/
├── public/
│   └── index.html     ← Página (HTML estático, single file)
├── vercel.json         ← Headers de segurança, cache, redirects
└── README.md
```

## Deploy via Vercel (Dashboard)

1. Acesse **vercel.com** → login com GitHub
2. **Add New → Project** → selecione `brunoxpi/PoliticaDePrivacidade`
3. Configure:
   - **Framework Preset:** `Other`
   - **Output Directory:** `public`
4. Clique **Deploy**

## Deploy via Vercel CLI

```bash
npm i -g vercel
cd PoliticaDePrivacidade
vercel login
vercel --prod
```

## Domínio customizado

1. No painel Vercel: **Settings → Domains** → adicione `privacidade.anovainvestimentos.com.br`
2. No DNS: crie CNAME `privacidade` → `cname.vercel-dns.com`

## Atualizar a política

```bash
# Edite public/index.html
git add . && git commit -m "docs: atualiza política" && git push
# Vercel faz deploy automático
```

---

**Anova Financial Technologies Ltda.** · CNPJ 56.956.505/0001-89
