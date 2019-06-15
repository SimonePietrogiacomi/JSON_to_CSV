# JSON to CSV
Convert JSON file to CSV.

It takes every JSON in subdirectories and convert them in a single CSV file. Of course it work with a single JSON too.

The first line of the CSV contains all the keys from all the JSONs. The other lines have values associated with the specific key if there are values for those keys, nothing in other cases (e.g. if in a specific line there is no value for key "key", we'll have a ",," in his position)

**IMPORTANT** This program skip (key, value) pairs if "value" is a list
