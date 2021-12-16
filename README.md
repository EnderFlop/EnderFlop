import datetime
YEAR = datetime.date.today().year

year_to_class_dict = {
  2021: "freshman",
  2022: "sophomore",
  2023: "junior",
  2024: "senior"
  }

try:
  print(f"Hey, I'm a {year_to_class_dict[YEAR]} at the University of Iowa, coding for fun and sometimes not for fun.")
except KeyError:
  print("Hey! I've either graduated from college or forgot to edit this!")
