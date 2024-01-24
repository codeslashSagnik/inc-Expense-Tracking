

### Main Features
- [x] Add Expenses and Incomes by different catgeory and source.
- [x] Users can export their expenses and incomes in Excel, CSV or PDF. (filters are present to download data by year, week, month and today)
- [x] Visualize data by a graph. Graphs are using filtering to show data of month, year, week and today.
- [x] Users can change graph options. (eg: piechart, bargraph, linegraph, etc)
- [x] Users can import incomes and expenses from a csv and excel.
- [x] Users can also search expenses and incomes present in their account

##### Fill the .env file with the correct database, email credentials and cloudinary api credentials, then in terminal execute following commands

```bash
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
source .env
python manage.py migrate
python manage.py runserver
```



### Generate dummy data
```bash
cd Income-Expense-Tracker
source venv/bin/activate
source .env
python generate_data.py
```

##### If all commands run successfully website will be running on PORT 8000 on localhost [http://localhost:8000](http://localhost:8000)
