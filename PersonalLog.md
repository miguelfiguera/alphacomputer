## AlphaComputer Project:

Requeriments (They are not in the order to tackle):

1. Able to read a excel sheet and create objects from there (inventory).
2. Has admins, has users.
3. Has a shopping cart.
4. Has a message platform to talk with the admins.
5. Uses devises for authentication.
6. Has a dashboard for the admins.
7. Creates a email bill and send it to the client.
8. creates an email order to the admin and send it through email.
9. Implements all the rails tests that it has to implement.
10. Has well done commits.
11. User can add items to the shopping cart.
12. Users can login and register using google.
13. Orders had the possibilitie to updated status to "Payment Complete"
14. orders are created with the status of "pending Payment"
15. Orders should be updated manually by user as venezuelan banks does not have APIs that I can use.
16. After the order gets updated to "Payment Complete", it should send an email to admin, with the order items and quantity.
17. Users should have a profile for demographic data.
18. It should update the inventory with each order.
19. It should replace the inventory with each load of excel, creating new items if they are not in the inventory and updating quantity if they exist.
20. Admin should be able to report as "nulified" the orders that meet that status.
21. Checking for all orders is for the admins, and checking for owned orders for the clientes/users.
22. No blog but all posts of instagram or maybe tiktok videos...
23. StaticPages controller for: About, Help, Home.
24. Layout should have the business logo.

---

Possible Asociations:

User:

1. User has one shopping cart
2. User has many orders
3. User has many items through shopping cart
4. Has one profile

Shopping Cart:
1. has many items
2. belongs to user

Admin:
1. I do not know yet...
2. But the app should detect which admin is online and create the messages only with that admin.

Items:
1. belongs to shopping cart.

Orders:
1. Belongs to users

---


GEMS to install later: 

1. Standard
2. Device
3. One for xls or excel.
4. googlea omniauth

---

Questions for Matt:
1. Should I deploy from the beginning to avoid problems?
2. And if that is not possible, should I start coding on branches and mergin later?

User notes:
1. Admin should be differentiated by the boolean nature of a attribute called "admin" so evaluation should be easy as #admin? method.