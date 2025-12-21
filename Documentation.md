# CRM CASE STUDY PROJECT

### **Background**

A company with multiple fashion brands wanted to understand which brand or brands were performing well, and which needed immediate attention due to poor performance. Data was available, yet a single view of insights was not accessible.

What was needed:
1. An automatic way to group each brand into one of the four stages: **Loyalty, Ad Spend Inefficient, Retention Risk, Healthy**.
2. A dashboard to show brand growth and their various growth stages over time.
3. A simple alert system to inform the team right away when a brand is classified as “Retention Risk.”

## STEPS

### **Step 1: Defining Key Metrics**

Three main performance metrics were identified:

**Return %** = (Return Amount / Total Sales) × 100

- **Why it matters**: Shows how much revenue is being lost to returns.
- **Business Impact:** High returns can signal product issues, customer dissatisfaction, or fulfillment problems.

 **Ad Spend ROI** = Net Sales / Total Ad Spend

- **Why it matters**: Tells you how much revenue is generated for every dollar spent on ads.
- **Business Impact**: Highlights marketing efficiency and helps stop wasted ad spend.

**AOV (Average Order Value)** = Net Sales / Order Count

- **Why it matters**: Shows how much customers spend per order.
- **Business Impact**: Higher AOV means more revenue with fewer transactions (better cost efficiency).

## **Step 2: CRM Logic Table – Stages & Triggers**

A CRM stage was created based on performance triggers:
| CRM Stage | Trigger Condition |
| --- | --- |
|  🔥 Retention Risk | Return % > 10% **OR** Net Sales ↓ 2 months in a row |
|  🔴 Ad Spend Inefficient | ROI < 1.2 |
| 🟢 Loyalty Opportunity | ROI > 2 **AND** Return % < 5% |
| ⚪️ Healthy | If it does not meet any of the conditions above |

<img width="1585" height="666" alt="Screenshot 2025-08-12 022022" src="https://github.com/user-attachments/assets/9ec6d9f5-a2be-4896-b6ee-e61ed86a2a79" />

## **Step 3: Dashboard for Brand Growth**

A Power Bi dashboard was developed to visualize :

- Number of brands
- Average Return on Interest
- Total Return % of all brands.
- Total Net Sales of all brands
- Net Sales by Brands.
- Top Retention Risk Account (Action Priority).
- Brands Performance Across CRM Stages.
- Net Sales Trends by CRM Stages

This makes it easier for decision makers to identify risk at a single glance and act accordingly.

<img width="1381" height="785" alt="Screenshot 2025-08-12 134642(1)" src="https://github.com/user-attachments/assets/6ed3fc77-198d-4586-bea9-06cfdbf0c48e" />

### **Step 4: Automating Alerts with Zapier**

To make sure no “Retention Risk” notice slipped through the cracks, a **Zapier automation** was set up to send an immediate message to the team.

Whenever a brand was flagged as a Retention Risk in the CRM retention logic table, an automated alert was sent to the team via zapier to alert the team into taking immediate actions with details such as:

**Subject:**

Brand Retention Alert 🚨

**Body:**

Hello Team,

A customer has been flagged as a Retention Risk.

• Brand: Brand A

• Return %: 14.2%

• Ad Spend ROI: 0.93

• CRM Stage: 🔴 Retention Risk

https://github.com/user-attachments/assets/18ce5da1-56b3-4bb8-be2b-a3445fe83c4e

This allows the team to act immediately, without waiting for a manual review.

## **Outcome & Impact**

 Client can now **quickly identify** brands at risk.

Marketing and sales teams receive **instant alerts** when action is required, which saves time and resources.

Dashboard provides a clear growth snapsho**t** for decision-making.

CRM pipeline stages are data-driven and transparent.


