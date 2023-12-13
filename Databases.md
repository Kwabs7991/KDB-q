Databases:

TABLES: first class objects in q

The \l system command loaded and ran the script sp.q.
The script defined three tables, ran three queries against them and displayed the results.
The \a system command listed the names of tables.

**Tables:**

→ To save a table to a file of the same name:

- we can do the following: **save ‘:path/to/sp**
- To save it as an Excel spreadsheet we can instead do: **save ‘:path/to/sp.xls**
- To save it as an CSV spreadsheet we can instead do: **save ‘:path/to/sp.csv**
- To save it as an XML spreadsheet we can instead do: **save ‘:path/to/sp.xlm**
- To save it as an Text file we can instead do: **save ‘:path/to/sp.txt**
- To save it as an Binary file we can instead do: **save ‘:path/to/sp**
- For E.g.: **save ‘:C:/q/w64/sp.xls**

***Note:  Large tables can be splayed (each column written as its own file) and partitioned into time periods.***

[save, rsave keywords save tables to file | Reference | kdb+ and q documentation - Kdb+ and q documentation](https://code.kx.com/q/ref/save/)

CSVs:

→ We can do the following to fetch a CSV example from this website:

- url:”URL LOCATION”
    - For E.g.: url:"https://code.kx.com/download/data/example.csv"
