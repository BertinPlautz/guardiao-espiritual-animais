# 🚀 GUIA DE DEPLOY NO VERCEL - SUPER SIMPLIFICADO

## 📋 RESUMO RÁPIDO

Este guia ensina a migrar seu site para o **Vercel** de forma **gratuita** e **sem complicação**.

---

## ✨ BENEFÍCIOS DO VERCEL

- ✅ **100% Gratuito** para projetos pessoais
- ✅ **Sem erro 405** (problema resolvido)
- ✅ **Google Analytics funciona** perfeitamente
- ✅ **Preview nas redes sociais** (WhatsApp, Instagram, Facebook)
- ✅ **SSL automático** (HTTPS)
- ✅ **Deploy em 2 minutos**
- ✅ **CDN global** (site super rápido no mundo todo)

---

## 🎯 MÉTODO 1: UPLOAD MANUAL (MAIS FÁCIL)

### PASSO 1: Criar conta no Vercel

1. Acesse: **https://vercel.com**
2. Clique em **"Sign Up"**
3. Escolha: **"Continue with GitHub"** (crie conta no GitHub se não tiver)
4. Autorize a conexão
5. ✅ Conta criada!

### PASSO 2: Baixar os arquivos do Genspark

**Opção A - Exportar projeto completo:**
- No painel do Genspark, procure por **"Export"** ou **"Download Project"**
- Baixe o arquivo ZIP
- Extraia em uma pasta

**Opção B - Download manual:**
- Crie uma pasta no seu computador: `guardiao-espiritual`
- Dentro dela, crie as subpastas: `css`, `js`, `images`
- Acesse cada URL e salve (Ctrl+S):
  - `www.simbaspet.com.br/index.html` → salve como `index.html`
  - `www.simbaspet.com.br/livros.html` → salve como `livros.html`
  - `www.simbaspet.com.br/css/style.css` → salve em `css/style.css`
  - `www.simbaspet.com.br/js/script.js` → salve em `js/script.js`
  - Para cada imagem em `www.simbaspet.com.br/images/`, salve na pasta `images/`

### PASSO 3: Adicionar arquivos de configuração

Na pasta do projeto, adicione os arquivos que já foram criados:
- `vercel.json`
- `robots.txt`
- `sitemap.xml`
- `.vercelignore`

### PASSO 4: Fazer upload no Vercel

1. No painel do Vercel, clique em **"Add New Project"**
2. Clique em **"Browse"** ou arraste a pasta inteira
3. Configure:
   - **Project Name**: `guardiao-espiritual-animais`
   - **Framework Preset**: Deixe em "Other"
   - **Root Directory**: `./` (raiz)
   - **Build Command**: deixe vazio
   - **Output Directory**: `./` (raiz)
4. Clique em **"Deploy"**
5. ⏱️ Aguarde 1-2 minutos
6. ✅ Site publicado!

### PASSO 5: Ver seu site no ar

O Vercel vai gerar um link temporário tipo:
```
https://guardiao-espiritual-animais.vercel.app
```

**Teste o site agora:**
1. Acesse o link
2. Abra o Console (F12)
3. Digite: `typeof gtag`
4. Deve retornar: `"function"` ✅

---

## 🌐 MÉTODO 2: VIA GITHUB (MAIS PROFISSIONAL)

### PASSO 1: Criar repositório no GitHub

1. Acesse: **https://github.com/new**
2. Nome do repositório: `guardiao-espiritual-animais`
3. Deixe como **Public**
4. Marque: **"Add a README file"**
5. Clique em **"Create repository"**

### PASSO 2: Fazer upload dos arquivos

1. Na página do repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste TODOS os arquivos do projeto (ou clique em "choose your files")
3. No campo de commit, escreva: `Initial commit - Landing page`
4. Clique em **"Commit changes"**

### PASSO 3: Conectar ao Vercel

1. Acesse: **https://vercel.com/new**
2. Clique em **"Import Git Repository"**
3. Selecione o repositório: `guardiao-espiritual-animais`
4. Clique em **"Import"**
5. Configure:
   - **Project Name**: deixe o mesmo
   - **Framework Preset**: "Other"
   - **Root Directory**: `./`
6. Clique em **"Deploy"**
7. ✅ Site publicado!

---

## 🔗 PASSO EXTRA: CONECTAR SEU DOMÍNIO

### Conectar www.simbaspet.com.br ao Vercel

1. No Vercel, vá no seu projeto
2. Clique em **"Settings"** → **"Domains"**
3. Digite: `www.simbaspet.com.br`
4. Clique em **"Add"**

O Vercel vai mostrar algo tipo:

```
Configure seu DNS no Registro.br:

Tipo: CNAME
Nome: www
Valor: cname.vercel-dns.com
```

### No Registro.br:

1. Acesse: **https://registro.br**
2. Login → Selecione `simbaspet.com.br`
3. Vá em **"DNS"** → **"Zona DNS"**
4. **Delete** o registro CNAME existente para `www`
5. **Adicione** novo registro:
   - **Tipo**: CNAME
   - **Nome**: www
   - **Valor**: `cname.vercel-dns.com`
   - **TTL**: 3600
6. Clique em **"Salvar"**

### Adicionar domínio raiz (sem www):

No Vercel, adicione também: `simbaspet.com.br`

No Registro.br:
1. **Delete** os registros A existentes
2. **Adicione** registro A com IP do Vercel (ele mostrará qual)

**⏱️ Aguarde 24-48h** para propagação completa.

---

## ✅ CHECKLIST PÓS-DEPLOY

Após o deploy, teste:

### 1. Site funcionando
```
✅ Acesse: seu-projeto.vercel.app
✅ Todas as páginas carregam
✅ Imagens aparecem
✅ Design está correto
```

### 2. Google Analytics
```
✅ F12 → Console → typeof gtag = "function"
✅ Acesse: analytics.google.com
✅ Tempo Real → deve aparecer 1 usuário ativo
```

### 3. Status Code
```
✅ Teste em: https://www.redirect-checker.org/
✅ Deve retornar: 200 OK (não 405)
```

### 4. Preview Redes Sociais
```
✅ WhatsApp: https://developers.facebook.com/tools/debug/
✅ Deve mostrar: imagem + título + descrição
```

### 5. Links funcionando
```
✅ 4 CTAs levam para Kiwify
✅ Botão "Leituras Sobre Pets..." abre página de livros
✅ 5 livros levam para Amazon
✅ Redes sociais abrem corretamente
```

---

## 🆘 PROBLEMAS COMUNS

### Problema: "Arquivos não carregam"
**Solução**: Verifique se a estrutura de pastas está correta:
```
/
├── index.html
├── livros.html
├── vercel.json
├── robots.txt
├── sitemap.xml
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
    └── (todas as imagens)
```

### Problema: "Google Analytics não funciona"
**Solução**: 
1. Verifique se `index.html` tem o código do Analytics (linhas 14-21)
2. Limpe o cache do navegador (Ctrl+Shift+Delete)
3. Teste em modo anônimo (Ctrl+Shift+N)

### Problema: "Domínio não conecta"
**Solução**:
1. Verifique se os DNS estão corretos no Registro.br
2. Aguarde até 48h para propagação
3. Teste em: https://dnschecker.org/

---

## 💬 PRECISA DE AJUDA?

Se tiver qualquer dúvida em algum passo:

1. Tire um **print da tela**
2. Me envie o print
3. Me diga em qual **passo** está

Vou te guiar passo a passo! 😊

---

## 🎉 PRÓXIMOS PASSOS APÓS DEPLOY

Depois que o site estiver no ar no Vercel:

1. ✅ Testar todas as funcionalidades
2. ✅ Verificar Google Analytics (24h)
3. ✅ Conectar domínio www.simbaspet.com.br
4. ✅ Compartilhar nas redes sociais
5. ✅ Começar a divulgar e vender!

---

**Boa sorte com o deploy! 🚀✨**
