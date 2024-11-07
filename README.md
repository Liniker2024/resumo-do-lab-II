# resumo-do-lab-II
Segundo Desafio (Benefícios da nuvem)

Nesse lab aprendemos sobre o SLA e suas características como o tempo de inatividade por semana, tempo de inatividade por mês e tempo de inatividade por ano. É importante entender sobre SLA para evitar possíveis problemas em casos de criação de serviço / contrato. Aprendemos também a introdução sobre a criação de máquinas virtuais pelo Azure junto à algumas características de configuração como Opções de disponbilidade, zona de disponibilidade, criação de conjunto de dimensionamento de máquinas virtuais. Também aprendemos sobre a questão da redundância:

- LRS (Local Redundancy Scheme): Refere-se a uma técnica de redundância local, onde componentes críticos de um sistema, como links de comunicação ou equipamentos, são duplicados dentro de um mesmo local (por exemplo, no mesmo data center ou em uma mesma instalação). Isso garante que, se um componente falhar, outro pode assumir a função sem causar interrupções.

- GRS (Global Redundancy Scheme): Trata-se de uma redundância aplicada de forma global, ou seja, em uma escala maior, envolvendo a duplicação de sistemas e links em diferentes locais geográficos. A GRS visa garantir a continuidade dos serviços mesmo em caso de falhas em uma região específica, proporcionando maior resiliência.

- ZRS (Zero-Risk Scheme): Um esquema de redundância onde o objetivo é eliminar completamente o risco de falha, utilizando múltiplos caminhos ou soluções redundantes. Embora o termo "Zero-Risk" possa ser uma meta ideal, em muitos casos ele se refere a estratégias para minimizar os riscos de falhas críticas.

- GZRS (Global Zero-Risk Scheme): Combina a redundância global (GRS) com o objetivo de mitigar todos os riscos de falha em uma rede de grande escala. Nesse esquema, a redundância é implementada globalmente e de forma tão robusta que o risco de falha é minimizado ao máximo possível, buscando alta disponibilidade em qualquer cenário.
