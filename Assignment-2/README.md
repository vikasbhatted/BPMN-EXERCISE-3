# Assignment 2: Logistics and Shipment Management

## Overview
This BPMN diagram represents the shipment process, from booking and parcel pickup to inspection, delivery, and handling of exceptions.

## Process Flow

1. **Create Shipment Booking:** The shipper books a shipment.
2. **Validate Booking:** The logistics coordinator validates the booking and calculates charges. Invalid bookings are returned for correction.
3. **Schedule Pickup:** A pickup agent is assigned.
4. **Collect and Scan Parcel:** The pickup agent collects and scans the parcel.
5. **Sort and Move Parcel:** The parcel is moved to the destination hub. Parallel gateways represent the parallel activities and their synchronization.
6. **Inspect Parcel:** The parcel is checked for damage.
7. **Handle Damage:** If the parcel is damaged, the claims department settles the claim through a refund or replacement.
8. **Deliver Parcel:** If the parcel is not damaged, the delivery agent notifies the recipient and attempts delivery.
9. **Recipient Decision:** The recipient accepts or refuses the parcel.
   - **Accepted:** Proof of delivery is recorded, the shipment is closed, and the invoice is processed.
   - **Refused:** The parcel is returned to the sender.
10. **End Events:** The process ends with shipment delivery, return to sender, or claim settlement.

## BPMN Elements Used
- Start and End Events
- User Tasks and Service Tasks
- Exclusive Gateways for validation and decisions
- Parallel Gateways for concurrent activities
- Sequence Flows
- Swimlanes to represent responsibilities

## Outcome
The process handles successful deliveries as well as damaged parcels and refused deliveries.
