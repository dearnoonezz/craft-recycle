# Craft Recycle 4.0 · GTA RP

Site estático, sem dependências ou compilação.

## GitHub Pages
1. Extraia o ZIP e envie todos os arquivos para a raiz do repositório.
2. Settings → Pages → Deploy from a branch → main → / (root) → Save.
3. Abra o endereço indicado pelo GitHub.

## Editor
A aba Editável permite alterar nome, cores, ordem e visibilidade das páginas, criar páginas, excluir páginas personalizadas e configurar caixas. As caixas de cálculo usam dois campos independentes: não são fórmulas encadeadas. Na reciclagem, edite um material, escolha os resultados e ajuste as quantidades. Fotos são reduzidas e guardadas localmente.

## Persistência e publicação
Alterações são locais ao navegador. Para publicar seus dados e personalizações para novos visitantes, baixe config.js pela aba Editável e substitua o arquivo no repositório. Visitantes com dados locais anteriores continuam usando seus próprios dados; para carregar os padrões publicados, exporte um backup antes de limpar os dados do site. A aba Editável não tem autenticação e é acessível a qualquer visitante, mas não altera o repositório diretamente. Não publique informações privadas. Use Backup para transferir dados e fotos entre navegadores. O armazenamento local tem limite variável.

Os valores desconhecidos permanecem vazios; o preço do alumínio ainda está pendente. A reciclagem usa o valor unitário limpo cadastrado para cada material gerado. 

## Versão 4.0 — atualização sobre a 3.1
- Mochila: inventário real, peso disponível, retorno conhecido e alerta de pendências; pedidos com preço superior ao geral são considerados até a quantidade solicitada.
- Ranking: comparação de venda direta, reciclagem, contrabando líquido e preço geral para players. Pedidos específicos aparecem com comprador, quantidade e preço quando informado.
- Players: cadastro, pedidos, entregas e lista de coleta cruzada com a mochila. Marcar entregue não retira itens automaticamente da mochila.
- A chave local `craft-recycle-v1` permanece intacta. As novas páginas e o cadastro de players são adicionados aos dados existentes; exporte um backup antes de atualizar. Não limpe os dados do navegador.
- Para atualizar, substitua somente `app.js`, `style.css`, `index.html` e `README.md` no mesmo repositório. Não substitua `config.js` se tiver configurações próprias. Não exclua arquivos.
- O backup JSON inclui dados de players; mantenha-o privado. A exportação de config.js exclui players, pedidos e mochila. Não publique backups no GitHub.
- O valor de reciclagem usa o campo de valor unitário limpo dos materiais gerados, não o maior preço entre modalidades. Valores incompletos não são considerados definitivos.
- Os dados são locais ao navegador e endereço do site, não sincronizados entre dispositivos.
