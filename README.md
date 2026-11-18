# OuvEdu de Bolso — versão com Campanhas

## Como abrir
1. Extraia **todo o conteúdo** do arquivo ZIP para uma pasta.
2. Abra a pasta `OuvEdu-de-Bolso-com-Campanhas`.
3. Dê duplo clique em `index.html` para abrir a tela inicial no navegador.
4. Clique em **Campanhas** para acessar os cinco temas.

A página de Campanhas contém os dados JSON incorporados para funcionar também quando o projeto é aberto diretamente pelo arquivo `index.html` (file://). As imagens devem permanecer na pasta `campanhas/imagens`.

## Estrutura
- `index.html`: página inicial.
- `orientacao/`: módulo Orientação.
- `gestores/`: módulo Gestores.
- `campanhas/index.html`: módulo Campanhas.
- `campanhas/campanhas.json`: dados em JSON, mantidos como arquivo separado.
- `campanhas/imagens/`: 51 imagens numeradas por sequência.

Para publicação em hospedagem ou atualização PWA, publique a pasta inteira mantendo os caminhos e a estrutura.
