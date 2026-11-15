# Fold â€” personal finance planner

Open `index.html` in a modern browser to use the app. The first visit creates a local profile for Soumya De (name, age, income, baseline expenses, existing investments, and existing SIPs). It stores its data in that browser's local storage, so no information is sent anywhere.

The goal planner calculates an inflation-adjusted future target, future value of the starting corpus and recurring SIPs, and the monthly SIP required to meet the remaining target. Saved goals can be opened and edited, and the roadmap compares target dates with the projected completion date at the SIP currently assigned to each goal.

The overview includes a household budget view and a step-up SIP projection for 5, 10, 20, and 30 years. Its estimates compound monthly at the annual return divided by 12, invest each SIP at the beginning of the month, and increase the SIP once each year by the selected step-up percentage. Figures are illustrative and exclude taxes and fees.

The budget uses take-home income, the higher of baseline monthly expenses or expenses logged in the current month, existing monthly SIPs, and the additional SIP required across goals. Expense entries update the view as they are recorded.

