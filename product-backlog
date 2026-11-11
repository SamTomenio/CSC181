# Product Backlog

# Team Information

Team name: Wattsupes  
Project title: Iligan WattsApp: Personal Energy Reverse-Budgeting Calculator for ILPI Consumers  
Primary user group for the first release: Student boarders   
Format: User stories with one use case

| Member | GitHub username | Personal CSC181 repository |
| :---- | :---- | :---- |
| Michael Andre L. Novela | Michael-Andre-Novela | https\://github.com/Michael-Andre-Novela/csc181 |
| Sam B. Tomenio | SamTomenio | https\://github.com/SamTomenio/CSC181/tree/main/Activities |
| Jericho Zhadraq S. Villadolid | Jericho-Villadolid | https\://github.com/Jericho-Villadolid/CSC181 |
| Winchester T. dela Vega | AikawaKun9 | https\://github.com/AikawaKun9/csc181 |

# 1\. Interview Summary

List the interviews or observations your team conducted. Use roles and codes, not names or contact details. Include at least two stakeholder groups.

| Code | Stakeholder role | Date | Method | Interviewer(s) |
| :---- | :---- | :---- | :---- | :---- |
| V1 | Student boarder — 8bcfe38 | 2026-10-23 | Google Forms (online survey) | Wattsupes (team-owned form) |
| V2 | Student boarder — 2bbc4e6 | 2026-10-23 | Google Forms (online survey) | Wattsupes (team-owned form) |
| V3 | Student boarder — ed3eeaa | 2026-10-23 | Google Forms (online survey) | Wattsupes (team-owned form) |
| V4 | Student boarder — 60e8dc1 | 2026-10-23 | Google Forms (online survey) | Wattsupes (team-owned form) |
| H1 | Residential household — c4a812f | 2026-10-26 | Google Forms (online survey) | Wattsupes (team-owned form) |
| H2 | Residential household — b892d11 | 2026-10-26 | Google Forms (online survey) | Wattsupes (team-owned form) |
| H3 | Residential household — d2190f4 | 2026-10-26 | Google Forms (online survey) | Wattsupes (team-owned form) |

# 2\. From Interview Notes to Needs

Record at least 8 findings. Follow the worked example on Week 4, slide 10\. Type is F (functional), Q (quality / non-functional), or C (constraint). See Week 4, slide 7\.

| ID | Source | What we heard or saw | Underlying need | Requirement idea | Type |
| :---- | :---- | :---- | :---- | :---- | :---- |
| F1 | V1, V2, V3, V4, H2, H3 | Six of the seven respondents found it extremely or somewhat difficult to convert a monthly peso budget into daily appliance operating hours. | Translate a fixed budget into practical usage limits. | Calculate estimated allowable daily hours using budget, electricity rate and appliance wattage. | F |
| F2 | V2, V3, V4, H3 | Four of the seven respondents do not track their electricity usage and rely on the monthly bill to learn how much they consumed. | See costs before billing arrives. | Display projected electricity expenses based on entered appliance usage. | F |
| F3 | V1, V2, H1, H3 | Four respondents preferred appliance presets with editable wattage. | Set up appliance profiles quickly without losing flexibility. | Provide appliance presets whose wattage can be edited. | F |
| F4 | V3, V4 | Two student boarders preferred entering exact wattage shown on  an appliance’s label. | Use an appliance's own rated power instead of only defaults. | Allow custom wattage entry from a backplate or sticker. | F |
| F5 | H1 | One respondent from a multi-family household preferred reducing the use of lights and televisions, rather than limiting cooling, citing heat-related health concerns. | Evaluate savings while protecting important household uses. | Let users compare costs after adjusting selected appliance hours. | F |
| F6 | V1, V2 | V1 requested daily usage tracking and monthly bill estimates; V2 requested a real-time bill calculator. | Check changing cost estimates while planning usage. | Update daily and monthly projected costs when planned hours change. | F |
| F7 | H3 | Respondent requested comparing appliance running costs (fans, air conditioners or PCs). | Make informed trade-offs between appliance choices. | Compare projected consumption and costs for alternative appliance plans. | F |
| F8 | H2 | Respondent requested proactive alerts when projected monthly consumption approaches a budget limit. | Notice projected overspending before the bill arrives. | Show a warning when the projected cost reaches a configured threshold. | F |
| F9 | V2, V3, V4, H2, H3 | Five of the seven respondents selected weekly usage-limit setting/review rather than daily dynamic monitoring. | Plan and revisit an electricity allowance over a week. | Support weekly usage-limit planning and review. | F |
| F10 | V4 | One respondent suggested scanning a bill or landlord notice to determine cost per kWh. | Reduce manual work when entering an effective rate. | Consider bill-image rate capture as a proposed enhancement. | F |
| Q1 | H2 | One respondent specifically requested offline budget threshold alerts. | Get a budget warning without requiring connectivity. | Display projection-based threshold alerts while offline. | Q |
| C1 | V2, V3 | Two student boarder respondents report variable electricity rates set by landlords. | Use a rate that reflects individual billing arrangements. | Do not assume one fixed utility rate; let users enter an effective rate. | C |

## Assumption log

List things the team believes but has not confirmed. See Week 3, slide 19\.

| ID | Assumption | Risk if wrong (High/Medium/Low) | How we will check it |
| :---- | :---- | :---- | :---- |
| A1 | Users can identify reasonably representative wattage values and estimate daily operating hours for their appliances. | High | Ask participants to set up a real appliance using its label and compare estimates with their reported usage. |
| A2 | Users will understand that projected electricity costs are estimates rather than actual meter readings. | High | Conduct a usability walk-through and ask participants to explain the projected-cost label and its limitations. |

# 3\. User Stories

Write 10 to 15 stories. Every story cites at least one finding ID. Mark the INVEST check Yes only after team review. See Week 4, slides 14–17.

| ID | User story | Source finding(s) | Epic | INVEST check |
| :---- | :---- | :---- | :---- | :---- |
| US-01 | As a student boarder, I want to set a monthly electricity budget so that I can plan appliance use within my allowance. | F1 | Electricity budget setup | Yes |
| US-02 | As a student boarder paying a landlord-set electricity rate, I want to enter my effective cost per kWh so that my estimates reflect what I am charged. | C1 | Electricity budget setup | Yes |
| US-03 | As a household consumer, I want to select an appliance from a preset library so that I can create an appliance profile without knowing its wattage beforehand. | F3 | Appliance profile setup | Yes |
| US-04 | As a student boarder, I want to enter an appliance's rated wattage manually so that the calculation can use the value on its label. | F4 | Appliance profile setup | Yes |
| US-05 | As a student boarder, I want to enter planned daily operating hours for an appliance so that I can estimate its electricity cost. | F6 | Usage planning and estimation | Yes |
| US-06 | As a student boarder, I want to calculate the estimated daily hours available for one selected appliance after accounting for my other planned usage, so that I can keep my total projected cost within my monthly budget. | F1 | Usage simulations | Yes |
| US-07 | As a residential household consumer, I want to see a projected monthly electricity cost based on planned appliance use so that I can anticipate a bill increase. | F2, F6 | Usage planning and estimation | Yes |
| US-08 | As a household consumer, I want to compare the estimated cost of two daily operating-hour options for one appliance, so that I can choose the more affordable schedule. | F5, F7 | Usage simulations | Yes |
| US-09 | As a student boarder, I want to review and adjust a weekly electricity usage limit so that I can revise my plan as my schedule changes. | F9 | Electricity budget setup | Yes |
| US-10 | As a household consumer, I want to see an in-app warning when my projected monthly cost reaches my entered monthly budget, even without internet access, so that I can adjust my planned usage. | F8, Q1 | Electricity budget setup | Yes |
| US-11 | As a student boarder, I want to save my current appliance plan on my device so that I can reopen it during my weekly review without re-entering the values. | F9 (inferred need; validate) | Usage planning and estimation | Yes |
| US-12 | As a student boarder, I want the app to suggest an electricity rate from a photo of one printed bill for my confirmation, so that I can reduce manual rate entry. | F10 | Rate capture (future option) | No — OCR feasibility/sizing pending |

## Epics and how we split them

List each epic and stories it was split into. Name splitting approach: workflow step, business rule, data type, or happy path first. See slide 18\.

| Epic | Split into | How we split it |
| :---- | :---- | :---- |
| Electricity budget setup | US-01, US-02, US-09, US-10 | By workflow step and rule: set budget, enter rate, review weekly limit, then warn at budget threshold |
| Appliance profile setup | US-03, US-04 | By input method: preset selection and manual rated-wattage entry |
| Usage planning and estimation | US-05, US-07, US-11 | By workflow step: plan hours; view projection; save plan |
| Usage simulations | US-06, US-08 | By calculation type: affordable operating hours for one appliance, then a two-option cost comparison |

## Stories we rewrote

Give at least two examples of stories rewritten or split, and why. See Week 4, slide 17\.  
1\. Before: As a student boarder, I want to manage my budget, appliance hours, and bill estimate all at once.  
   After: US-01 (monthly budget), US-05 (planned daily hours), and US-07 (monthly cost projection).  
   Reason: The original bundled multiple distinct outcomes, making it too large and difficult to test (Small, Testable).  
2\. Before: As a residential consumer, I want a smart app that predicts my exact electricity bill.  
   After: US-07: View a projected monthly cost based on entered appliance usage.  
   Reason: The original implied meter accuracy or predictive intelligence that the app does not provide (Testable, Estimable).

# 4\. Acceptance Criteria

Draft acceptance rules for team approval. Recommended Must-have stories: US-01, US-02, US-04, US-05, US-06, US-07 and US-10. These seven each have normal and unhappy-path Given–When–Then scenarios. Section 8 must use matching priorities and verify that Must-haves fit the team's two-sprint capacity.

Shared calculation assumptions for these draft tests: 30-day planning month, user-entered flat effective rate (₱/kWh), constant entered appliance wattage, and estimated usage; the results do not represent live meter readings or the final utility bill. Numbers below are test fixtures, not verified ILPI tariffs or stakeholder-approved accuracy targets.

## US-01: Set a monthly electricity budget

Acceptance criteria:

☐ Given an empty budget field, entering ₱1,500 and saving records a monthly budget of ₱1,500.

☐ The saved monthly budget is displayed on the planning screen and is used in subsequent projections.

☐ (unhappy) When the amount is zero, negative, or not numeric, saving is blocked and an input error is shown.

Scenario 1: Normal case

Given the budget field is empty

When the user enters ₱1,500 and saves

Then the monthly budget displays ₱1,500 and remains available for calculations

Scenario 2: Unhappy path

Given the current saved budget is ₱1,500

When the user enters −₱100 and attempts to save

Then the app shows a validation message and retains the ₱1,500 budget

## US-02: Enter effective electricity rate

Acceptance criteria:

☐ Entering a positive effective rate in ₱/kWh stores that value for future cost calculations.

☐ A cost estimate uses the user-entered rate rather than a fixed default rate.

☐ (unhappy) A rate of ₱0, a negative rate, or nonnumeric text is rejected without replacing the last valid rate.

Scenario 1: Normal case

Given the monthly budget is ₱1,500 and no rate has been set

When the user enters ₱12.50/kWh and saves

Then the rate shown is ₱12.50/kWh and subsequent estimates use that value

Scenario 2: Unhappy path

Given the saved rate is ₱12.50/kWh

When the user tries to save a rate of ₱0/kWh

Then the app displays a rate validation error and preserves ₱12.50/kWh

## US-03: Choose a preset appliance

Acceptance criteria:

☐ Selecting an appliance preset populates its name and an editable example wattage.

☐ The user can confirm the selected preset and add one appliance entry to the plan.

☐ (unhappy) If no preset is selected, the app does not add an empty appliance entry.

Given–When–Then scenarios: not required unless this story is upgraded to Must-have in Section 8\.

## US-04: Enter or edit rated appliance wattage

Acceptance criteria:

☐ Users can enter a positive wattage for a manually configured appliance.

☐ Updating the wattage of an existing appliance changes its subsequent calculated cost.

☐ (unhappy) A missing, zero, negative, or nonnumeric wattage is rejected and the prior valid value is retained.

Scenario 1: Normal case

Given a fan entry has a rated wattage of 60 W

When the user changes its wattage to 45 W and saves

Then the entry shows 45 W and later estimates use 45 W

Scenario 2: Unhappy path

Given the fan has a saved rating of 45 W

When the user tries to replace it with −20 W

Then the app shows a wattage validation error and retains 45 W

## US-05: Set planned daily appliance hours

Acceptance criteria:

☐ Users can enter planned daily operating hours from 0 through 24 for a single appliance.

☐ Changing planned hours refreshes that appliance's estimated consumption and cost using its wattage and the configured rate.

☐ (unhappy) Values below 0, above 24, or not numeric are rejected without updating the saved hours.

Scenario 1: Normal case

Given a 100 W appliance and an effective rate of ₱10/kWh are configured

When the user enters 5 planned hours per day

Then the app shows 0.5 kWh/day and ₱5/day for that appliance

Scenario 2: Unhappy path

Given an appliance has 5 saved hours per day

When the user enters 25 hours per day

Then the app displays an hours validation error and keeps 5 hours

## US-06: Calculate affordable daily hours for one appliance

Acceptance criteria:

☐ The calculation subtracts the projected monthly cost of other planned appliances from the user's monthly budget before allocating hours to the selected appliance.

☐ For a positive remaining budget, the app calculates allowable daily hours as remaining budget ÷ (selected wattage ÷ 1,000 × rate × 30), capped at 24 hours per day.

☐ (unhappy) If other planned costs meet or exceed the budget, the result is 0 allowable hours and the app explains that no estimated budget remains.

☐ (unhappy) If the selected wattage or rate is missing or nonpositive, the app requests valid inputs instead of dividing by zero.

Scenario 1: Normal case

Given the monthly budget is ₱1,500, other appliances total ₱900 per month, the selected appliance is 100 W, and the rate is ₱10/kWh

When the user calculates the selected appliance's allowable daily hours

Then the app shows 20 hours/day for a 30-day planning month

Scenario 2: Unhappy path

Given the monthly budget is ₱1,500 and other planned appliances already total ₱1,600 per month

When the user calculates hours for a 100 W appliance

Then the app displays 0 allowable hours and an explanation that the remaining budget is exhausted

## US-07: View projected monthly electricity cost

Acceptance criteria:

☐ The app totals estimated monthly consumption for the planned appliances using wattage ÷ 1,000 × daily hours × 30 days.

☐ The displayed projected monthly electricity cost equals total planned kWh multiplied by the entered ₱/kWh rate, and is labeled an estimate.

☐ (unhappy) If no valid rate is configured, the app prompts for a rate instead of showing a monetary projection.

Scenario 1: Normal case

Given one 100 W appliance is planned for 5 hours/day and the rate is ₱10/kWh

When the user views the monthly estimate

Then the app displays 15 kWh and a projected cost of ₱150 for a 30-day month

Scenario 2: Unhappy path

Given an appliance has valid wattage and planned hours, but no electricity rate is set

When the user opens the projected monthly cost

Then the app requests a rate and does not display an unsupported Peso amount

## US-08: Compare two operating-hour options

Acceptance criteria:

☐ Users can enter two daily operating-hour options for one appliance and view the estimated monthly cost of each option.

☐ The app displays the Peso difference between the two options using the same appliance wattage, entered rate, and 30-day planning month.

☐ (unhappy) If either option is below 0 or above 24 hours/day, the app blocks the comparison and identifies the invalid input.

Given–When–Then scenarios: add if this story is designated Must-have in Section 8\.

## US-09: Review and adjust a weekly usage limit

Acceptance criteria:

☐ Users can enter a nonnegative weekly planned-hours limit for a selected appliance, up to 168 hours per week.

☐ The app displays the saved weekly limit when the user returns to the weekly planning view.

☐ (unhappy) A weekly limit greater than 168 hours, negative, or nonnumeric is rejected and does not overwrite the previous limit.

Given–When–Then scenarios: add if this story is designated Must-have in Section 8\.

## US-10: Show an offline budget warning

Acceptance criteria:

☐ When the projected monthly cost equals or exceeds the saved monthly budget, the app displays a visible in-app budget warning.

☐ The warning uses locally stored budget, appliance, and rate inputs and does not require an internet connection.

☐ (unhappy) If the monthly budget is not configured, the app displays a prompt to set a budget instead of claiming the user has exceeded a threshold.

☐ The warning text identifies the amount as a projection, not actual meter consumption.

Scenario 1: Normal case

Given the user has a saved monthly budget of ₱1,500 and a projected monthly cost of ₱1,600.

When the user opens the planning screen while offline.

Then the app displays a budget warning indicating that projected expenses exceed the budget by ₱100.

Scenario 2: Unhappy path

Given the user has not configured a monthly budget.

When the app calculates projected monthly expenses.

Then the app prompts the user to configure a budget, instead of displaying an exceeded budget warning.

## US-11: Save and reopen an appliance plan locally

Acceptance criteria:

☐ Saving a plan stores the appliance name, wattage, and daily planned hours in local device storage.

☐ After closing and reopening the app without internet access, the saved plan can be reopened with the same values.

☐ (unhappy) If saving fails, the app shows an error and does not falsely report that the plan was saved.

Given–When–Then scenarios: not required unless this story is upgraded to Must-have in Section 8\.

## US-12: Suggest a rate from a bill image (future option)

Acceptance criteria:

☐ If bill-image recognition is implemented, the user can select one image and request a suggested ₱/kWh rate.

☐ A recognized rate is displayed for user confirmation and is not applied automatically.

☐ (unhappy) When no usable rate can be identified, the app shows an extraction failure message and allows manual rate entry.

Given–When–Then scenarios: add if this story is designated Must-have in Section 8\.

# 5\. Quality Requirements and Constraints (EARS)

Write at least 3, using at least two EARS patterns. Record who agreed to any number. See Week 4, slides 7 and 13\.

| ID | Requirement | EARS pattern | Type | Source | Number agreed with |
| :---- | :---- | :---- | :---- | :---- | :---- |
| NFR-01 | While the device is offline, the system shall allow users to calculate projected electricity costs and view budget threshold alerts using locally stored budget, rate, and appliance profiles.  | State-driven  | (Reliability / Portability)  | Q1, F8, F9  | Respondent b892d11  agreed with offline threshold warning and local storage  |
| NFR-02 | When the projected monthly cost reaches or exceeds 100% of the configured monthly budget, the system shall display a visible in-app budget warning notification.  | Event-driven  | (Usability / Alerting)  | F8, Q1  | Respondent b892d11  agreed with 100% threshold alert  |
| NFR-03 | The system shall compute estimated monthly electricity costs based on user-entered effective rates in ₱/kWh and rated wattage values without assuming a fixed utility tariff.  | Ubiquitous  | Constraint  | C1, F1, F4  | V2, V3 (Variable landlord billing rate agreement); 6 of 7 survey respondents  |

# 6\. Use Case

## Use-case diagram

Show system boundary, actors, and main use cases. See Week 4, slide 23\.

\!\[ERD\](use-case.png)

UC-01: **Plan Appliance Usage, Project Costs, and Calculate Allowable Operating Hours**  
Choose workflow with most steps or error paths. See Week 4, slide 24\.

| Field | Description |
| :---- | :---- |
| Primary actor | Student Boarder / Residential Household Consumer  |
| Precondition | The user has opened the **Iligan WattsApp** application on their device (device may be offline)  |
| Main success scenario | **1\.** User sets or updates their monthly electricity budget (in ₱) and effective electricity tariff rate (in ₱/kWh)  **2\.** The user configures an appliance entry by selecting a preset or entering a rated wattage value (in W). **3\.** The user enters planned daily operating hours (0–24 hrs/day) for configured appliances.  **4\.** The system calculates total projected monthly consumption (in kWh) and estimated monthly cost (in ₱). **5\.** The user selects one target appliance and requests allowable daily operating hours to stay within budget. **6\.** The system calculates the remaining budget, computes allowable daily operating hours for that appliance (capped at 24 hours/day), displays the result, and saves the plan locally. |
| Extensions | **1a. Invalid Budget or Rate Input 1a1.** User enters ₱0, a negative value, or non-numeric text. **1a2.** System blocks saving, displays an input validation error, and retains the prior valid budget/rate. **3a. Invalid Operating Hours Input 3a1.** User enters hours less than 0 or greater than 24\. **3a2.** System displays a validation error message and preserves saved daily hours. **5a. Budget Exhausted by Other Planned Usage 5a1.** System detects that existing planned appliances meet or exceed the monthly budget. **5a2.** System outputs 0 allowable daily hours and explains that no estimated budget remains. **5b. Missing or Non-Positive Wattage or Rate 5b1.** Selected appliance wattage or effective tariff rate is unconfigured or zero. **5b2.** System prompts the user to supply valid inputs before calculating division. **6a. Projected Cost Reaches or Exceeds Target Budget 6a1.** Calculated projected monthly cost matches or exceeds the monthly budget threshold. **6a2.** System displays an offline in-app budget warning notification prompting usage adjustment.  |
| Postcondition | Appliance configuration, planned hours, projected monthly bill, and allowable daily appliance hours are updated and saved to local storage. |
| Stories covered | **US-01**, **US-02**, **US-03**, **US-04**, **US-05**, **US-06**, **US-07**, **US-10**  |

# 7\. Story Map

Write user journey steps across the top and story IDs underneath, highest priority first. Release 1 must span every journey step. See Week 4, slide 19\. May embed an image instead.

|  | \[Journey step 1\] | \[Journey step 2\] | \[Journey step 3\] | \[Journey step 4\] |
| :---- | :---- | :---- | :---- | :---- |
| Release 1 (MVP) | **US-01**: Set monthly budget **US-02**: Enter effective ₱/kWh rate  | **US-03**: Choose preset appliance **US-04**: Enter/edit rated wattage\[16\] **US-05**: Set planned daily hours **US-06**: Calculate affordable daily hours **US-07**: View projected monthly cost | **US-03**: Choose preset appliance **US-04**: Enter/edit rated wattage\[16\] **US-05**: Set planned daily hours **US-06**: Calculate affordable daily hours **US-07**: View projected monthly cost | **US-10**: Show offline budget warning  |
| Release 2 | **US-09**: Review & adjust weekly limit  | N/A (already in Release 1\) | **US-08**: Compare two operating-hour options **US-11**: Save & reopen plan locally  | N/A (already in Release 1\)  |
| Later | **US-12**: Suggest rate from bill image (OCR)  | N/A (already in Release 1\) | N/A (already in Release 1 and 2\) | N/A (already in Release 1\) |

# 8\. The Ordered Backlog

List every story in one order, highest priority first, with no ties. See Week 4, slides 26–28.

| Rank | Story | MoSCoW | Size (S/M/L) | Value / effort quadrant | Sprint |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | **US-01**: Set a monthly electricity budget  | Must-have  | S | High Value / Low Effort  | Sprint 1  |
| 2 | **US-02**: Enter effective electricity rate  | Must-have  | S | High Value / Low Effort  | Sprint 1  |
| 3 | **US-04**: Enter or edit rated appliance wattage  | Must-have  | S | High Value / Low Effort  | Sprint 1  |
| 4 | **US-05**: Set planned daily operating hours  | Must-have  | M | High Value / Low Effort  | Sprint 1  |
| 5 | **US-07**: View projected monthly electricity cost  | Must-have  | M | High Value / Low Effort  | Sprint 1  |
| 6 | **US-06**: Calculate affordable daily hours for one appliance  | Must-have  | M | High Value / Medium Effort  | Sprint 2 |
| 7 | **US-10**: Show an offline budget warning  | Must-have  | S | High Value / Low Effort  | Sprint 2 |
| 8 | **US-03**: Choose a preset appliance  | Should-have  | S | High Value / Low Effort  | Sprint 2 |
| 9 | **US-11**: Save and reopen an appliance plan locally  | Should-have  | S | Medium Value / Low Effort  | Sprint 2 |
| 10 | **US-08**: Compare two operating-hour options  | Could-have  | M | Medium Value / Medium Effort  | Release 2 |
| 11 | **US-09**: Review and adjust a weekly usage limit  | Could-have  | M | Medium Value / Medium Effort  | Release 2 |
| 12 | **US-12**: Suggest a rate from a bill image  | Wont-have  | L | High Effort / Uncertain Value  | Later |

## How we ordered it

Explain in 3–5 sentences why the top stories are at the top. Mention stakeholder value, risk, and dependencies.

The backlog order prioritizes stories that establish core input parameters (**US-01, US-02, US-04, US-05**) and deliver immediate financial visibility (**US-07**), addressing the key finding that **86%** of survey respondents struggle to convert monthly budgets into daily appliance usage.

Establishing these foundational inputs early mitigates technical and user-experience risks by ensuring formula accuracy before implementing reverse-budgeting logic (**US-06**) and threshold notifications (**US-10**). Strict functional dependencies are respected: cost projections and allowable operating hour calculations depend directly on saved budgets, effective rates, and appliance wattages.

Finally, complex automated features such as OCR bill scanning (**US-12**) are placed in the **Won't-have** category for the MVP due to feasibility and sizing risks.

## Capacity check

| Question | Answer |
| :---- | :---- |
| How many Must-have stories and total size? | 7 Must-have stories (**US-01, US-02, US-04, US-05, US-06, US-07, US-10**). Total size consists of **4 Small (S)** and **3 Medium (M)** stories**.** |
| Do Must-haves fit in about 60% of two sprints? | **Yes.** The 7 Must-have stories represent \~55–60% of total team capacity across Sprint 1 and Sprint 2, leaving a \~40% buffer for acceptance testing, bug fixes, and secondary Should-have implementations (**US-03**, **US-11**). |
| Do Release 1 stories form complete core workflow? | **Yes.** Release 1 forms a complete end-to-end user journey: setting budget/rate, configuring appliances, projecting monthly costs, calculating affordable daily hours, and displaying offline budget warnings. |
| Are all L-sized Must-have stories split? | **Yes.** There are no Large (L) stories among the Must-haves; the only L-sized story (**US-12**) is categorized as a Won't-have for the MVP release. |

# 9\. Definition of Done

List conditions every story must meet before it counts as done, starting Sprint 1\. See slide 22\.  
☐ Code Reviewed: The implemented feature has been reviewed by at least one other team member through a GitHub pull request.  
☐ Tests Pass: All relevant tests pass, including the normal and unhappy-path scenarios specified in the story's acceptance criteria.  
☐ Works on a Mobile Device: The feature works as expected on the target mobile device without unexpected errors.  
☐ Acceptance Criteria Satisfied: All conditions specified in the user story's acceptance criteria have been met and verified.

# 10\. Traceability Table

One row per Must-have story. Add test case IDs in Week 9\. See slide 30\.

| Story | Problem or goal it addresses | Source finding(s) | Test cases (Week 9\) |
| :---- | :---- | :---- | :---- |
| US-01: Set a monthly electricity budget | Establish a spending limit so users can plan their appliance consumption without exceeding their monthly allowance. | F1 | \[Leave blank for now\] |
| US-02: Enter effective electricity rate | Allow users to enter their actual electricity rate so that projected expenses reflect their individual billing arrangements. | C1 | \[Leave blank for now\] |
| US-04: Enter or edit rated appliance wattage | Allow users to provide the actual rated wattage of their appliances for more accurate electricity consumption estimates. | F4 | \[Leave blank for now\] |
| US-05: Set planned daily operating hours  | Allow users to specify their intended daily appliance usage to calculate estimated electricity consumption and expenses. | F6 |  |
| US-06: Calculate affordable daily hours for one appliance | Help users determine the allowable operating hours of a selected appliance based on their remaining monthly budget. | F1 |  |
| US-07: View projected monthly electricity cost | Help users anticipate their electricity expenses before receiving their actual monthly bill. | F2, F6 |  |
| US-10: Show an offline budget warning | Inform users when their projected monthly electricity expenses reach or exceed their configured budget, even without internet access. | F8, Q1 |  |

# 11\. Validation

## Team review

Record at least two problems found using INVEST, the quality checklist and common mistakes. See Week 4 slides 11 and 32\.

| Problem found | Story or requirement | How we fixed it |
| :---- | :---- | :---- |
| US-03 (Choose a preset appliance) is included in Release 1 in the story map but is classified as a Should-have in Sprint 2 in the ordered backlog. | US-03 | Align the story map with the ordered backlog or revise the priority if the team decides it is essential for Release 1\. |
| The use-case description includes saving the appliance plan locally, while US-11 is scheduled for Sprint 2\. | US-11 / UC-01 | Clarify whether local saving is necessary for the first release. If it is, reconsider its priority; otherwise, move it to a later use-case step. |

## Stakeholder walk-through

Show story map and top backlog to at least one interviewed stakeholder. See slide 31\.

| Stakeholder | Date | What they said | What we changed |
| :---- | :---- | :---- | :---- |
| Student boarders (4 respondents) | Survey response | The respondents experienced difficulty translating their monthly electricity budgets into daily appliance operating hours. Some also relied on waiting for their electricity bills instead of monitoring consumption. | Supported the prioritization of the reverse-budgeting calculator (US-06) and projected monthly electricity cost (US-07). |
| Residential households (3 respondents) | Survey responses | Respondents expressed interest in better electricity budgeting guidance, appliance usage estimates, and features that help them understand and manage household consumption. | Supported the development of appliance input options, electricity cost estimation, and budget monitoring features. |
| Residential household (Respondent H1) | October 26, 2026 | The respondent explained that refrigerators and washing machines are difficult to restrict. Reducing lights or television usage is preferable to limiting air conditioning because excessive heat can cause health problems. | Identified the need to consider essential appliances and health-related priorities when developing appliance budgeting recommendations and future trade-off simulation features. |

# 12\. Open Questions for Sprint 1

1\. How should users determine their effective electricity rate?  
2\. How should the application handle appliances with varying power consumption?  
3\. How will we verify the accuracy of the reverse-budgeting calculations?  
4\. Should the budget warning appear as soon as the projected cost reaches the threshold, or only after the user finishes entering the appliance plan?

# 13\. Member Contribution Record

Record actual interviews, analysis, stories, criteria, use case, review and validation contributions.

| Member | Interviews or analysis | Stories, criteria, or use case | Review or validation |
| :---- | :---- | :---- | :---- |
| Michael Andre L. Novela | Analyzed the interview log and summarized stakeholder needs for Sections 1–4. | Worked on the interview summary, user needs, user stories, and acceptance criteria in Sections 1–4. | Checked AI-assisted interview insights against respondents' answers and revised the wording. |
| Sam B. Tomenio | Used interview records to identify user needs and support requirements analysis. | Contributed to quality requirements using the team's interview records and related notes. | Checked the drafted requirements against the original interview sources. |
| Jericho Zhadraq S. Villadolid | Helped in interpretation of users' wants into applicable features. | Provided assistance in formulating the user stories and reviewing the interview logs. | Reviewed and revised each section, finding gaps in information. For example, identifying the lack of information from US-10 in section 4, after it had been categorized as must-have. |
| Winchester T. dela Vega | Helped analyze the interview and survey responses from 7 respondents (4 student boarders and 3 residential households), identifying their budgeting difficulties, appliance usage habits, and preferred app features. | Reviewed user stories such as US-01, US-03, US-06, US-07, US-10, and US-11, along with their relationship to the use cases and project requirements. | Checked the consistency of the story map and prioritized backlog, identified mismatches in US-03 and US-11, and used stakeholder responses to support the proposed features. |

# 14\. References

List lecture slides and external sources used. Write None if none.

[https\://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html\#1](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#1)  
 

# 15\. Team AI Use Declaration

Select one option:  
☐ No generative AI tools were used by any member in preparing this submission.  
☑ One or more members used generative AI tools. Details are provided below.  
If AI was used, complete table. Otherwise write Not applicable.

| Member who used AI | Tool | Purpose and sections assisted | How output was checked or revised |
| :---- | :---- | :---- | :---- |
| Michael Andre L. Novela | ChatGPT | I used ChatGPT to generate insights from the interview log and used it as a basis to work on part 1-4 | I checked the generated output if it corresponds to the answers of the interviewees and if it doesn’t stray away to the output that I want. |
| Sam B. Tomenio | Gemini Notebook | Parts of the Interview were put into Gemini Notebook AI as sources to get information quickly for multiple purposes in the backlog like when making Quality Requirements.  | Checking if it matches from the given source if it makes sense. Luckily Notebook offers you a direct source to where it was getting what it generates and the source was ours as it can be set to only generate what is available in given files which was ours. (I.e Interview Insights, Interview Logs, Interview Records and etc) |
| Winchester T. dela Vega | ChatGPT | Used to clarify requirements, organize stakeholder interview and survey findings, identify inconsistencies between the user stories and story map, and improve the wording of the sections. | Manually checked if the output is the same as the inputs… checked the Interview log if the respondents response is the same… also checked using the slides given |
| Jericho Zhadraq S. Villadolid | N/A | N/A | N/A |

## Main prompts or interaction summary

The team used ChatGPT and Gemini Notebook to organize and summarize interview responses, identify stakeholder needs, clarify user stories and requirements, and improve the wording and structure of the backlog. AI also helped locate relevant details across interview logs and identify inconsistencies between stories, the story map, and acceptance criteria. Team members checked the outputs against the original interview records, lecture materials, and their intended requirements, then revised the content where needed.

AI assistance supported interview synthesis, requirements clarification, drafting, and consistency checks. The team reviewed the outputs against its own source materials and remains responsible for the final backlog.

# 16\. Team Confirmation

We confirm that this document reflects our team's agreed-upon product backlog. All members listed below reviewed the final version, and each member will upload the same Markdown file to their personal CSC181 repository.

| Member | Reviewed final version |
| :---- | :---- |
| Michael Andre L. Novela | Yes |
| Sam B. Tomenio | Yes |
| Jericho Zhadraq S. Villadolid | Yes |
| Winchester T. dela Vega | Yes |

# Submission Checklist

☑ Interviews cover at least two stakeholder groups, with sources coded and no personal information.  
☑ Needs table has at least 8 findings, each labelled F, Q, or C.  
☑ Assumptions are recorded separately from evidence.  
☑ There are 10 to 15 user stories, each with a real role, a “so that”, and at least one finding.  
☑ Epics are split, and at least two rewrites are recorded.  
☑ Every story has at least 3 acceptance criteria, including an unhappy path, with no weak words.  
☑ Every Must-have story has at least 2 Given–When–Then scenarios.  
☑ At least 3 quality requirements or constraints use EARS patterns.  
☑ One use case has a diagram, main success scenario, and at least 2 extensions.  
☑ Story map has Release 1 line across every journey step.  
☑ Every story has MoSCoW label and size, and backlog is ordered with no ties.  
☑ Must-haves fit about 60% of capacity; Won't-haves retained.  
☑ Definition of Done included.  
☑ Traceability table covers every Must-have.  
☑ Team review and stakeholder walk-through recorded.  
☑ Contributions, references, and AI use declared.  
☑ All members reviewed same final document.  
☑ Each member saved activities/product-backlog.md (images in activities/backlog-images/).  
☑ Each member committed and pushed their copy.  
☑ Each member submitted their own GitHub link via MOLE before Nov 9, 2026 23:59:59.  
