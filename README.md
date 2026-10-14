# Loja Virtual — Estilo dos Boys

Projeto React + Vite. Publicado pela Vercel a partir deste repositório do GitHub.

## Como atualizar o site
Sempre que você subir arquivos novos aqui no GitHub (Add file → Upload files, com o mesmo nome/pasta), a Vercel publica a nova versão sozinha em ~1 minuto.

## Acesso ao painel admin
Não existe botão no site. Para entrar: digite `seusite.com/admin` na barra de endereço
(ou clique 5 vezes seguidas na logo).

## Arquivos importantes
- `src/App.jsx` — a loja inteira (vitrine + painel admin)
- `src/index.css` — reset de estilos (evita fundos brancos e botões cinza)
- `vercel.json` — faz `/admin` e os links de produtos funcionarem ao abrir direto / atualizar a página
- `index.html`, `package.json`, `vite.config.js`

## Rodar no computador (opcional)
```
npm install
npm run dev
```

## Importante sobre os dados
Produtos, fotos e configurações editados no painel ficam salvos **no navegador de quem editou** (localStorage).
Ou seja: ainda NÃO aparecem automaticamente para os visitantes. Para isso é preciso ligar um banco de dados
na nuvem (ex: Supabase). Enquanto isso, use "Configurações → Baixar backup" para guardar seus dados.
