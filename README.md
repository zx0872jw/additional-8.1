# additional-8.1
# write def total_rain(year): ... on line 3

    total = sum(year)
    print("Total rainfall in a year is %0.2f" %total)

def average_rain(year):
    average = sum(year)
    average = average / 12
    print("The average monthly ranfall is %0.2f %average)
    
def high_month_rain(year, months):
    highest_rain = max(year)
    month = months[year.index(highest_rain)]
    print("The highest month rainfall is:", month)
    
def low_month_rain(year, months):
    lowest_rain = min(year)
    month = months[year.index(lowest_rain)]
    print("The lowest month rainfall is:", month)
    
def main():
    year = []
    jan=float(input("Please enter Jan rainfall: '))
    feb=float(input("Please enter Feb rainfall: '))
    mar=float(input("Please enter Mar rainfall: '))
    apr=float(input("Please enter Apr rainfall: '))
    may=float(input("Please enter May rainfall: '))
    jun=float(input("Please enter Jun rainfall: '))
    jul=float(input("Please enter Jul rainfall: '))
    aug=float(input("Please enter Aug rainfall: '))
    sep=float(input("Please enter Sep rainfall: '))
    octob=float(input("Please enter Oct rainfall: '))
    nob=float(input("Please enter Nov rainfall: '))
    dec=float(input("Please enter Dec rainfall: '))
    
    months = ["jan", "feb", "mar", "apr", "may", "jun", "jul", "aug", "sep", "oct", "nov", "dec"]
    
    year.append(jan)
    year.append(feb)
    year.append(mar)
    year.append(apr)
    year.append(may)
    year.append(jun)
    year.append(jul)
    year.append(aug)
    year.append(sep)
    year.append(oct)
    year.append(nov)
    year.append(dec)
    
    total_rain(year)
    average_rain(year)
    high_month_rain(year, months)
    low_month_rain(year, months)
    
main()
