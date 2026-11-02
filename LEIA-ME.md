# Analista de Erros — app Android de teste

O app abre a página do Analista de Erros dentro do celular e funciona sem internet.
Links de pesquisa e fontes abrem no navegador. A pergunta à IA não aparece nesta versão.

## Gerar o APK pelo GitHub (sem instalar nada)
1. Crie uma conta grátis em github.com e um repositório novo (pode ser privado).
2. Clique em "uploading an existing file" e arraste todo o conteúdo desta pasta.
3. Se a pasta `.github` não subir (pastas com ponto ficam ocultas), use
   "Add file > Create new file", digite o nome `.github/workflows/gerar-apk.yml`
   e cole o conteúdo do arquivo de mesmo nome desta pasta.
4. Abra a aba "Actions". O "Gerar APK de teste" roda sozinho (uns 5 minutos).
5. Ao terminar, abra a execução e baixe "AnalistaDeErros-teste" (zip com o APK).

## Ou pelo Android Studio
Abra esta pasta no Android Studio, espere sincronizar e use
Build > Build App Bundle(s) / APK(s) > Build APK(s).

## Instalar no celular
Copie o APK para o celular, toque nele e permita "instalar apps desconhecidos".
É uma versão de teste (assinatura de depuração): não serve para a Play Store.
