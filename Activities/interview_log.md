# **Interview Log**

Source: Survey on student boarder energy budgeting & household appliance usage in Iligan City. Respondents are identified by Respondent ID and Submission ID. Names, emails, and social links are removed for privacy purposes.

Submissions: 7 total respondents (4 student boarders \+ 3 residential households). All 7 respondents completed the core questionnaire covering living/property profile, billing calculation, usage tracking habits, bill shock frequency, budget-to-hours conversion difficulty, appliance profiles, restriction criteria, and app preferences.

# **Respondent Profile**

| Group | Breakdown |
| :---- | :---- |
| Property / Living arrangement | Boarding house / Dormitory 2, Shared apartment 1, Single-room 1, Multi-family shared property 1, Single-family house 1, Rented house / Dedicated apartment 1 |
| Billing & meter setup | Individual sub-meter per room 2, Variable rate by landlord 2, Multi-family shared property 1, Single-family owner-occupied 1, Rented house with independent ILPI meter 1 |
| Average monthly electric bill / budget | ₱601 – ₱1,000 (2), ₱1,500 – ₱3,000 (1), ₱3,001 – ₱5,000 (1), ₱5,001 – ₱8,000 (1), Above ₱1,000 (1), Unanswered (1) |
| Electric usage tracking method | Do not track usage / wait for bill (4), Mental estimates based on past bills (1), Inspect physical meter outside (1), Manually check sub-meter dials (1) |
| Bill shock frequency | Almost every month (2), Frequently / hot months (1), Occasionally / tariff jumps (1), Rarely or never (3) |
| Budget-to-hours conversion difficulty | Extremely difficult (3), Somewhat difficult (3), Neutral (1) |
| Preferred appliance setup method | Hybrid presets with editable wattage (4), Exact wattage from backplate/sticker (2), Standard appliance presets (1) |
| App usage mode & frequency | Weekly limit setting & family review (5), Daily dynamic monitoring (2) |

# **Key Interview Insights**

## **Key findings**

| Finding | Evidence | Why it matters for the app |
| :---- | :---- | :---- |
| High conversion difficulty across all segments | 86% (6/7) find converting a monthly budget into daily operating hours difficult (3 Extremely difficult, 3 Somewhat difficult, 1 Neutral). | Core value proposition validated for both student boarders and larger residential households. |
| Unmonitored passive consumption | 57% (4/7) do not track usage at all until the bill arrives; others rely on rough mental estimates or physical meter checks. | Proactive daily usage guidelines and tracking features are essential to replace passive waiting. |
| Health and cooling prioritization during bill surges | Families hesitate to restrict refrigerators or ACs due to heat-related health risks (e.g., heat fever), preferring light/TV cutbacks instead. | The app should feature appliance trade-off simulation so families can optimize non-essential consumption while protecting health-critical cooling. |
| Strong preference for hybrid appliance profile setup | 57% (4/7) prefer hybrid presets with editable wattage values, balancing setup speed with accuracy. | Pre-filled templates with editable wattage fields offer the ideal default setup flow. |
| High demand for bill calculation & estimation features | Features requested include real-time bill calculators, daily usage tracking, and OCR bill scanning for kWh rate capture. | Offline estimation tools and simple rate calculation inputs should be central to the MVP. |

## **Features requested (n=7)**

| Feature | Votes | Share |
| :---- | :---- | :---- |
| Weekly usage limit setting for self/housemates/family | 5 | 71% |
| Hybrid preset templates with editable wattage | 4 | 57% |
| Daily dynamic monitoring & running hour tracking | 2 | 29% |
| Daily usage tracking with monthly bill estimation | 2 | 29% |
| Real-time bill calculator | 2 | 29% |
| Exact wattage entry from backplate sticker | 2 | 29% |
| Bill scanner (determine cost per kWh) | 1 | 14% |
| Standard appliance presets | 1 | 14% |
| Offline threshold alerts & trade-off simulator | 1 | 14% |

## **Suggested MVP priorities**

| Priority | Build | Basis |
| :---- | :---- | :---- |
| 1 | Reverse-budgeting engine (Peso limit to daily appliance operating hours) | 86% of respondents find manual conversion difficult. |
| 2 | Hybrid appliance profile builder (Preset library \+ editable wattage) | Chosen by 57% of respondents as the preferred setup method. |
| 3 | Real-time bill estimator & daily usage tracker | Explicitly requested by both student boarders and multi-family households to avoid bill shocks. |
| 4 | Appliance trade-off simulator & usage recommendations | Directly requested by household respondents who struggle to choose which appliances to scale back without compromising health/comfort. |
| 5 | Shared/family room usage planner | 71% intend to use the app weekly to set and review usage limits with family members or housemates. |

# **1\. Respondent Table**

| \# | Respondent ID | Submission ID | Property / Living Arrangement | Billing & Meter Setup | Monthly Bill / Budget | Usage Tracking Method | Bill Shock Frequency | Conversion Difficulty | App Usage Mode | Preferred Input Method |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | 8bcfe38 | a5f4eba | Boarding house / Dormitory | Sub-meter readings per room | Above ₱1,000 | Manually check sub-meter dials | Almost every month | Extremely difficult | Daily dynamic monitoring | Hybrid presets with editable wattage |
| 2 | 2bbc4e6 | 1459666 | Shared apartment / House rental | Variable rate set by landlord | ₱601 – ₱1,000 | Do not track, wait for bill | Rarely or never | Somewhat difficult | Weekly limit setting | Hybrid presets with editable wattage |
| 3 | ed3eeaa | db57c0b | Boarding house / Dormitory | Variable rate set by landlord | Unanswered | Do not track, wait for bill | Rarely or never | Somewhat difficult | Weekly limit setting | Exact wattage from backplate/sticker |
| 4 | 60e8dc1 | 514033a | Single-room / Studio apartment | Sub-meter readings per room | ₱601 – ₱1,000 | Do not track, wait for bill | Almost every month | Extremely difficult | Weekly limit setting | Exact wattage from backplate/sticker |
| 5 | c4a812f | f9011b2 | Multi-family / Shared property | Shared residential property | ₱5,001 – ₱8,000 | Rough mental estimates | Occasionally (3–4 mos) | Neutral | Daily to set & monitor running hours | Hybrid setup of standard presets |
| 6 | b892d11 | e341c09 | Single-family house | Owner-occupied independent ILPI meter | ₱3,001 – ₱5,000 | Manually inspect meter outside | Frequently (Hot months) | Extremely difficult | Weekly to review with family | Selecting standard appliance presets |
| 7 | d2190f4 | a11874c | Rented house / Apartment | Independent ILPI meter | ₱1,500 – ₱3,000 | Do not track, wait for bill | Rarely or never | Somewhat difficult | Weekly to review targets | Hybrid setup of standard presets |

# **2\. Appliance Usage and Tracking Behavior**

| Respondent ID | High-Wattage Appliances Operated | Usage Tracking Approach | Bill Shock Frequency | Restriction & Trade-off Decision Criteria |
| :---- | :---- | :---- | :---- | :---- |
| 8bcfe38 | Inverter Aircon, Electric Fans, Electric Kettle, Rice Cooker | Manually check sub-meter dials | Almost every month | Restrict electric fan usage |
| 2bbc4e6 | Electric Fans, Desktop PC / Gaming Laptop | Do not track, wait for bill | Rarely or never | Unanswered |
| ed3eeaa | Electric Kettle, Rice Cooker / Hot Plate | Do not track, wait for bill | Rarely or never | Unanswered |
| 60e8dc1 | Electric Fans, Desktop PC, Electric Kettle, Rice Cooker, Hair Dryer / Iron | Do not track, wait for bill | Almost every month | Based on what is not needed in everyday use |
| c4a812f | Inverter Aircon, Refrigerator/Freezer (24/7), Washing Machine/Dryer, Desktop PC/Entertainment, Multiple Stand Fans | Rough mental estimates based on past billing cycles | Occasionally (Every 3–4 months) | Hard to restrict fridge or washing machine; prefer reducing lights/TV rather than AC due to health risks (fever from heat) |
| b892d11 | Non-inverter Aircon, Refrigerator/Freezer, Electric Cooking Appliances, Multiple Stand Fans | Manually inspect electric meter outside | Frequently (Hot months) | Turn off aircon during daytime, rely on stand fans, and avoid induction cooker during peak hours |
| d2190f4 | Refrigerator/Freezer, Electric Cooking Appliances, Multiple Stand Fans, Desktop PC | Do not track, wait for bill | Rarely or never | Limit desktop PC gaming hours and unplug idle appliances |

# **3\. App Preferences, Input Methods, and Feature Requests**

| Respondent ID | App Usage Frequency & Model | Preferred Profile Setup Input Method | Desired Specific Feature |
| :---- | :---- | :---- | :---- |
| 8bcfe38 | Daily dynamic monitoring | Hybrid presets with editable wattage | Feature that tracks daily electricity usage and estimates monthly bill to manage budget |
| 2bbc4e6 | Weekly limit setting | Hybrid presets with editable wattage | Real-time bill calculator |
| ed3eeaa | Weekly limit setting | Exact wattage from backplate/sticker | Unanswered |
| 60e8dc1 | Weekly limit setting | Exact wattage from backplate/sticker | Scanner for electricity bill to determine cost per kWh |
| c4a812f | Daily to set and monitor running hours | Hybrid setup of standard presets with editable wattage | Guidance on how to budget from appliances better based on standard usage knowledge |
| b892d11 | Weekly to review with family members | Selecting standard appliance presets | Offline threshold alerts when projected monthly consumption approaches budget limits |
| d2190f4 | Weekly to review overall targets | Hybrid setup of standard presets with editable wattage | Appliance trade-off simulator comparing appliance running costs |

# **4\. Open-Ended Responses**

| Respondent ID | Suggested Improvements & Specific Feature Requests | Additional Comments |
| :---- | :---- | :---- |
| 8bcfe38 | Daily usage tracking and monthly bill estimation to prevent overspending in boarding house setups. | Wants a feature that tracks daily electricity usage and projects monthly costs dynamically. |
| 2bbc4e6 | Real-time bill calculator. | Highlighted the need for instant bill estimation while using appliances. |
| ed3eeaa | N/A | No write-in comment provided. |
| 60e8dc1 | Scanner for electricity bills to determine the effective cost per kWh. | Suggested OCR or image scanning of utility bills/landlord notices to automatically capture rate per kWh. |
| c4a812f | Appliance energy budgeting guidance based on standard consumption parameters. | Commented that physical sub-meters are not present near his household. Noted that sudden tariff increases cause bill surges, and health risks from extreme heat make aircon cutbacks undesirable. |
| b892d11 | Proactive budget threshold notifications and offline meter log tracking. | Wants simple preset options for household members who don't know exact appliance wattages. |
| d2190f4 | Appliance trade-off comparison tool to see cost differences between running fans vs. air conditioners or PCs. | Suggested clear visual guides for energy-saving habits. |
