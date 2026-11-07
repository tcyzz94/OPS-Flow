# OPSFlow — Product Brief

## 1. Purpose

OPSFlow helps employees request purchase approvals and manage inventory so that businesses can track approval decisions, stock levels, and product expiry.

## 2. Problem Statement

### Current Process

Purchase approvals are handled through email or SMS without being recorded in a central system.

### Main Problems

- Inventory sometimes cannot meet demand.
- Expiring products can be overlooked in large inventories.
- Purchase approval records are scattered across messages.
- Business owners lack visibility into product performance.

### Impact

These problems make it difficult to identify replenishment needs, manage ageing stock, and trace past approval decisions.

Product performance reporting is outside the first version’s scope.

## 3. Target Users and Responsibilities

| Role                | Responsibilities in OPSFlow                                                                                              | Included in MVP? |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| Employee / operator | Submit purchase requests, record incoming goods, and enter inventory and expiry information.                             | Yes              |
| Boss / approver     | Review purchase requests and record approval decisions.                                                                  | Yes              |
| Purchasing officer  | Procurement responsibilities currently sit within the employee role. Whether a separate role is needed is **to decide**. | To decide        |
| Admin               | Responsibilities have not yet been defined.                                                                              | To decide        |

**To decide:** Whether “boss” and “manager” represent the same approver role, and whether operators need distinct permissions for procurement and warehouse work.

## 4. Three Core Use Cases

### Use Case 1 — Request Purchase Approval

- **Actor:** Employee / operator and boss / approver.
- **Goal:** Obtain and retain a recorded purchase approval.
- **Starting condition:** An employee identifies a purchasing need.
- **Main steps:**
  1. The employee submits a purchase request.
  2. The boss reviews the request.
  3. The boss records an approval decision.
- **Expected result:** The decision is stored and can be checked later.
- **To decide:** Required request information, rejection behavior, and who may approve each request.

### Use Case 2 — Record Incoming Inventory

- **Actor:** Employee / operator.
- **Goal:** Keep inventory records up to date when goods arrive.
- **Starting condition:** A shipment arrives at the warehouse.
- **Main steps:**
  1. The operator records the received items.
  2. The system increases the recorded inventory quantities.
- **Expected result:** Inventory reflects the received goods.
- **To decide:** How receipts relate to approved requests and which actions decrease inventory.

### Use Case 3 — Identify Expiring Stock

- **Actor:** Employee / operator.
- **Goal:** Identify stock that needs attention because of its expiry date.
- **Starting condition:** The operator has recorded expiry information for received goods.
- **Main steps:**
  1. The operator enters expiry information when goods arrive.
  2. The system identifies expired or soon-to-expire stock.
  3. The system makes the warning available to users.
- **Expected result:** Users can identify affected stock and take action.
- **To decide:** The warning threshold and whether warnings appear in the system or are sent as notifications.

## 5. MVP Scope

### Included

- Purchase-request approval and recorded approval history.
- Inventory tracking.
- Expiry warnings.

### Out of Scope

- Purchase order creation.
- Invoice approval.
- Payment processing.
- Product and sales performance reporting.
- Performance benchmarking.

## 6. Decisions to Clarify

- What information must a purchase request contain?
- Who may approve or reject a request?
- Are purchasing officer and admin separate roles in the MVP?
- Which activities decrease inventory?
- How are received goods connected to approved requests?
- What counts as “close to expiry”?
- Where will users see expiry warnings?

## 7. Expected Outcomes

OPSFlow aims to:

- Improve visibility into stock levels and replenishment needs.
- Help users identify ageing and expiring inventory.
- Make purchase approval decisions easier to trace.

Effectiveness will be assessed using recorded operational history after the system is completed. Specific success measures remain **to decide**.
