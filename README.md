# Trabalho_final_IA_genetics
Trabalho final da disciplina de Inteligência Artificial sobre predição genômica para melhoramento genético.

O trabalho tem como contexto melhoramento genético de cabras com foco no leite de cabra, e o objetivo é testar algoritmos de Machine Learning (Random Forest, SVM e MLP) na seleção dos marcadores (SNPs) que mais influenciam nos fenótipos (proteína e lactose).

Aqui disponibilizo o código feito no google colab em python para rodar os 3 algoritmos, no qual substituindo adequadamente os caminhos dos dados é possívele executa-los. É natural que eles demorem um pouco para terminar de rodar.

No mesmo notebook há um codigo que compara os modelos com a lista de resultados dos métodos tradicionais (GWAS), pegando os top 20 SNPs do modelo e vendo se os encontram na lista (ou se são correlacionados com algum da lista >0.3).

Também disponibilizo os dados:

A matriz de marcadores genéticos (para proteína e lactose)

A tabela de fenótipos por individuos (para lactose e proteína)

Um arquivo de texto entitulado map que possui mais informações sobre os marcadores

A tabela de correlações entre os marcadores.

A lista de SNPs de lactose e proteína (para efeitoa ditivo e de dominancia) encontrados pelos métodos tradicionais (para comparar com as saídas dos modelos).

Lembre-se que os métodos tradicionais podem ter detectado alguns resultados em outros cromossomos na lista deles, só avaliamos nesse trabalho (com os modelos) o cromossomo 6 para proteina e o cromossomo 2 para lactose que é onde estão a maioria dos resultados.

