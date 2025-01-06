# Segmentação de alunos por meio de método de clusterização k-means

O objetivo deste projeto é desenvolver uma classificação dos estudantes com base nas suas notas do boletim escolar para que sejam desenvolvidos materiais de reforço que mais se adequem às suas forças e fraquezas.

Para aqueles alunos com dificuldades em Matemática, mas com facilidade em Ciências da Natureza, podem ser criados exemplos didáticos e questões que ensinem e avaliem o aprendizado de Matemática utilizando contextos oriundos das Ciências da Natureza.

A expectativa é que a associação de novos conhecimentos ao conhecimento pré-existente ajudará os alunos na compreensão e memorização do conteúdo, maximizando o aprendizado.

Foram criados 4 clusters, sendo eles:

*  Cluster 0: Alto a médio desempenho em Humanas e baixo desempenho em Exatas;
*  Cluster 1: Alto desempenho em Humanas, com alto a médio desempenho em Exatas;
*  Cluster 2: Baixo desempenho em todas as disciplinas;
*  Cluster 3: Alto a médio desempenho em todas as disciplinas.

<img src='https://raw.githubusercontent.com/Lud-lud/clustering_analysis/refs/heads/main/3d_plot.png'/>
<img src='https://raw.githubusercontent.com/Lud-lud/clustering_analysis/refs/heads/main/clusters.png'/>

Como conclusão do objetivo do estudo, foram feitas as seguintes recomendações:

*  Cluster 0: Recomenda-se a criação de conteúdos de reforço de Matemática e Tecnologia e Informática mesclados com Língua Portuguesa, Ensino Religioso e Geografia.
*  Cluster 1: Recomenda-se a criação de conteúdos de reforço para todas as disciplinas de humanas mesclados com Matemática e Ciências.
*  Cluster 2: Recomenda-se a criação de conteúdos de reforço para todas as disciplinas mescladas entre si.
*  Cluster 3: Recomenda-se a criação de conteúdos de reforço de Ciências, Língua Portuguesa e Educação Física mesclados com História, Língua Estrangeira e Tecnologia e Informática.

Veja o desenvolvimento completo do projeto [aqui](https://github.com/Lud-lud/segmentacao_estudantes_clustering_analysis/blob/main/analise_clustering_notas_escolares.ipynb).
