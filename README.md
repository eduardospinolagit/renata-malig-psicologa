# Renata Malig - Psicologia

Site institucional da psicóloga Renata Malig (CRP 12/26909), especialista em terapia
para crianças, adolescentes e famílias, com atendimento presencial em Balneário Camboriú
e online.

## Sobre o projeto

Site single-file: todo o HTML, CSS e JavaScript ficam em `index.html`, sem dependências
externas nem build. Layout mobile-first e responsivo.

## Estrutura

```
index.html          site completo (HTML + CSS + JS inline)
site.webmanifest    manifesto PWA
robots.txt          regras de rastreamento
sitemap.xml         mapa do site
og-image.png        imagem de compartilhamento social
icon-192.png        ícones do app
icon-512.png
apple-touch-icon.png
```

## Rodar localmente

```bash
python -m http.server 3000
# http://localhost:3000
```

## Deploy

Deploy automático na Vercel a cada push na branch `main`.

---

Desenvolvido pela Sano Lab.
