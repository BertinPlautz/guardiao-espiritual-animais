# 📷 Guia de Imagens da Landing Page

## 🖼️ Imagens Utilizadas no Projeto

Esta landing page utiliza **4 imagens principais** que já estão integradas e funcionando nos URLs fornecidos.

---

## 📋 Lista Completa de Imagens

### 1. **MOCKUP DO PRODUTO** (Hero Section)
- **Arquivo**: Mockup.png
- **URL Atual**: `https://www.genspark.ai/api/files/s/EKZ4KTFx`
- **Localização**: Hero Section (imagem principal à direita)
- **Dimensões Recomendadas**: 1000x800px (aprox.)
- **Formato**: PNG com fundo transparente
- **Descrição**: Mockup mostrando o produto em múltiplos dispositivos (livro físico + tablet + smartphone)
- **Objetivo**: Ancorar autoridade e profissionalismo imediatamente

**Como Aparece na Página**:
```html
<img src="https://www.genspark.ai/api/files/s/EKZ4KTFx" 
     alt="Mockup do Guardião Espiritual dos Animais" 
     class="mockup-image">
```

**Efeitos Aplicados**:
- ✨ Animação de flutuação suave (3s loop)
- 💫 Drop shadow forte (0 20px 60px)
- 🎨 Filtro de qualidade mantido

---

### 2. **BÔNUS 1 - O RITUAL DO ADEUS**
- **Arquivo**: Bônus 1 - RITUAL DO ADEUS.png
- **URL Atual**: `https://www.genspark.ai/api/files/s/Fw91a6ar`
- **Localização**: Seção de Bônus (primeiro card à esquerda)
- **Dimensões Recomendadas**: 600x900px (vertical)
- **Formato**: PNG ou JPG
- **Descrição**: Capa ou mockup do guia "O Ritual do Adeus: A Carta de Alforria"
- **Objetivo**: Mostrar valor tangível do primeiro bônus

**Como Aparece na Página**:
```html
<img src="https://www.genspark.ai/api/files/s/Fw91a6ar" 
     alt="Bônus 1 - Ritual do Adeus" 
     class="bonus-image">
```

**Efeitos Aplicados**:
- 🔥 Badge "BÔNUS EXCLUSIVO" sobreposto
- 📏 Container de 350px de altura
- 🎯 Efeito zoom no hover (scale 1.05)
- 💰 Preço destacado: DE R$ 47 → GRÁTIS

---

### 3. **BÔNUS 2 - SOS ENERGÉTICO**
- **Arquivo**: Bônus 2 - SOS ENERGÉTICO.png
- **URL Atual**: `https://www.genspark.ai/api/files/s/ZmmrtTx1`
- **Localização**: Seção de Bônus (segundo card à direita)
- **Dimensões Recomendadas**: 600x900px (vertical)
- **Formato**: PNG ou JPG
- **Descrição**: Capa ou mockup do guia "SOS Energético: Caixa de Ferramentas"
- **Objetivo**: Mostrar valor tangível do segundo bônus

**Como Aparece na Página**:
```html
<img src="https://www.genspark.ai/api/files/s/ZmmrtTx1" 
     alt="Bônus 2 - SOS Energético" 
     class="bonus-image">
```

**Efeitos Aplicados**:
- 🔥 Badge "BÔNUS EXCLUSIVO" sobreposto
- 📏 Container de 350px de altura
- 🎯 Efeito zoom no hover (scale 1.05)
- 💰 Preço destacado: DE R$ 47 → GRÁTIS

---

### 4. **FOTO DA AUTORA - HELENA FONTES**
- **Arquivo**: Autora.png
- **URL Atual**: `https://www.genspark.ai/api/files/s/zqg8FqJb`
- **Localização**: Seção de Autoridade
- **Dimensões Recomendadas**: 600x600px (quadrada) ou 400x500px (retrato)
- **Formato**: PNG ou JPG
- **Descrição**: Foto profissional de Helena Fontes com seus animais de estimação
- **Objetivo**: Criar conexão humana, transmitir autoridade e empatia

**Como Aparece na Página**:
```html
<img src="https://www.genspark.ai/api/files/s/zqg8FqJb" 
     alt="Helena Fontes - Autora" 
     class="author-photo">
```

**Efeitos Aplicados**:
- 🔲 Bordas arredondadas (20px radius)
- 🌟 Borda dourada decorativa (outline 3px)
- 🏅 Badge flutuante "15 anos de experiência"
- 💫 Sombra forte para destaque
- 📱 Responsiva (max-width: 300px no mobile)

---

## 🔄 Como Substituir Imagens

Se você quiser usar suas próprias imagens no futuro:

### Opção 1: Upload Direto (Servidor)
1. Faça upload das imagens para seu servidor
2. Organize em pasta: `/images/`
3. Edite o `index.html`:

```html
<!-- Antes -->
<img src="https://www.genspark.ai/api/files/s/EKZ4KTFx" alt="...">

<!-- Depois -->
<img src="images/mockup.png" alt="...">
```

### Opção 2: CDN Externo
Use serviços gratuitos como:
- **Imgur** (imgur.com)
- **ImgBB** (imgbb.com)
- **Cloudinary** (cloudinary.com)

### Opção 3: Integração com Hospedagem
Se usar WordPress, Wix, etc., faça upload pela plataforma e copie os URLs gerados.

---

## 📐 Especificações Técnicas

### Dimensões Ideais

| Imagem | Largura | Altura | Proporção | Peso Máx |
|--------|---------|--------|-----------|----------|
| Mockup Hero | 1000px | 800px | 5:4 | 500KB |
| Bônus 1 & 2 | 600px | 900px | 2:3 | 300KB |
| Foto Autora | 600px | 600px | 1:1 | 200KB |

### Formatos Recomendados
- **PNG**: Para mockups com fundo transparente
- **JPG**: Para fotos (menor tamanho de arquivo)
- **WebP**: Formato moderno (menor tamanho, boa qualidade)

### Otimização
Para melhor performance, otimize imagens com:
- **TinyPNG** (tinypng.com) - Compressão automática
- **Squoosh** (squoosh.app) - Conversor online do Google
- **ImageOptim** (imageoptim.com) - App para Mac

---

## 🎨 Diretrizes de Design

### Para Mockup do Produto:
✅ Fundo transparente ou suave  
✅ Múltiplos dispositivos (credibilidade)  
✅ Alta resolução (sem pixelização)  
✅ Paleta harmônica com a landing page  
❌ Evite fundos muito escuros (conflita com hero)

### Para Bônus:
✅ Formato vertical (estilo e-book)  
✅ Título bem visível na capa  
✅ Visual profissional (não amador)  
✅ Cores complementares (dourado, roxo, verde)  
❌ Evite textos muito pequenos

### Para Foto da Autora:
✅ Expressão calorosa e empática  
✅ Ambiente claro e clean  
✅ Preferencialmente com animais  
✅ Roupa neutra/elegante  
✅ Boa iluminação natural  
❌ Evite selfies ou fotos amadoras  
❌ Evite fundos confusos/poluídos

---

## 🚀 Dicas de Performance

### Lazy Loading
As imagens estão configuradas para lazy loading (carregamento sob demanda):

```html
<img loading="lazy" src="...">
```

Isso melhora a velocidade inicial da página!

### Responsividade
Todas as imagens se adaptam automaticamente ao tamanho da tela:

```css
.mockup-image {
    width: 100%;
    max-width: 550px;
    height: auto;
}
```

### Fallback
Se uma imagem não carregar, o navegador exibe o texto alternativo:

```html
<img src="..." alt="Descrição clara do conteúdo">
```

---

## 🔍 Checklist de Qualidade de Imagens

Antes de usar qualquer imagem, verifique:

### Técnico
- [ ] Resolução adequada (HD ou superior)
- [ ] Tamanho de arquivo otimizado (<500KB)
- [ ] Formato correto (PNG/JPG/WebP)
- [ ] Sem distorções ou pixelização
- [ ] Carregamento rápido (teste em 3G)

### Visual
- [ ] Paleta de cores harmônica
- [ ] Boa iluminação e contraste
- [ ] Composição profissional
- [ ] Livre de marcas d'água indesejadas
- [ ] Alta qualidade percebida

### Legal
- [ ] Você possui direitos da imagem
- [ ] Sem conteúdo protegido por copyright
- [ ] Modelos assinaram termo de uso (se aplicável)
- [ ] Créditos dados (se necessário)

---

## 📊 Impacto das Imagens na Conversão

### Por Que Imagens Importam:

**Mockup do Produto** (Hero):
- 📈 Aumenta credibilidade em **40-60%**
- 🎯 Melhora compreensão da oferta
- 💎 Transmite valor e profissionalismo
- ⚡ Captura atenção imediatamente

**Imagens de Bônus**:
- 💰 Tornam valor tangível (não é só texto)
- 🎁 Aumentam percepção de "ganho extra"
- 🔥 Criam urgência para não perder
- ✅ Facilitam decisão de compra

**Foto da Autora**:
- 🤝 Cria conexão humana e confiança
- 👩‍🏫 Estabelece autoridade
- 💜 Gera empatia com o público
- 🎯 Combate ceticismo

---

## 🆘 Solução de Problemas

### ❓ Imagem não aparece
**Possíveis causas**:
1. URL incorreta ou quebrada
2. Bloqueio de CORS (cross-origin)
3. Imagem foi deletada do servidor
4. Firewall/ad-blocker interferindo

**Solução**:
- Teste abrir o URL diretamente no navegador
- Verifique o Console (F12) para erros
- Faça upload local das imagens

### ❓ Imagem muito lenta
**Possíveis causas**:
1. Arquivo muito pesado (>1MB)
2. Servidor lento
3. Imagem não otimizada

**Solução**:
- Comprima com TinyPNG
- Use CDN (Cloudinary, ImgBB)
- Converta para WebP

### ❓ Imagem distorcida no mobile
**Possíveis causas**:
1. CSS de responsividade faltando
2. Proporções incorretas

**Solução**:
- Adicione `width: 100%; height: auto;`
- Teste em dispositivos reais

---

## 📌 Resumo Rápido

| Localização | Imagem Usada | Efeito Principal |
|-------------|--------------|------------------|
| Hero Section | Mockup 3D do produto | Flutuação suave + sombra |
| Seção Bônus | 2 capas verticais | Zoom no hover + badge |
| Autoridade | Foto da Helena | Borda dourada + badge |

**Status**: ✅ Todas as imagens estão integradas e funcionando perfeitamente!

---

## 💡 Próximos Passos

Se você quiser melhorar ainda mais:
1. Adicione mais fotos de animais felizes (conexão emocional)
2. Crie vídeo de apresentação da Helena (hero section)
3. Adicione fotos de depoimentos (prova social visual)
4. Crie infográfico dos 3 pilares (facilita compreensão)

---

**Suas imagens estão perfeitas e prontas para converter!** 🎨📸✨

---

*Última atualização: 07/01/2026*
