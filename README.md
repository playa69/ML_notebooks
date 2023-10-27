# ML_notebooks
Подробная информация о Notebook'ах в этом репозитории:

>1. Supervised
```
1. Decision_tree_classifier - имплементация дерева решений в библиотеке sklearn. Кроссвалидация и отложенная выборка из sklearn.model_selection.
2. kNN_regression_classification,
3. kNN_weighted - имплементация kNN из sklearn для задачи регрессии и классификации. Без/с весами, с callable-атрибутом. Метрики acuracy_score и R2 (max R2 0.993) 
```
>2. Unsupervised
```
1. Elbow_method,
2. KMeans_custom_and_sklearn,
3. KMeans++_implementation - имплементация KMeans и KMeans++ (лейблы, центройды, кластеры) c критерием останова. Метод Локтя и его визуализация. Имплементация библиотеки sklearn
4. PCA_and_clusterization_metrics - PCA (метод главных компонент) и метрики кластеризаций (affinity prop., спектральная и иерархическа) AMI, ARI, V,H и С
```
>3. Data analysis and others
```
1. spotify_analysis_numpy_pandas,
2. telecom_analysis_pandas_matplotlib__t_sne - визуализация и анализ двух датасетов с помощью Pandas, Seaborn, Matplotlib и scikit t-sne отображения.
3. stable_diffusion - ноутбук с имплементацией (форк) stable_diffusion (промпт - text2image)
4. StandardScaler_MinMaxScaler - standardscaler() и minmaxscaler(), p-value and Shapiro–Wilk test from scipy
```
CSV также тут!
>Also more datasets here https://www.kaggle.com/datasets:
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
