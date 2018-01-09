### Investigating Iphone Activity Data With Python

To run this analysis with your own data, first you will need to export
your data from the iphone 'health' app.

Next, it will need to be converted from an XML to a CSV.
Personally, I used [this pre-made applehealthdata.py script](https://github.com/tdda/applehealthdata)

From here its a fairly straightforward case of placing the CSV in a
folder named 'data' (iphone_activity_data/data), removing the 'example'
stepcount CSV, and running the jupyter notebook.

---

Requires Python 3 (and other dependencies are printed in the notebook)


