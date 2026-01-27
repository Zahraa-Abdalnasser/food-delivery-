# food-delivery-
A restaurant browsing and ordering system designed to simplify the process of exploring restaurants, viewing menus, and placing orders

<h2> System Key Features : </h2>
<h3> 1. Restaurant Browsing: </h3>
Users can browse through a list of available restaurants and view
their details, including location, cuisine type, ratings, and customer reviews. This feature
provides users with a comprehensive overview of the available dining options.

<h3> 2. Menu Viewing: </h3>
Users can access restaurant menus, explore dierent categories, and
view item details such as descriptions, prices, and availability. This functionality allows
users to make informed decisions based on their preferences.

<h3> 3. Cart Management: </h3>
Customers can add items to their cart, modify quantities, and remove
items if needed. The cart provides a summary of the selected items and calculates the
total cost, allowing users to review their order before proceeding to checkout.

<h3> 4. User Registration and Login: </h3>
User registration and login system to
provide a personalized experience for users. Registered users can manage their pro les,
track order history, and receive personalized recommendations.
<h3> 5. Order Placement and Conrmation: </h3>
Once the user is ready to place an order, they can
proceed to checkout, select the preferred payment method, and provide delivery or
pickup details. Upon successful order placement, users receive con rmation along with
an estimated delivery or pickup time.

<h3> 6. Notifications System : </h3>
The system would notifiy the customer about their order at it's different stages (e.g placed , on the way , deliverd sccessfully).

<h3> 7. Cross platform cabability : </h3>
The systme should be allowed to work on multiple opearating systems (e.g ios , android , windows ,...etc ).

<h3> 8. Secure payment integration : </h3>
The systme should have a very secured and protected payment ways.

<h2> Functional Requirments :</h2>

 <h3> 1. User must be able to create a profile in easy way . </h3>
 <h3> 2. User can edit their profile data . </h3>
 <h3> 3. User can login from differnt devices . </h3>
 <h3> 4. User can browse food by category , location or price . </h3>
 <h3> 5. User can add , remove items from the cart . </h3>
 <h3> 6. User can't edit their order after submmiting the order . </h3>
 <h3> 7. User have the ability to choice the payment way they prefer . </h3>
 <h3> 8. User can track their order untile delivery . </h3>
 <h3> 9.User can rate the resturent or the order . </h3>

 ## Non Functional Requirments :
 ### 1. Simple and easy to use interface .
 ### 2. Systme should have 2 versions for mobile and web .
 
# Place order diagrams:
## Flow Chart:
![Digram](https://raw.githubusercontent.com/Zahraa-Abdalnasser/food-delivery-/refs/heads/main/FlowChart.drawio.svg)

## Sequence diagram:
![Digram](https://raw.githubusercontent.com/Zahraa-Abdalnasser/food-delivery-/refs/heads/main/Food%20delivery%20Sequence%20diagram.drawio.svg)

## Entity Relationship:
![Diagram](https://raw.githubusercontent.com/Zahraa-Abdalnasser/food-delivery-/refs/heads/main/Entity%20Relationship%20Diagram.drawio.svg)

## Pseudo code:
```
                                    function place-order(object cart )
                                     {
                                         check-payment-method;
                                         Enter-address-info;
                                         save(cart);
                                         print(successfully submitted order!);
                                        send-notification();
                                     }

```
