# Muesli-Sebastian-Deming

## Delivery process

```mermaid
  flowchart TD;
      New_Order-->Order_Received_Day_1;
      Order_Received_Day_1-->Order_Processed_Day_2; 
      Order_Processed_Day_2-->Ready_to_Ship_Day_2;
      Ready_to_Ship_Day_2-->Regular_Delivery;
      Ready_to_Ship_Day_2-->Express_Delivery;
      Regular_Delivery-->Order_Leaves_Warehouse_Day_3;
      Express_Delivery-->Order_Leaves_Warehouse_Day_3;
      Order_Leaves_Warehouse_Day_3-->Order_Delivered;
```

### Order_Received_Day_1
Customers can send orders every day but the warehouse only works Monday to Friday so any orders received on the weekends wait until Monday to be actioned.

### Order_Processed_Day_2
--> **Mo-Fr**

### Order_Leaves_Warehouse_Day_3
Trucks Leave the warehouse on Mondays, Wednesdays and Fridays. Orders leave on trucks the day after they are made ready for shipping (or two days later if there is no truck).  --> **Mo, Mi, Fr**
Customers can pay for Express Processing that means the orders leave on the truck the day the order is ready for shipping.
