SITE PARA RAQUEL — COMO PERSONALIZAR E PUBLICAR

1) PERSONALIZAR O SITE
- Abra o arquivo index.html em um editor de texto (o Bloco de Notas funciona; o VS Code é mais confortável).
- Procure os textos entre colchetes, como [COLE AQUI O PRIMEIRO TEXTO COMPLETO], e substitua cada aviso pelo texto definitivo.
- Para manter parágrafos, cole o texto dentro da área marcada. O site preserva as quebras de linha.
- Troque os títulos dos textos se quiser.
- Na carta escondida, apague o aviso e escreva uma carta inédita para a Raquel.

2) ADICIONAR AS FOTOS
- Coloque suas imagens dentro da pasta fotos.
- Prefira JPG/JPEG ou WebP e nomes simples, por exemplo: foto-01.jpg, foto-02.jpg, foto-03.jpg.
- No index.html, procure o bloco “SUA PRIMEIRA FOTO AQUI” e substitua o bloco inteiro por:
  <img class="photo" src="fotos/foto-01.jpg" alt="Uma lembrança nossa">
- Faça o mesmo com os outros espaços, usando foto-02.jpg e foto-03.jpg.
- Você pode adicionar mais fotos copiando uma linha <img class="photo" ...> para onde quiser.
- Use fotos que vocês estejam confortáveis em deixar acessíveis por um link público.

3) TESTAR ANTES DE PUBLICAR
- Salve o index.html.
- Dê dois cliques nele para abrir no navegador.
- Teste em janela estreita e, quando publicar, abra o link no celular também.
- A música usa o vídeo oficial de “Tudo Que Você Quiser” no YouTube e precisa de internet.

4) PUBLICAR GRATUITAMENTE NO GITHUB PAGES
- Entre em https://github.com e faça login/crie uma conta.
- Clique no + (canto superior direito) > New repository.
- Nome do repositório: para-raquel (pode ser outro nome).
- Escolha Public e clique em Create repository.
- Dentro do repositório, clique Add file > Upload files.
- Envie o index.html e a pasta fotos (incluindo as imagens que colocou nela). Se estiver usando a interface web, pode arrastar os arquivos; para a pasta, arraste os arquivos de dentro dela e mantenha o caminho fotos/nome-da-foto.jpg. Se isso ficar difícil, envie tudo por um arquivo ZIP não funciona diretamente como site: extraia primeiro no computador.
- Clique Commit changes.
- Vá em Settings > Pages.
- Em Build and deployment, escolha Deploy from a branch.
- Branch: main. Pasta: /(root). Clique Save.
- Aguarde alguns minutos. O link aparecerá na seção Pages e normalmente será parecido com https://SEU-USUARIO.github.io/para-raquel/
- Se não aparecer de imediato, aguarde até 10 minutos e atualize a página.

IMPORTANTE SOBRE PRIVACIDADE
O site publicado no GitHub Pages é público. Mesmo que o link não seja divulgado, outras pessoas podem acessá-lo se o encontrarem. O conteúdo do repositório e as fotos também podem ficar acessíveis. Não coloque nada que precise ser realmente privado. Considere pedir consentimento antes de publicar fotos íntimas ou muito pessoais.

DICA
Faça os ajustes primeiro, depois publique. Quando quiser mudar textos ou fotos, basta enviar a versão atualizada dos arquivos ao mesmo repositório; o site será atualizado.
