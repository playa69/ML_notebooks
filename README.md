# ML_notebooks
Подробная информация о Notebook'ах в этоп репозитории:
```
0. stable_diffusion - ноутбук с имплементацией stable_diffusion (промпт - text2image)
1. Elbow_method, KMeans, KMeans++ - имплементация KMeans и KMeans++ (лейблы, центройды, кластеры) c критерием останова. Метод Локтя и его визуализация. Имплементация библиотеки sklearn
2. Decision_tree_classifier - имплементация дерева решений в библиотеке sklearn. Кроссвалидация и отложенная выборка из sklearn.model_selection
3. Spotify.., telecom.. - визуализация и анализ двух датасетов с помощью Pandas, Seaborn, Matplotlib и scikit t-sne
4.
```
CSV in ```"../../data/%name%.csv"``` or seaborn, 
for telecom dataset go to [MLcourse_ai]([url](https://github.com/Yorko/mlcourse.ai/blob/main/data/telecom_churn.csv))
>Also more ds here https://www.kaggle.com/datasets:
```
import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
```
>Python: https://www.python.org/ with enabled env variable

```
pip install numpy
pip install pandas
pip install seaborn
pip install jupyter
jupyter-notebook
```
