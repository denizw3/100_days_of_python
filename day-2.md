Day 2 Project: Tip Calculator (Bahşiş Hesaplama)

Restoranda kalabalık arkadaş grupları için bahşiş hesaplamaya yarayan bir proje yazdım:

```python
print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10 12 15 "))
people = int(input("How many people to split the bill? "))
tip_percent= tip / 100
total_bill= bill + (bill*tip_percent)
per_person= round(total_bill / people, 2)
print (f"You should pay $ {per_person} per person!")


