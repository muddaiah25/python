# python

There are four collection data types in the Python programming language:

1."LIST" is a collection which is ordered and changeable. Allows duplicate members.

2."TUPLE" is a collection which is ordered and unchangeable. Allows duplicate members.

3."SET" is a collection which is unordered and unindexed. No duplicate members.

4."DICTIONARY" is a collection which is unordered, changeable and indexed. No duplicate members.

When choosing a collection type, it is useful to understand the properties of that type. Choosing the right type for a particular data set could mean retention of meaning, and, it could mean an increase in efficiency or security.

print("Hello, World!"); if 5>7: print ("5 is more than 2"); else: print (" 2 is more than 5");

x=10; y=10;

z=x+y;

print( str(x) +" + " + str(y) +"="+ str(z));

x = 1 # int y = 2.8 # float z = 1j # complex print(type(x)); print(type(y)); print(type(z));

x = 1.10 y = 1.0 z = -35.59

print(type(x)); print(type(y)); print(type(z));

a = "Hello, World!"; print(a[1]);

b = "Hello, World!"; print(b[2:5]);

a = " Hello, World! " print(a.strip()) # returns "Hello, World!"

a = "Hello, World!" print(len(a))

a = "Hello, World!" print(a.lower())

a = "Hello, World!" print(a.upper())

a = "Hello, World!" print(a.replace("H", "J"))

a = "Hello, World!" print(a.split(",")) # returns ['Hello', ' World!']

print("Enter your name:") x = input() print("Hello, " + x)

print ( 10 * 5);

thislist = ["apple", "banana", "cherry"] print(thislist);

thislist = ["apple", "banana", "cherry"] print(thislist[1])

thislist = ["apple", "banana", "cherry"] thislist[1] = "blackcurrant" print(thislist)

thislist = ["apple", "banana", "cherry"] for x in thislist: print(x)

thislist = ["apple", "banana", "cherry"] if "apple" in thislist: print("Yes, 'apple' is in the fruits list")

thislist = ["apple", "banana", "cherry"] print(len(thislist))

thislist = ["apple", "banana", "cherry"] thislist.append("orange") print(thislist)

thislist = ["apple", "banana", "cherry"] thislist.insert(1, "orange") print(thislist)

thislist = ["apple", "banana", "cherry"] thislist.remove("banana") print(thislist)

thislist = ["apple", "banana", "cherry"] del thislist[0] print(thislist)

thislist = ["apple", "banana", "cherry"] del thislist print(thislist) #this will cause an error because "thislist" no longer exists.

thislist = ["apple", "banana", "cherry"] thislist.clear() print(thislist)
