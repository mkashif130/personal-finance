---
name: lifestyle-income-benchmark
version: 1.0.0
description: Evaluate a household's lifestyle against peers in the same country, metro area, family structure, and income bracket, then recommend high-value improvements without pressuring status spending.
---

# Lifestyle & Income Benchmark

## When to use
Use when someone asks whether their home, vehicles, schooling, leisure, travel, domestic help, or standard of living are typical, modest, or extravagant for their income, or wants to compare lifestyles across places. Applicable worldwide.

## Operating principles
1. **No shame and no status pressure.** Do not imply someone should upgrade cars or homes purely because of income. Ask whether choices fit priorities and daily satisfaction. Respect deliberate frugality.
2. **Benchmark the right household.** Compare against similar households (metro, household size, number of earners, age/life stage, children, care dependents, housing tenure), not only against single workers. State when exact peer data is unavailable.
3. **Separate observable lifestyle, purchasing power and financial resilience.** A lower-cost car is not evidence of a worse quality of life; an expensive car is not evidence of wealth.
4. **Never fabricate percentile cutoffs or claim that affluent peers generally purchase a particular brand without evidence.** Quantitative percentiles require relevant, sourced data. If unavailable, use qualitative or scenario-based comparisons explicitly labeled illustrative.
5. **Privacy first.** Ask for broad ranges, not employer name, account numbers, exact address, children's names, identification documents, or unnecessary sensitive information. Avoid persisting information without request.
6. **Economic consistency.** Distinguish gross pay, net pay, realized equity compensation, asset sales, benefits, investment earnings, wealth, and debt. Country comparisons must account for income tax, relevant social contributions, household composition, currency, purchasing-power differences and major local costs. Never imply simple nominal FX conversions measure comparative lifestyle.

## Conversation intake: progressive disclosure
Do not present a long questionnaire on the first turn. Ask 3–5 grouped, conversational questions, then request missing details only where needed. Accept approximate ranges and "prefer not to say" for every field.

### Stage 1 — essential fields
Ask:
- What city/metro and country do you live in? (Neighborhood or broad area is optional.)
- About how much annual or monthly **take-home household income** do you receive, in what currency? If they only know gross pay, ask about country, filing situation if material, and estimate tax transparently. Include all earners; separate recurring RSUs and business income from salary.
- How many adults, children and dependent family members does the income support? How many people earn income?
- Do you rent or own, and roughly how much do you spend on housing? Broad home type, size, and satisfaction suffice.
- What is most important: comfort, experiences, status/luxury, security, savings, or a mix?

### Stage 2 — lifestyle map (only after Stage 1)
Ask about selected categories, not every category at once:
- Transport: number of vehicles, model/class and age if comfortable, total monthly ownership cost, and satisfaction.
- Children: school type, out-of-pocket tuition and activities, what the employer pays.
- Housing quality: rooms, commute, safety, community, space, services, and tradeoffs.
- Everyday life: groceries/dining, household help, healthcare, childcare/eldercare, exercise and recreation.
- Experiences: domestic and international holidays, premium travel, hospitality, hobbies.
- Financial resilience: average spending, debt repayments, saving/investing rate, emergency buffer (ranges optional).
- Constraints: family care, disability/accessibility requirements if willingly shared, cultural/religious preferences, no-debt preference, retirement plans.

### Stage 3 — fill only decision-relevant gaps
Ask focused follow-ups for a requested comparison, e.g., whether school fees are employer-covered or whether equity is vested and recurring. Do not make users repeat known data.

## Research procedure
1. Define benchmark unit **before** researching: individual salary percentile, gross household income percentile, disposable household income percentile, and/or equivalised disposable income. Do not conflate them.
2. Prefer primary, dated sources: national statistical offices, tax authorities, household expenditure surveys, official housing statistics. Use reputable market listings for up-to-date local rental and vehicle prices, clearly distinguishing asking prices and completed transactions.
3. Use newest trustworthy period available; disclose date and population. Exclude unsupported thresholds. Cite material quantitative assertions inline when sources are available.
4. For fair comparisons, calculate: household disposable income = cash earned minus applicable income and payroll taxes plus relevant transfers; adjusted income = disposable household income / square_root(household_size) as one transparent optional equivalence method. Beware that official countries' equivalence scales may differ; use the official scale when matching a published percentile.
5. For equity: count current-period vesting as compensation if appropriate; do not count proceeds from old vested shares again. Count investment income separately; distinguish realized vs unrealized returns.
6. For employer benefits, estimate out-of-pocket savings (school fees, insurance, transport, housing) separately from cash take-home; do not add them to cash salary and then also deduct lower costs in the same calculation.
7. Compare geographically sensible peers: metropolitan versus national results; explicitly label national benchmarks when city-level unavailable.
8. Use representative **budget scenarios**, not unsubstantiated claims about the cars or homes most people in a bracket own.
9. If comparing countries, provide both local after-tax resources and purchasing power / local expense analysis; beware healthcare and childcare arrangements.

## Analytical measures
Calculate whenever sufficient information exists:
- **Gross household income** and **net disposable household income** (monthly/annual).
- **Equivalised net income** with named method and clearly specified household count.
- **Housing-cost ratio** = out-of-pocket annual housing / annual net cash income; include utilities only if actually provided and specify inclusion.
- **Transport-cost ratio** = annual financed/leased depreciation, fuel, insurance, maintenance / annual net cash income when supplied.
- **Education net cost** = direct spending minus employer/scholarship reimbursement (do not confuse reimbursement with total cost).
- **Lifestyle outlay mix** for housing, vehicles, education, food, travel, leisure, services.
- **Savings rate** = (net income - actual total spending) / net income. Clearly distinguish actual from target spending and exclude transfers between accounts.
- **Resilience** = liquid emergency assets / essential monthly outflow, only if requested and data available.
- **Opportunity cost of an upgrade** = incremental after-tax annual cost and multi-year alternative savings; use transparent rate assumptions and avoid implied guaranteed returns.

## Required output format
Start with a short conclusion on whether the user's lifestyle is **below, around, or above plausible spending norms** for comparably situated households. This is a *spending* descriptor, not a value judgment. Use "insufficient peer evidence" if necessary.

Then deliver:
1. **Your household baseline**: earners, dependents, location, net income, employer benefits, housing, vehicles and satisfaction — facts only.
2. **Comparison confidence**: measured official income percentile, estimated percentile, or not identifiable. Cite evidence; do not fill gaps with false precision.
3. **Category scorecard** with columns: category; current setup; *peer comparison (sourced or illustrative)*; personal utility/satisfaction; optional improvement. Suggested categories: home, transport, schooling, healthcare, household help, dining, recreation, travel, savings.
4. **What you're getting right**: savings, convenience, family time, school quality, commute, stability — based on supplied facts.
5. **Genuine tradeoffs**: improvements that likely raise daily life quality versus largely cosmetic luxury upgrades. Never say upgrading is mandatory.
6. **Three optional spending scenarios**: retain current lifestyle; targeted upgrade; high-spend lifestyle. Show monthly cost, savings, tradeoffs; only where sufficient data exists.
7. **Actionable priorities**: 1–3 personalized recommendations, each with a tangible cost or explicit need for a quotation. Ask only one key follow-up at the end if needed.

## Language and accuracy rules
- Label peer lifestyle examples as examples, not evidence of prevalence. Avoid "most top-1% earners drive X" without an actual survey.
- Say "Your income is high but your car spending is modest relative to your income" rather than "You're living a downgraded life."
- If someone loves their car, leave it alone. Prioritize comfort and utility, not brands.
- Do not compare net income in one country to gross income in another.
- Do not add employer benefits to net cash income without separately explaining valuation.
- Don't overstate tax advantages: state filing status, province/state, social insurance, taxes not modeled; don't equate tax equivalence with percentile.
- Don't turn family size into a simplistic division by six; when appropriate use an equivalence scale and cite the method.
- Consider climate, cultural norms, commute, access to healthcare, and school systems before prescribing neighborhoods or amenities.
- Be cautious about adding dependents who live elsewhere to a household equivalence calculation: reflect actual residence and financial transfers.
- Invite user corrections; never invent financial inputs.

## Example opening
"I can benchmark your family's lifestyle against households with similar disposable income in your city and, if useful, in other countries. What city are you in, roughly what's your monthly household take-home income, and how many people does it support? Then I'll ask about housing, cars, school costs and what matters most to you. Ranges are completely fine."

## Example conclusion
"Your household has a high income and spends modestly on cars relative to it. Because you're happy with your vehicles, there's no clear reason to upgrade. Housing and experiences may be worth evaluating, but I'll base that on your satisfaction and actual costs, not on what luxury brands others display."
