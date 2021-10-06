# Interface-SAVA
Interface Gráfica para o cálculo de IWV

Este projeto é útil a novos usuários interessados em calcular o IWV (conteúdo de vapor D’água integrado da atmosfera). A interface simplifica o processo de utilização do pacote de processamento GIPSY versão X-rc02 para o estudo exclusivo do IWV. Ressalta-se que o pacote GIPSY deve ser licenciado junto a JPL de modo independente da interface SAVA.

O SAVA permite ao  operador “Abrir” um arquivo de observação RINEX para processamento, em seguida executa-se o processamento. Onde o SAVA extrair todas as informações necessárias para obter arquivos complementares, construir a árvore de processamento para rodar o GIPSY e gerar as séries temporais de atraso total e úmido do zênite e o IWV.  

Estão à disposição ainda os arquivos de efemérides, viés e mapa ionosférico e o arquivo de saída gerado pelo SAVA para visualização.
Os principais pacotes python necessários são apresentados a seguir. 
name: Interface sava
dependencies:
    - python=2.7
    - matplotlib
    - numpy
    - pandas=0.24.2
    - pip
    - wxpython=4.0.0
    - pymap3d=1.3.0
