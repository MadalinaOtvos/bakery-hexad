# bakery-hexad

A bakery used to base the price of their produce on an individual item cost. So if a customer ordered
10 cross buns then they would be charged 10x the cost of single bun. The bakery has decided to start
selling their produce prepackaged in bunches and charging the customer on a per pack basis. So if the
shop sold vegemite scroll in packs of 3 and 5 and a customer ordered 8 they would get a pack of 3 and
a pack of 5. The bakery currently sells the following products:

</br > Name          <pre>        Code       <pre>       Packs
</br > Vegemite Scroll       VS5     <pre>          3 @ $6.99
                                      </br > <pre> <pre> <pre> 5 @ $8.99
</br > Bluberry Muffin       MB11            <pre> <pre> <pre> 2 @ $9.95
                                      </br > <pre> <pre> <pre> 5 @ $16.95
                                      </br > <pre> <pre> <pre> 8 @ $24.95 
</br > Croissant             CF         3 @ $5.95
                                      </br >  5 @ $9.95
                                      </br >  9 @ $16.99
# Task
Given a customer order you are required to determine the cost and pack breakdown for each product.To save the shipping space each order should contain the minimal number of packs.

# Input:
Each order has a series of lines with each line containing the number of items followed by the
product code. An example input:
</br > 10 VS5
</br > 14 MB11
</br > 13 CF

# Output:
A successfully passing test(s) that demonstrates the following output:
</br > 10 VS5 $17.98
</br > 2 x 5 $8.99
</br > 14 MB11 $54.8
</br > 1 x 8 $24.95
</br > 3 x 2 $9.95
</br > 13 CF $25.85
</br > 2 x 5 $9.95
</br > 1 x 3 $5.95
