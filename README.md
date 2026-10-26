# Site do Prev Auto

Site estático em HTML, CSS e JavaScript, pronto para publicar na Vercel.

## Testar localmente
Abra `index.html` no navegador. Para melhor simulação, use uma extensão de servidor local no editor ou execute `python -m http.server 8000` nesta pasta e acesse `http://localhost:8000`.

## Publicar na Vercel
1. Crie um repositório no GitHub e envie todos os arquivos desta pasta.
2. Entre em https://vercel.com e importe o repositório.
3. Como é um site estático simples, normalmente não é necessário build command; deixe o diretório raiz como `./`.
4. Clique em Deploy. A Vercel fornecerá um endereço público `*.vercel.app`.

Documentação: https://vercel.com/docs

## Como ativar o botão de download
O site espera o APK em `downloads/prev-auto.apk`.
1. Gere uma build de distribuição do aplicativo no Android Studio.
2. Copie o APK para `downloads/prev-auto.apk`.
3. Envie o arquivo ao repositório e faça novo deploy.

Não publique APK de debug como se fosse uma versão oficial. Enquanto o projeto estiver em teste, deixe isso explícito no site e compartilhe apenas com pessoas que entendem que é um protótipo. Para distribuição ampla, considere publicar pela Google Play.

## Personalização
- Edite `index.html` para textos.
- Edite `styles.css` para cores, espaçamentos e aparência.
- O layout usa `#0A1D37`, azul, laranja e verde da identidade visual do Prev Auto.
