# 12-02-22Assing2
supermarket bill
# This loop will go on until the budget is integer or float while True: try: bg = float(input("Enter your budget : ")) # if budget is integer or float it will be stored # temporarily in variable 's' s = bg except ValueError: print("PRINT NUMBER AS A AMOUNT") continue else: break # dictionary to store product("name"), quantity("quant"), # price("price") with empty list as their values a ={"name":[], "quant":[], "price":[]} # converting dictionary to list for further updation b = list(a.values()) # variable na value of "name" from dictionary 'a' na = b[0] # variable qu value of "quant" from dictionary 'a' qu = b[1] # variable pr value of "price" from dictionary 'a' pr = b[2] # This loop terminates when user select 2.EXIT option when asked # in try it will ask user for an option as an integer (1 or 2) # if correct then proceed else continue asking options while True: try: ch = int(input("1.
