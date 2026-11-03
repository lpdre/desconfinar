# Desconfinar

Site pessoal, simples e independente, para **analisar e comparar caminhadas** a partir de ficheiros GPX/KML. Não é um navegador GPS nem uma aplicação para bicicletas, motas, carros ou escalada.

## Organização do ecrã

O site abre por defeito em **Tudo**, com comparação, mapa 2D e perfil altimétrico na mesma página. Os separadores **Mapa**, **Comparar** e **Analisar** permitem isolar o conteúdo quando for mais cómodo, especialmente no telemóvel. Na comparação em ecrãs pequenos, as colunas usam círculos com a cor e o número do percurso; os nomes completos estão na legenda por baixo. O botão único para importar GPX/KML está no cabeçalho.

## Como experimentar

1. Abre o site e seleciona **Escolher ficheiros**. Podes importar vários GPX/KML de uma vez.
2. Na lista à esquerda (por baixo, em telemóvel), assinala até **4 percursos**.
3. Na **Comparação direta**, cada coluna corresponde a um trilho: distância, D+, D−, inclinações, tempo e velocidade (quando existe histórico temporal).
4. No gráfico **Perfis altimétricos sobrepostos**, compara os mesmos percursos na mesma escala de distância e altitude.
5. Clica no nome de um percurso ou em **Analisar** para ver os indicadores individuais, incluindo inclinação máxima sustentada em 100, 200 e 500 m.
6. O **Mapa** abre só quando precisas dele; tem opção 2D/3D.

Para conhecer a interface sem GPX, escolhe **Experimentar com 3 exemplos fictícios**. Estes exemplos não correspondem a caminhos reais e não servem para navegação.

## Lista, medição e relevo 3D

- **Lista compacta:** cada percurso tem uma linha curta com nome truncado, distância, D+ e ações pequenas (analisar, enquadrar no mapa e remover). No telemóvel a lista tem altura limitada e deslocação vertical.
- **Medir distâncias:** no cabeçalho do mapa, escolhe **Medir distâncias**. Clica ou toca em pontos sucessivos para medir a distância geodésica total em linha reta, com o valor do último segmento. Usa **Desfazer**, **Limpar pontos** ou **Terminar medição**. Não mede caminhos pedestres pela rede de trilhos nem leva altitudes em conta.
- **Vista 3D:** há um regulador de inclinação entre 45° e 85°, para aproximar a câmara do horizonte. Inclinações superiores a 60° são experimentais no MapLibre e podem ter artefactos gráficos em alguns dispositivos.

## Condições e limitações

- Apenas percursos pedestres. O GPX não identifica necessariamente o tipo de atividade; confirma os ficheiros carregados.
- Altitudes, D+ e inclinações variam com a qualidade e densidade dos pontos GPS. Não são medidas de dificuldade técnica.
- Tempo e velocidade em movimento apenas quando existem carimbos temporais válidos no ficheiro. As velocidades são filtradas para valores típicos de caminhada.
- GPX e KML são analisados localmente no navegador e não são partilhados nem publicados. As bibliotecas e os dados cartográficos dependem de serviços externos.
- Ainda não existe base de dados partilhada, contas nem pesquisa geográfica por pontos.

## Publicação

O projeto é um site estático com `index.html` na raiz. No GitHub Pages, seleciona **Settings → Pages → Deploy from a branch → main → / (root)**.
