# llSPS-INT-1224-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding

This is my internship project of building a Intelligent Customer Helpdesk Chatbot with Smart Document Understanding. I have built it using 
the services of IBM Cloud.


So this project is basically building a better chatbot than a typical Customer Care Chatbot.
A typical Customer Care chatbot, can answer simple questions like the location and hours of the store, greetings to the customer and also make an appointment if possible. If any question or query falls out of the pre-determined question set, it either states that the question is invalid or connects the user to an agent which in turn wastes the time of the customer.

So the purpose of this project is to solve this problem. In this project there will be another option .We use an extra feature of Watson Discovery i.e., Smart Document Understanding (SDU). With the help of this feature we train our assistant with the pre-loaded user manual of the particular product and when the customer asks a query related to the product, the chatbot uses the Watson Discovery service to search for the answer in the document and gives a relevant answer instead of connecting the user to an agent. So unless and until the customer himself asks the assistant to connect to a customer representative the assistant will answer all of the queries. 

To take it a step further, this feature also helps Discovery to train to what text in the document is important and what is not. This will improve the answers returned by the assistant. Node red is used to create a UI for the chatbot which can be deployed and so can be used anywhere

I have used Tesla Car manual as the document for Watson Discovery.

Node-RED Dashboard Link after deploying:- https://node-red-ijowm.eu-gb.mybluemix.net/ui/

Youtube Video link:- https://youtu.be/xjMbgbF5CBU
