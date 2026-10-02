| OP-Id | Operation | Purpose |
|---|---|---|
| OP-01 | Receive Delivery Request | Accept the customer order, pickup location, destination, and delivery priority. |
| OP-02 | Validate Order Details | Check item information, address accuracy, route constraints, and service rules before dispatch. |
| OP-03 | Assign Delivery Task | Match the request to an available autonomous vehicle and assign the delivery mission. |
| OP-04 | Pre-Trip System Check | Inspect vehicle sensors, battery level, navigation modules, and safety status. |
| OP-05 | Load Cargo | Secure the package or payload onto the vehicle in a safe and balanced manner. |
| OP-06 | Initialize Navigation Plan | Generate the route from the current position to the delivery destination using map and traffic data. |
| OP-07 | Begin Vehicle Movement | Start the autonomous vehicle and transition from idle mode to active transit. |
| OP-08 | Monitor Road Conditions | Track obstacles, traffic signals, lane position, and environmental changes during transit. |
| OP-09 | Navigate to Destination | Follow the planned route and adjust steering, speed, and pathing to reach the drop-off point. |
| OP-10 | Deliver Package | Stop at the target location, confirm safe arrival, and complete the drop-off task. |
| OP-11 | Update Delivery Status | Record the successful delivery event and communicate completion to the control system or operator. |
| OP-12 | Return to Base | Send the vehicle back to the depot or base station after completing the mission and confirm system readiness for the next task. |
