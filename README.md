To find the L^h for a specified Date, ID, and horizon depth, use the search_Lh 
method.
Below is an example use of the code:
    test = PlaceHolder("data.csv")
    test.search_Lh("1981Q3", "GB_0", 3)
Notice:
    1. I have not add any exceptions to report manual errors(like ValueError). 
        I will if necessary.
    2. Make sure Statsmodels is installed. See 
        https://www.statsmodels.org/stable/install.html for instruction.
