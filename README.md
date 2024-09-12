# Exp-6
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\sakthi\Downloads\daily-min-temperatures.csv')

print(series.head())
series.plot()
pyplot.show()
![Screenshot 2024-09-12 144737](https://github.com/user-attachments/assets/ac9a9fe7-a36b-4e45-b348-64f64932664d)
series.plot(style='-.')
pyplot.show()
![Screenshot 2024-09-12 144750](https://github.com/user-attachments/assets/7a894aae-3f35-48d2-87ea-5414f7de47cf)
series.hist()
pyplot.show()
![Screenshot 2024-09-12 144759](https://github.com/user-attachments/assets/841b9a53-c8f2-43b5-9042-9b57e0e86d5e)
series.plot(kind='kde')
pyplot.show()
![Screenshot 2024-09-12 144807](https://github.com/user-attachments/assets/93623ba3-c438-459e-bf67-1ea509937ca0)


