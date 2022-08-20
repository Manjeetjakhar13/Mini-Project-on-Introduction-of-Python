# mini-project-on-introduction-of-python
For a seamless eCommerce shopping experience, it is essential to deliver the product promptly to the customer. And that’s where a professional courier service plays a vital role. 'FastTrack' courier company stores the relevant data of its clients and parcels in the form of dictionary
problem statement::::
 Create a dictionary for storing shipment information in key-value pairs. Shipment id is used as a key and list of other attributes like sender, receiver, start date, Delivery Date, Sender_location, Receiver_location, Delivery status, Shipping cost is associated with shipment id. Use the data shown in the table below.
 
Use below table to refer to client’s data. Please note that a client can be a sender or receiver.
 
Q1. Create a Dictionary of lists to store the information of shipments given in the table

Q2. Create a Dictionary of to store the information of clients given in the table.

Q3. Write a code to replace client’s id with their respective name in shipment dictionary using a loop and dictionary comprehension

Q4. Print all shipment details that are sent by Phillip

Q5. Print all shipment details that are received by Ramya

Q6. Print all shipments which are in 'In-Transit' status

Q7. Print all shipments which are delivered within 7 days of courier Start date

Q8. Print all shipments which are delivered after 15 days of courier start date or not yet been delivered.

Q 9. Write a function find_all_routes to display all possible routes from senders location to receivers location given in the dictionary for each shipment.¶

Graph data structure is used to represent network of pickup and delivery nodes. Consider a below graph diagram for given nodes in the table where sender location and receiver location is represented by node with number.
Connection between two nodes shows route exists between those areas. E.g there exists a path from area 1 to area 2 but there is no direct route between area1 and area5. please note that this routes are bidirectional.
To reach to area5 from area1 , delivery person can take any route like 1-2-4-5 or 1-2-3-4-5


 
Any graph like reqired can be represented by matrix shown below. presence of 1 represents the route between nodes and 0 represents there is no direct route exist between the nodes. Create matrix for the network shown above and using this matrix find all possible routes from A to B. 
 
