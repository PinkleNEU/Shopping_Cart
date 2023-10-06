# Shopping_Cart
* Simulate on-line shopping with cart by:
* - adding initial items to cart
* - repeatedly sorting and totaling items in cart
* - removing items from cart then showing and totaling items in cart
* - adding additional items to cart then showing and totaling items in cart

* a. (10 POINTS) Create AbstractFactoryAPI INNER abstract class (in Item class)
* b. (10 POINTS) Derive AbstractItemFactory INNER class (in Item class) from AbstractFactoryAPI
* c. ( 5 POINTS) Implement AbstractItemFactory as Lazy Singleton factory for creating all Item
objects
* d. ( 5 POINTS) Item class MUST override toString()



* 3. 20 TOTAL POINTS Create Cart class with demo() and demo2() static methods for class Driver to
call:
* a. Cart must COMPLETE the implementation of demo() method (attached BELOW)
* - Using Stream API AND Lambda expressions to:
* SORT initial items in Cart by ASCENDING ID, NAME & ASCENDING PRICE and SHOW
WITH TOTAL
* REMOVE items from Cart and SHOW WITH TOTAL
* ADD ADDITIONAL items in Cart and SHOW WITH TOTAL
* b. Cart must CREATE static demo2() to do SAME FUNCTIONALITY as demo() WITHOUT USING
LAMBDA expressions



* 4. 10 TOTAL POINTS Create following item objects (in FOLLOWING order) using
AbstactItemFactory and add to Cart:
* "3,Almond Milk,2.49"
* "5,Wheat Bread,1.49"
* "2,OJ,3.49"
* and SHOW Total all items in Cart:
*
* 5. 20 TOTAL POINTS Remove item #3 Almond Milk AND item #5 Wheat Bread from Cart and SHOW
Total all items in Cart
*
* 6. 10 TOTAL POINTS ADD additional items #6 Swiss Cheese, $6.49 AND item #7 Blue Cheese 6.49
to Cart and SHOW Total all items in Cart
*
* NOTE:
* FULL CREDIT GIVEN ONLY IF BOTH demo() and demo2() implementations are completed and
submitted on time.
* OTHERWISE AT MOST HALF CREDIT GIVEN for #2, #7
*
* @author dpeters
*
*/


public class Cart {
/**
* Demonstrate the use of this class and simulate on-line shopping cart
*/
public static void demo() {
System.out.println("\n\t" + Cart.class.getName() + ".demo()...");
4/29/22, 6:42 PM Final Cart
https://northeastern.instructure.com/courses/103210/assignments/1384388 3/4
Cart obj = new Cart();
/**
* Add initial Items to Cart IN THIS ORDER using factory
*/
System.out.println("ADD ITEM to CART: \"3,Almond Milk,2.49\"");
System.out.println("ADD ITEM to CART: \"5,Wheat Bread,1.49\"");
System.out.println("ADD ITEM to CART: \"2,OJ,3.49\"");
System.out.println("\n\t AND SHOW UPDATED CART ...");
** TO BE COMPLETED BY STUDENT **
obj.show();
System.out.println();
/**
* sort Items in Cart and SHOW CART WITH TOTAL COST (after each SORT)
*/
System.out.println("\n\t SORT Items by ID...");
** TO BE COMPLETED BY STUDENT **
System.out.println("\n\t SORT Items by PRICE...");
** TO BE COMPLETED BY STUDENT **
System.out.println("\n\t SORT Items by NAME...");
** TO BE COMPLETED BY STUDENT **
/**
* Remove Items from cart:
* "5,Wheat Bread,1.49"
* "3,Almond Milk,2.49"
*/
System.out.println("\n\t Remove Items from CART...");
System.out.println("\n\t Remove \"5,Wheat Bread,1.49\" ...");
System.out.println("\n\t Remove \"3,Almond Milk,2.49\" ...");
System.out.println("\n\t AND SHOW UPDATED CART...");
** TO BE COMPLETED BY STUDENT **
System.out.println();
4/29/22, 6:42 PM Final Cart
https://northeastern.instructure.com/courses/103210/assignments/1384388 4/4
/**
* add items to cart and SHOW CART with TOTAL COST
*/
System.out.println("ADD ADDITIONAL Items to Cart...");
System.out.println("ADD ITEM to CART: \"6,Swiss Cheese,6.49\"");
System.out.println("\n\t AND SHOW UPDATED CART ...");
** TO BE COMPLETED BY STUDENT **
System.out.println();
System.out.println("ADD ITEM to CART: \"7,Blue Cheese,6.49\"");
System.out.println("\n\t AND SHOW UPDATED CART ...");
** TO BE COMPLETED BY STUDENT **
System.out.println();
System.out.println("\n\t" + Cart.class.getName() + ".demo()... done!");
}
