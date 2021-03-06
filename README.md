# Iniciação Cientifica e Tecnologica do UniBH

Projeto Health Lab 4.0
Análise Preditiva na Área da Saúde com Machine Learning 
Orientador: José Humberto Cruvinel (UNIBH)

_____________ 
Objetivo:
Criar um modelo de previsão de internação a partir das variáveis preditoras com Machine Learning. 
O dataset foi disponibilizado com mais de 60 variáveis diferente sobre a situação do paciente e no final tínhamos a indicação se ele foi internado ou não. Ou seja, o projeto foi criado em um modelo binário (dois tipos), internado ou não. 

_____________ 
Pré-Processamento 
-Redução de dimensionalidade; 
-Transformação de dados; 
-Preenchimento de valores nulos/faltantes; 
-Limpeza dos dados/Remoção de Outliers (dados que fogem da margem aceitável). 

_____________ 
Modelos de Machine Learning utilizados: Naive Bayes, Árvore de Decisão (Decision Tree), Random Forrest, SVM (Suport Vector Machine) Regressão Logística, Rede Neural.

_____________ 
Métricas utilizadas: Matriz de Confusão/F1/Accuracy.

Resultados: Alcançamos acurácias relativamente altas, mas não consideramos esse métrica. Pois o dataset tinha muitos dados não internação e poucos dados com a internação. Ou seja o conjunto de dados estava muito desbalanceado prejudicando o modelo. Sendo assim criamos uma nova métrica com base apenas nas pessoas que deveriam ser internadas. 

_____________ 
Conclusão: O dataset foi insuficiente para criar um modelo adequado, muito pela quantidade dos dados, o seu balanceamento não tinha tantos modelos de internação, valores nulos, outliers entre outros. 

_____________ 
Trabalhos futuros: Trabalhar no campo textual (não estruturado) com técnicas de PLN – Processamento de Linguagem Natural.

_____________ 

Apresentação: https://www.youtube.com/watch?v=u8cTE6KkIcs&t=1900s
