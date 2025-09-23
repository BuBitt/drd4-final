# Introdução

A dopamina é um neurotransmissor fundamental na modulação de funções cerebrais relacionadas à motivação, aprendizado, memória, comportamento social e controle motor. Alterações em sua sinalização estão associadas a uma ampla gama de condições, que vão desde transtornos neuropsiquiátricos, como esquizofrenia e transtorno de déficit de atenção e hiperatividade (TDAH), até variações comportamentais ligadas à busca por novidade e impulsividade (Missale et al., 1998; Ashok et al., 2017).
Entre os componentes do sistema dopaminérgico, destaca-se o gene DRD4 (Dopamine Receptor D4), que codifica um receptor acoplado à proteína G pertencente à família dos receptores D2-like. Esse receptor está envolvido na inibição da adenilato ciclase, regulando indiretamente os níveis intracelulares de AMPc (Beaulieu et al., 2011). O gene DRD4 apresenta alta variabilidade genética, caracterizada por polimorfismos de nucleotídeo único (SNPs) e repetições em tandem em número variável (VNTRs), especialmente localizados na região codificante do terceiro loop citoplasmático da proteína (Van Tol et al., 1992).
Esses polimorfismos têm sido alvo de intenso interesse científico por sua possível associação com diferenças individuais no comportamento humano. Em particular, variantes no exon 3, que abrigam repetições do tipo VNTR, foram relacionadas a traços de personalidade como busca por novidade, impulsividade e predisposição a comportamentos de risco (Ebstein et al., 1996; Munafo et al., 2008). Além disso, certos SNPs no gene DRD4 podem impactar a estrutura e a função da proteína, com potenciais implicações clínicas e farmacológicas (Ding et al., 2002; Wang et al., 2004).
Dessa forma, o estudo das variantes genéticas do DRD4 é relevante não apenas para a compreensão dos mecanismos moleculares que modulam a neurotransmissão dopaminérgica, mas também para a investigação de sua contribuição em fenótipos comportamentais e em condições neuropsiquiátricas (Faraone et al., 2006; Reist et al., 1997). Neste contexto, o presente projeto buscou identificar e analisar polimorfismos no gene DRD4, avaliando sua distribuição e possíveis efeitos estruturais e funcionais por meio de ferramentas de bioinformática.


# Metodologia

Este estudo foi conduzido utilizando exclusivamente ferramentas computacionais, sem coleta de material biológico, com o objetivo de analisar variantes do gene DRD4 associadas a transtornos como TDAH e autismo.

1. Coleta de Sequências

As sequências nucleotídicas do gene DRD4 foram obtidas a partir do banco de dados NCBI Nucleotide (nuccore) (Sayers et al., 2022), utilizando as seguintes strings de busca:

>DRD4 AND HOMO SAPIENS AND ADHD

>DRD4 AND HOMO SAPIENS AND AUTISM

As sequências e suas correspondentes traduções proteicas foram exportadas em formato FASTA para posterior análise.

2. Alinhamento Múltiplo de Sequências

As sequências nucleotídicas foram submetidas a alinhamento múltiplo utilizando o algoritmo ClustalW2, por meio do software MEGA11 (Tamura et al., 2011). Esse procedimento permitiu identificar regiões conservadas e variantes entre diferentes alelos ou amostras.

Em seguida, as sequências de aminoácidos derivadas foram também alinhadas múltipla e sistematicamente, possibilitando a detecção de alterações estruturais e divergências entre proteínas variantes do DRD4.

3. Predição de Estrutura Secundária

As sequências de proteínas resultantes do alinhamento foram submetidas à predição de estrutura secundária utilizando o servidor PSIPRED (McGuffin et al., 2000). A análise permitiu identificar a formação de hélices alfa, folhas beta e voltas, fornecendo informações sobre possíveis alterações estruturais associadas a variantes em arquivos .ss2.

4. Catalogação e Análise dos Resultados

As variantes identificadas foram catalogadas quanto à posição na sequência, tipo de alteração (substituição, inserção ou deleção) e possível efeito funcional. Os dados foram organizados em tabelas e figuras, evidenciando regiões polimórficas, padrões de conservação e alterações relevantes. Os achados foram posteriormente discutidos à luz da literatura científica, correlacionando polimorfismos com potenciais impactos neuropsiquiátricos.