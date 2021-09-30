# Ch14-Algo-Trading

Baseline Data, Original SVC Model:
![image](https://user-images.githubusercontent.com/85848524/135171594-92109721-f3d5-4049-9606-9d245446f562.png)

Date Sliced (1/1/2018-1/1/2021), Original SVC Model:
![image](https://user-images.githubusercontent.com/85848524/135384824-13916342-73fb-4ce3-adfa-65948f48c6fd.png)
Dropping 2015-2017 from the model turned out to improve the model's accurately significantly, as the strategy looks to very closely match the actual returns.

SMA Adjusted to 50 day and 200 day, Original SVC Model:
![image](https://user-images.githubusercontent.com/85848524/135390990-b0ca550f-7e24-4cec-bd3e-4a84d5ab6ec8.png)
Adjusting the SMA to 50 and 200 days looked to improve the model's accuracy, as the strategy more closely matched the actual returns.

Baseline Data, AdaBoost Model:
![image](https://user-images.githubusercontent.com/85848524/135378663-20f88ec0-15fc-4a1f-bb32-018e730ff496.png)
The AdaBoost model performed about the same as the baseline SVC model, with almost no noticeable difference in the chart.

