ORGANIZE PWA 2.0
=================

Versão reconstruída para uso simples no celular e para repertórios de igreja.

PRINCIPAIS RECURSOS
- Início com acesso rápido ao último repertório.
- Repertórios separados.
- Biblioteca de músicas com título, artista/ministério, tom e cifra.
- Pesquisa de repertórios e músicas.
- Ordem das músicas com subir/descer.
- Modo Culto em tela cheia.
- Próxima/anterior e gesto de deslizar.
- A-/A+ para tamanho da cifra.
- Transposição por semitons e botão Tom original.
- Backup e restauração em JSON.
- PWA instalável e funcionamento offline depois do primeiro carregamento.
- Tudo salvo localmente no aparelho.

COMO PUBLICAR NO GITHUB PAGES PELO CELULAR
1. Crie/abra um repositório no GitHub.
2. Envie os 5 arquivos desta pasta:
   index.html
   manifest.json
   sw.js
   icon-192.png
   icon-512.png
3. No GitHub, abra Settings > Pages.
4. Em Build and deployment, escolha Deploy from a branch.
5. Selecione a branch principal (normalmente main) e a pasta /root.
6. Salve.
7. Abra o endereço gerado pelo GitHub Pages.
8. No Chrome/Android, use "Adicionar à tela inicial" ou "Instalar app" quando aparecer.

OBSERVAÇÃO
Esta versão é local-first: os dados ficam no navegador/aparelho. O backup permite migrar os dados.
Sincronização entre aparelhos, login e compartilhamento online real exigem uma camada de nuvem, como Supabase, que pode ser adicionada em uma próxima versão sem perder esta estrutura.
