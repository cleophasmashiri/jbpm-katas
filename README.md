#### Business Problem: Exclusive Gateway-Pizza Delivery.
You are required to implement exclusive gateway for Pizza delivery to enable the following: 
* If a customer selects delivery option "Home Delivery" then delivery method is set "homeDelivery". 
* if a customer selects delivery option "Collect" then delivery is set "collect". 
* If customer does not select delivery method "voucher" is selected. * For each branching option add script task that populates the order's actions property as order.addAction("action"), where action could be: "Collected", "Home Delivered" or "Voucher Created".

#### Instructions 
1. Clone initial project: 

```
git clone https://github.com/cleophasmashiri/exclusive-gateway-pizza-delivery-initial.git 2\. cd into exclusive-gateway-pizza-delivery-initial and run tests. 
```
Run tests.
```
mvn clean test 
```

3. Import project "exclusive-gateway-pizza-delivery-initial" into jbpm business central.

4. Create process model: ExclusiveGatewayPizzaDelivery. 

5. Run tests to vesrify your implementation.
```
mvn clean test
```
6. Compare your solution with final one below. 
[https://github.com/cleophasmashiri/exclusive-gateway-pizza-delivery-initial.git](https://github.com/cleophasmashiri/exclusive-gateway-pizza-delivery-initial.git)

For more articles go to: [https://www.bpmkatas.com/](https://www.bpmkatas.com/).
