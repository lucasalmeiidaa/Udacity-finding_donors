# Nanodegree Data Scientist
# Aprendizagem supervisionada
## Projeto: Encontrando doadores para a CharityML

### Instalação

Este projeto requer **Python 2.7** e as seguintes bibliotecas Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html)

A Udacity recomenda que os alunos instalem o [Anaconda](https://www.continuum.io/downloads), uma distribuição de Python que contém todas as bibliotecas e software necessários para este projeto. 

### Código

Um modelo do código é fornecido no arquivo notebook `finding_donors.ipynb`. Você também precisará usar o arquivo Python `visuals.py` e o arquivo de dados `census.csv` para concluir seu trabalho. Mesmo que parte do código já tenha sido fornecida para ajudá-lo a começar, você precisará implementar funcionalidades adicionais em alguns pontos para conseguir completar o projeto com sucesso. Note que o código incluído em `visuals.py` foi feito para ser utilizado do jeito que está, sem manipulação por parte dos alunos. Mas, se você estiver interessado em saber como as visualizações são criadas no notebook, fique à vontade para explorar esse arquivo Python.

### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto `finding_donors/` (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook finding_donors.ipynb
```  
ou
```bash
jupyter notebook finding_donors.ipynb
```

Isso abrirá o o software e arquivo de projeto iPython Notebook em seu navegador.

### Dados

O conjunto de dados do censo consiste em 32.000 registros, sendo que cada registro possui 13 atributos. Este conjunto de dados é uma versão modificada do que foi publicado no artigo *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* de Ron Kohavi. Você pode encontrar este artigo [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), com o conjunto de dados original hospedado em [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Atributos**
- `age`: Idade
- `workclass`: Classe trabalhadora (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Nível de educação (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Número de anos de estudo concluídos
- `marital-status`: Estado civil (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Ocupação profissional (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Status de relacionamento (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Raça (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sexo (Female, Male)
- `capital-gain`: Ganhos de capital monetário
- `capital-loss`: Perdas de capital monetário
- `hours-per-week`: Média de horas trabalhadas por semana
- `native-country`: País de origem (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Variável-alvo**
- `income`: Classe de renda (<=50K,>50K)</=50K,>

## 📝 Link para o notebook: [finding_donors](https://github.com/lucasalmeiidaa/Udacity-finding_donors/blob/master/finding_donors_PT.ipynb)
