Creating a file in the mod´s world, we can write our accented words.
 
![alt text](https://raw.githubusercontent.com/jrlazz/lazzaccents/master/accent1.png)

Reading them with

local file=io.open(minetest.get_worldpath().."/arquivb.txt","r")

local arr={}

for line in file:lines() do

	table.insert(arr,line)
	
end

We can use this array to obtain labels, buttons and textlists with accented words.

![alt text](https://raw.githubusercontent.com/jrlazz/lazzaccents/master/accent2.png)
