Ferramentas de ArcGIS para Análise de Necessidade de Calagem e Geração de Grade Amostral

Este repositório contém duas ferramentas desenvolvidas em Python para uso com o ArcGIS: Necessidade de Calagem e Grade Amostral. Essas ferramentas foram criadas como parte de um trabalho acadêmico para auxiliar na análise agronômica e no planejamento de amostragens.
Ferramenta: Necessidade de Calagem

Esta ferramenta realiza o cálculo da necessidade de calagem com base em dados de CTC (Capacidade de Troca de Cátions), V% (saturação por bases), PRNT (Poder Relativo de Neutralização Total) e outras variáveis específicas do solo.
Parâmetros de Entrada:

    Contorno: Classe de feição que define a área de estudo.
    Amostra: Arquivo de amostra que contém os dados de CTC e V%.
    CTC: Nome do campo de Capacidade de Troca de Cátions.
    V: Nome do campo de saturação por bases.
    V2: Valor desejado de V%.
    PRNT: Valor de Poder Relativo de Neutralização Total.
    TamPixel: Tamanho do pixel para o IDW.
    DMin: Dose mínima de calagem.
    DMax: Dose máxima de calagem.
    Saida: Caminho do arquivo de saída.

Ferramenta: Grade Amostral

A ferramenta de Grade Amostral gera uma grade para amostragem em coordenadas geográficas ou planas, permitindo a conversão entre sistemas de coordenadas.
Parâmetros de Entrada:

    Contorno: Classe de feição que define a área de estudo.
    Densidade: Densidade da grade (tamanho da célula).
    Saida: Caminho do arquivo de saída.
    Converter: Opção para converter as coordenadas.

Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
Como Contribuir

Se você deseja contribuir com este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Todos os tipos de contribuição são bem-vindos.
