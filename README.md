# Painel Comercial — Tradição Cadu

## Deploy no GitHub Pages

### Passo a passo:

1. Crie um repositório **privado** no GitHub (ex: `painel-cadu`)

2. Suba os arquivos:
```bash
git init
git add .
git commit -m "Painel comercial v4"
git branch -M main
git remote add origin git@github.com:SEU-USUARIO/painel-cadu.git
git push -u origin main
```

3. Ative o GitHub Pages:
   - Vá em **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / pasta **/ (root)**
   - Clique **Save**

4. Em ~1 minuto, o painel estará em:
   `https://SEU-USUARIO.github.io/painel-cadu/`

### Notas:
- O repositório é **privado**, mas a URL do Pages é acessível para quem tem o link
- Não compartilhe a URL publicamente
- Para atualizar, edite o `index.html` e faça push novamente
