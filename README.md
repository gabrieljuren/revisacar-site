# revisacar-site

Página pública de **Política de Privacidade** do aplicativo [RevisaCar](https://revisacar.com), pronta para publicação via GitHub Pages ou Netlify.

---

## Publicar no GitHub Pages

### Passo a passo

1. **Faça o push do repositório para o GitHub** (caso ainda não tenha feito):

   ```bash
   git add .
   git commit -m "Add privacy policy page"
   git push origin main
   ```

2. **Ative o GitHub Pages:**
   - Acesse o repositório no GitHub.
   - Clique em **Settings** > **Pages** (menu lateral).
   - Em **Source**, selecione o branch `main` e a pasta `/ (root)`.
   - Clique em **Save**.

3. **Aguarde alguns segundos.** O GitHub irá exibir a URL pública no topo da seção Pages:

   ```
   https://<seu-usuario>.github.io/revisacar-site/
   ```

### URL final (exemplo)

```
https://gabrieljuren.github.io/revisacar-site/
```

Use essa URL como link da Política de Privacidade no cadastro do aplicativo na App Store Connect.

---

## Alternativa: Publicar no Netlify

1. Acesse [netlify.com](https://netlify.com) e faça login.
2. Clique em **"Add new site"** > **"Import an existing project"**.
3. Conecte ao repositório GitHub e selecione `revisacar-site`.
4. Mantenha as configurações padrão (sem build command, publish directory é a raiz `/`).
5. Clique em **Deploy site**.

O Netlify gera uma URL pública como:

```
https://revisacar-privacy.netlify.app
```

Você também pode configurar um domínio personalizado nas configurações do site.

---

## Estrutura do projeto

```
revisacar-site/
├── index.html   # Página de Política de Privacidade
└── README.md    # Este arquivo
```

