# CatalogTransactions
#This Program is a catalog of products that displays the transactions between customers

#Description of "Lovely Loveseat" product

lovely_loveseat_description = """"Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."""

#Price of "Lovely Loveseat" product

lovely_loveseat_price = 254.00

#Description of "Stylish Settee" product

stylish_settee_description = """"Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep"""

#Price of "Stylish Settee" product

stylish_settee_price = 180.50

#Description of "Luxurious Lamp" product

luxurious_lamp_description = """"Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."""

#Price of "Luxurious Lamp" product

luxurious_lamp_price = 52.15

#Sales Tax Calculation 

sales_tax = .088

#Total amount of Customer One's purchase 

customer_one_total = 0

#Tracking the procucts of Customer One 

customer_one_itemization = ""

#Adding products and prices to Customer One's Itemization and Total 

customer_one_total += lovely_loveseat_price
customer_one_itemization += lovely_loveseat_description 

customer_one_total += luxurious_lamp_price
customer_one_itemization += luxurious_lamp_description 

#Customer One is checking out items for purchase 

customer_one_tax = customer_one_total * sales_tax

#Adds the sales tax to Customer One's Total

customer_one_total = customer_one_tax

#Prints out the receipt of Customer One's purchases 

print("Customer One Items: ")
print(customer_one_itemization)
print("Customer One Total: ")
print(customer_one_total)


#Total amount of Customer Two's purchase 

customer_two_total = 0

#Tracking the procucts of Customer One

customer_two_itemization = ""

#Adding products and prices to Customer Two's Itemization and Total

customer_two_total += stylish_settee_price
customer_two_itemization += stylish_settee_description

customer_two_total += luxurious_lamp_price
customer_two_itemization += luxurious_lamp_description

#Adds the sales tax to Customer Two's Total

customer_two_tax = customer_two_total * sales_tax

#Add the sales tax to Customer Two's Total

customer_two_total += customer_two_tax

#Prints out Customer Two's recepit

print("Customer Two Items: ")
print(customer_two_itemization)
print("Customer Two Total: ")
print(customer_two_total)


