# Resumo e Dicas para Exatas

Site estático em HTML, CSS e JavaScript. Não precisa de instalação de dependências nem de framework.

## Publicar pelo GitHub Pages

1. Entre em https://github.com e crie um repositório novo.
2. Dê um nome ao repositório, por exemplo `resumo-exatas`.
3. Envie o arquivo `index.html` para a raiz do repositório (botão **Add file** > **Upload files**).
4. Abra **Settings** > **Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
7. Aguarde a publicação. O endereço do site aparecerá na própria página **Pages**.

## Salvamento do progresso

O site salva automaticamente no armazenamento local do navegador:
- respostas das questões e acertos;
- dias concluídos do plano semanal;
- notas, pesos, bônus e nota de corte da calculadora SISU;
- última aba aberta.

**Importante:** esses dados ficam no navegador e dispositivo usados. Limpar os dados do navegador ou trocar de dispositivo/navegador pode fazer o progresso não aparecer. Para sincronizar entre dispositivos ou usuários, será necessário conectar um banco de dados, como Supabase.

## Atualizar o site

Edite o `index.html` e envie a nova versão para o mesmo repositório no GitHub. O GitHub Pages publicará a atualização automaticamente.
