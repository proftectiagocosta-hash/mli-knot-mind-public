# Criar e publicar o repo `mli-knot-mind-public`

## Opção com GitHub CLI

No terminal, dentro da pasta onde você extraiu este pacote:

```powershell
cd caminho\para\mli-knot-mind-public

git init
git status
git add README.md MANIFESTO.md ROADMAP.md SECURITY.md LICENSE.md CHANGELOG.md docs site assets
git commit -m "docs: criar vitrine publica do mli knot mind"

gh repo create proftectiagocosta-hash/mli-knot-mind-public --public --description "Public showcase of the MLI-Knot Mind prompt-governance framework" --source . --remote origin --push
```

## Se o repo já existir no GitHub

```powershell
cd caminho\para\mli-knot-mind-public

git init
git remote add origin https://github.com/proftectiagocosta-hash/mli-knot-mind-public.git
git status
git add README.md MANIFESTO.md ROADMAP.md SECURITY.md LICENSE.md CHANGELOG.md docs site assets
git commit -m "docs: criar vitrine publica do mli knot mind"
git pull --rebase origin main
git push origin main
```

## Ativar GitHub Pages depois

No GitHub:

```text
Settings → Pages → Build and deployment → Source: Deploy from a branch
Branch: main
Folder: /site
Save
```

## Regra de segurança

Antes de publicar, confirme que nenhum arquivo contém:

```text
prompts privados completos
checkpoints reais
histórico bruto
dados pessoais
tokens, chaves ou segredos
rotinas internas sensíveis
```
