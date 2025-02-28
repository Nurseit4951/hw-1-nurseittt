# hw-1-nurseittt
# 1. Клонируем твой репозиторий
git clone https://github.com/Nurseit4951/hw-1-nurseittt.git
cd hw-1-nurseittt

# 2. Создаём исходный CSV-файл
echo "year,region,value\n2020,Almaty,130500\n2021,Almaty,150500" > data_original.csv

# 3. Создаём Python-скрипт для преобразования
echo "import pandas as pd\n\ndf = pd.read_csv('data_original.csv')\ndf['year'] = df['year'].astype(str) + '-01-01'\ndf.to_csv('data_trans
