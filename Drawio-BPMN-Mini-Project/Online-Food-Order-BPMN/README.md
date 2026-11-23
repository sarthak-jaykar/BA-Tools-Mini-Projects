# Draw.io / BPMN Mini-Project — Online Food Order Process

![Draw.io](https://img.shields.io/badge/Tool-Draw.io-F08705)
![BA Practice](https://img.shields.io/badge/Focus-Business%20Process%20Analysis-2457A7)

## Business scenario

This exercise models an online food-order journey involving three participants: the customer, restaurant, and delivery partner.

## Objective

Analyse a simplified current-state process, identify potential friction points, and communicate a proposed future-state flow using BPMN-style process modelling in Draw.io.

## AS-IS analysis — observed process issues

1. **Manual order validation:** restaurant staff manually check an order before accepting it, which may delay confirmation.
2. **Late delivery coordination:** the delivery partner is involved only after food preparation begins, potentially creating avoidable pickup waiting time.
3. **Payment before order acceptance:** payment is collected before restaurant confirmation, so a rejected order requires a refund step.

## TO-BE considerations

1. **Earlier validation:** use an automated validation step where appropriate to reduce manual checking.
2. **Earlier delivery notification:** notify the delivery partner sooner to improve coordination.
3. **Clear rejection and refund handling:** make rejection communication and refund processing explicit in the proposed flow.

These are proposed process improvements for the exercise, not measured operational outcomes.

## Process diagrams

| AS-IS process | TO-BE process |
|---|---|
| ![Online food order AS-IS](OFO-AS-IS%20Process.drawio.png) | ![Online food order TO-BE](OFO-TO-BE%20Process.drawio.png) |

[Open editable Draw.io source](Online-Food-Order-Process-BPMN.drawio).

## Modelling elements used

- Start and end events
- Tasks and sequence flows
- Exclusive gateway
- Swimlanes for Customer, Restaurant, and Delivery Partner

## Business Analyst relevance

The exercise demonstrates a basic process-analysis cycle: understand the existing workflow, identify handoff and control issues, and represent a proposed process so stakeholders can review the changes.

## Interview summary

“I modelled an online food-order process across Customer, Restaurant, and Delivery Partner swimlanes. I reviewed the AS-IS flow, identified potential delays around manual validation, delivery coordination, and payment before acceptance, and created a TO-BE model to make the proposed improvements explicit.”

## Author

[Sarthak Jaykar — GitHub](https://github.com/sarthak-jaykar) · [LinkedIn](https://www.linkedin.com/in/sarthak-jaykar/)
