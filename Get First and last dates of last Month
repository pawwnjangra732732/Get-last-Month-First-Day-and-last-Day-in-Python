import datetime
# Get the today's Date
today = datetime.date.today()

#get the first Day of Current Month
first = today.replace(day=1)

#get the last date of last Month
lastMonthLastDate = first - datetime.timedelta(days=1)

# this will give us Last Month first day 
lastMonnthFirstDay = lastMonthLastDate.replace(day=1)

#and here is the Formatting of DATE
first = lastMonnthFirstDay.strftime("%m/%d/%Y")
last = lastMonthLastDate.strftime("%m/%d/%Y")
print(first)
print(last)
