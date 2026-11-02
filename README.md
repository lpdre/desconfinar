# Desconfinar

Site pessoal, simples e independente, para **analisar e comparar caminhadas** a partir de ficheiros GPX/KML. Não é um navegador GPS nem uma aplicação para bicicletas, motas, carros ou escalada.

## Como experimentar

1. Abre o site e seleciona **Escolher ficheiros**. Podes importar vários GPX/KML de uma vez.
2. Na lista à esquerda (por baixo, em telemóvel), assinala até **4 percursos**.
3. Na **Comparação direta**, cada coluna corresponde a um trilho: distância, D+, D−, inclinações, tempo e velocidade (quando existe histórico temporal).
4. No gráfico **Perfis altimétricos sobrepostos**, compara os mesmos percursos na mesma escala de distância e altitude.
5. Clica no nome de um percurso ou em **Analisar** para ver os indicadores individuais, incluindo inclinação máxima sustentada em 100, 200 e 500 m.
6. O **Mapa** abre só quando precisas dele; tem opção 2D/3D.

Para conhecer a interface sem GPX, escolhe **Experimentar com 3 exemplos fictícios**. Estes exemplos não correspondem a caminhos reais e não servem para navegação.

## Condições e limitações

- Apenas percursos pedestres. O GPX não identifica necessariamente o tipo de atividade; confirma os ficheiros carregados.
- Altitudes, D+ e inclinações variam com a qualidade e densidade dos pontos GPS. Não são medidas de dificuldade técnica.
- Tempo e velocidade em movimento apenas quando existem carimbos temporais válidos no ficheiro. As velocidades são filtradas para valores típicos de caminhada.
- GPX e KML são analisados localmente no navegador e não são partilhados nem publicados. As bibliotecas e os dados cartográficos dependem de serviços externos.
- Ainda não existe base de dados partilhada, contas nem pesquisa geográfica por pontos.

## Publicação

O projeto é um site estático com `index.html` na raiz. No GitHub Pages, seleciona **Settings → Pages → Deploy from a branch → main → / (root)**.
