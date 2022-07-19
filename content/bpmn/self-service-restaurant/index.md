---
title: 'Self-service restaurant'
weight: 2
---

## Background

A self-service restaurant is under chaotic conditions. Guests place their order at the till and receive their meals on call from the kitchen. As the restaurant is very popular, the processes need to be adapted to the increasing demand.

In the future, guests should only interact with one member of the staff when placing their order. The chef should purely be concentrating on preparing the meals. Buzzers will be introduced to signal to customers when their order is ready.

### Task: Create a model of the following optimized process.

A guest enters the restaurant when feeling hungry. He chooses a dish from the changing menu and waits until it is his turn. The guest then places his order with the employee. The employee enters the order into the POS system and collects the money from the guest.

After the payment, the employee sets up a buzzer and passes it on to the guest with the following information: “When the buzzer rings, your dinner is ready.” After setting the buzzer, the employee informs the chef of the new order. The chef prepares the meal and places it in the service hatch. The chef then tells the employee that he has placed the cooked meal in the service hatch.

As soon as the employee is aware that the order is ready, he sets off the guest’s buzzer. This is how the guest finds out that his dinner is ready for collection. He can now pick up his food and eat it. The employee hands over the tray with the meal when the guest appears at the service hatch. If a guest does not react to the buzzer, the employee calls him after 5 minutes, if necessary several times in a row.

**Hints**

Use 3 different pools for the model:
* Guest (food consumption)
* Employee (order processing)
* Chef (meal preparation)