# Desconfinar

Site pessoal de **análise e comparação de percursos pedestres** em ficheiros GPX e KML. Sem percursos de bicicleta, mota ou automóvel.

## Como usar

Abre o site, seleciona **Importar GPX / KML** e escolhe um ou vários ficheiros. É possível sobrepor percursos, ativá-los ou ocultá-los e comparar os seus dados. O mapa 2D/3D é apenas apoio à análise.

## Funcionalidades da versão 0.2

- Importação múltipla de GPX e KML.
- Sobreposição e comparação de percursos, com cores diferentes.
- Distância, desníveis acumulados, altitudes e perfil altimétrico.
- Inclinações médias e máximas sustentadas (janelas de 100, 200 e 500 m).
- Distribuição da distância por faixas de inclinação.
- Tempo e velocidade em movimento, quando existem registos temporais.

Os cálculos de inclinação e desnível dependem da qualidade dos dados de altitude. Os percursos de demonstração são fictícios.

## Privacidade e alojamento

O processamento de GPX/KML nesta versão é local, no navegador. Não existe base de dados, contas ou partilha automática de percursos. Para utilizar o mapa são carregados recursos de cartografia e bibliotecas externas.

Este repositório contém um site estático: basta publicar o `index.html` da raiz, por exemplo com GitHub Pages (**Settings → Pages → Deploy from a branch → main → / (root)**).
