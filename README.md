# M5stack-Project
M5Stack Project on Smart Retail solutions 

MunKart V3.0 Is the latest update to the MunKart Smart Retail M5Stack. Here is the basic flowchart. 

1. User scans item against RFID. The Three Items are "DBS", "WV" and "NYP"
2. When the User scans against the RFID, the code will check for the RFID. The RFID is already pre-registered in the code and will assign the respective name to it.
3. On the M5stack home screen, the text "[Item} has been added to cart!" will show up. On the same home screen there is the price of the three different products.
4. When the user double-presses Button C, they are introduced to a new page called the "Cart Menu" with the Item Name, Quantity, and Price. The Quantity and the Price will be updated when the user scans any item against the RFID, Note: User has to press Button C again to see the refreshed changes because we are not fucking updating it to the cloud.
5. After finishing their shopping, if the user long-presses Button C, it will erase the quantity and the price of the items and the words "Checkout Complete!" will show up.
6. If the user presses Button C while they are in the "Cart Menu" page, it will bring him back to the home page where he will see the prices of the different items.
7. If the user presses Button B, he will go to a new page called the "Employee's Page" where they are able to see the stock of the three different items.
8. If the user presses Button A once, the stock for item "DBS" will be reset to its original which is 15.
9. If the user presses Button A twice, the stock for the item "WV" will be reset to its original which is 20.
10. If the user long-pressess Button A, the stock for the item "NYP" will be reset to its original which is 10.
11. MunKart is also able to detect if the item has reached a certain limit and will light up the color "red" if the item's stock has exceeded the limit or if it is 0, along with a "Restock Alert" label on the m5stack. The M5stack will also not update the quantity if the item is scanned against the RFID unless the stock is reset.
