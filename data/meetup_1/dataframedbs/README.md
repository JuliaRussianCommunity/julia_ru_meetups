# Материалы по докладу "прототип колоночной БД https://github.com/waralex/DataFrameDBs.jl"

## Для запуска нужно

* установить DataFrameDBs.jl `import Pkg; Pkg.add(Pkg.PackageSpec(url = "https://github.com/waralex/DataFrameDBs.jl.git"))`
* скачать датасет отсюда: https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store

## Файлы

### database_creation.ipynb - конвертация данных из csv в DataFrameDBs

Этот ноутбук не рассматривался на выступлении, однако он понадобится вам, если вы захотите сами запустить презентацию.
При конвертации предполагается что файл `2019-Nov.csv` оригинального датасета переименован в `nov.csv` и лежит в одной папке с ноутбуком

### presentation.ipynb - собственно презентация

Предполагается что выполнены все действия из `database_creation.ipynb` и оригинальный датасет импортирован в таблицу `ecommerce`, которая лежит в одной папке с ноутбуком

## PS

Ноутбуки предоставлены as is, работоспособность их вне моего компьютера я не проверял. По любым вопросам/проблемам можно писать в Issues, или мне лично.