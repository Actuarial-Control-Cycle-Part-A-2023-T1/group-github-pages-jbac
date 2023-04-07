[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/elzutNYu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10744326)
# Actuarial Theory and Practice A @ UNSW

_"Tell me and I forget. Teach me and I remember. Involve me and I learn" - Benjamin Franklin_

---

### Congrats on completing the [2023 SOA Research Challenge](https://www.soa.org/research/opportunities/2023-student-research-case-study-challenge/)!

>Now it's time to build your own website to showcase your work.  
>To create a website on GitHub Pages to showcase your work is very easy.

This is written in markdown language. 
>
* Click [link](https://classroom.github.com/a/elzutNYu) to accept your group assignment.


#### Follow the [guide doc](Doc1.pdf) to submit your work. 
---
>Be creative! Feel free to link to embed your [data](hazard-event-data.csv), [code](sample-data-clean.ipynb), [image](unsw.png) here

More information on GitHub Pages can be found [here](https://pages.github.com/)
![](Actuarial.gif)

---

# Executive Summary
This social insurance program to manage Storslysia’s exposure to displacement risk associated with the country’s unique susceptibility to catastrophic climate-related events. This program is designed to have a high probability of reducing the economic cost to Storslysia by incentivising proactive, voluntary relocation, whilst also aiding the welfare of citizens displaced by inevitable climate catastrophe - under a wide range of climate-change scenarios.  

Australian interstate migration data is leveraged to estimate future costs of the program arising from voluntary relocation, whereas Storslysia’s historical data regarding property damage, injury, and death arising from climate disasters enhances estimates of involuntary-displacement costs. 

It was found with >90% certainty that economic costs would be cheaper with the program than without. It has been recommended that an initial Ꝕ 28.9 billion is set to ensure a 99% chance of remaining solvent year-to-year. Furthermore, the probability that year-to-year program costs exceed 10% of Storslysia’s current GDP is ~0.10%. All such figures are calculated under a worst-case climate scenario.

## Objectives
### Effective and Equitable Relocation Insurance
This program should reduce Storslysia’s expected costs arising from climate-related displacement. This will be achieved by covering costs associated with relocation – adjusted to account for geographic risk and socio-economic status. It should be noted that the intention of the program is to not act as a house and contents or life insurance program - we encourage the public to seek private insurance for this purpose. 
The National Flood Insurance Program (NFIP) in the United States, which is in USD 20 billion of debt, has struggled to remain solvent primarily due to its inability to accurately predict the increase of flood frequency and severity due to climate change (Ma, 2022). Thus, to bolster the long-run viability of our program, we have resolved this uncertainty by factoring the effect of climate change into our claim modelling.

### Incentivising Voluntary Relocation
Proactive, voluntary relocation is much cheaper for Storslysia to fund in comparison to ad hoc involuntary relocation arising from a natural peril. This is due to the additional costs of replacing items and fixing damages incurred from disaster (Adeagbo et al., 2016), as well as 0-50% increases in housing and relocation costs after weather event induced demand increases. Thus, successfully incentivizing year-round proactive relocation from higher to lower-risk regions is a critical aspect of our program - not only to reduce economic costs but also to shield the population from displacement risk exposure.  

## Monitoring Program Success
The program’s claim cost model (see Appendix) automatically reports predicted economic costs to Storslysia with and without the program. This will help to distinguish if savings will be produced. Additionally, the program cost will be evaluated with respect to Storslysia’s gross domestic product (GDP). The claim cost model distributes the predicted yearly model costs. 

---

# Program Design
![image](https://user-images.githubusercontent.com/113432792/230565499-7e6e4910-d5eb-498c-8892-651024c564ae.png)
## Involuntary Relocation 
### Percentage of Lump Sum Payment 
The lump sum payment,calculated yearly, will be given on a per person basis and will cover costs for transportation, health care, accommodation, and retail sales for a year to help relocate. The lump sum payment has been intentionally set to ensure only necessities can be provided. It was found in the Earthquake Commission in New Zealand that a cap-based sum insured policy attracted a large private insurance market to cover excess claims (Earthquake Commission 2019). Hence, if citizens desire further cover, they will be recommended to search for private insurers. This will reduce the heavy financial pressure that will impact the government if extreme amounts are paid out.

As seen in table above(Figure 1),all claimants must relocate to a safer region and the percentage of the total lump sum claimants are eligible for, will be according to the region they move to and its associated risk for natural disasters. This is in place to encourage those relocating,to move to the lowest risk region and thus lower the chance of the individual having to relocate again.
### 15% of New Property Purchase Subsidised 
On top of the lump sum payment to cover costs, 15% of the new property purchased will be subsidized according to the location of relocation.This was introduced to assist families during the difficult financial and mental distress that is associated with relocating. The subsidy will be the same percentage irrespective of the region that claimants are relocating to.Only one property subsidy can be claimed per household.
## Voluntary Relocation Incentives 
### 100% Of Lump Sum Payment Per Household 
Individuals who do relocate irrespective of which region they move to, will receive 100% of the lump sum payment per household to cover for their relocation costs. This is in comparison to claimants receiving a proportion of the fullcalculatedlump sum payment depending on region of relocation. Although, it is feasible for the payout to be larger for involuntary claim as the lump sum provided is on a per person rather than household basis, this is only likely to occur if individuals relocate from region 5to 1. The possible deterrent is also negated due to the higher cost of living in region 1 with median housing costs 20% lower in region 5implicatingvoluntary relocation is unlikely to occur to this region.
### 25% of New Property Purchase Subsidised 
Finally, a major incentive introduced, is subsidising 25% of the property value that is purchased for relocation as opposed to 15%. This will be regardless of which region a claimant relocates to.Just like involuntary claims, only one property subsidy can be claimed per household.
## Trigger Points 
For Involuntary relocation a claim may be made by a claimant for relocation if either their property damage exceeds at least 25% of their property value or serious injury/death has been inflicted due to a climate related event. It was assumed that these trigger events were a reasonable reason for relocation after a disaster. Whilst for voluntary relocation a claimant must provide evidence that they are relocating their primary residence to a safer region such as a down payment on a new house. A loss adjuster and home inspector will be sent to ensure a fair claim has been made for both scenarios.Due to the nature of voluntary payouts, only two voluntary claims can be made every ten years.
## Short and Long Term Program Evaluation 
Throughout both the short and long term, the programs expenses will be monitored yearly to evaluate its ability to reduce Storslysia’s economic costs and be below 10% of the nation’s GDP. In the short term, the voluntary relocation rate will be monitored (as this is likely when the majority of relocation will occur) to not only ensure that program is effective but ensure that economic costs will be accurately predicted. In the long term, the programs’ ability to economically sustain the increase in natural disasters due to climate change will be evaluated.

---

# Pricing/Costs

Considering the current world is still heavily dependent on fossil fuels, when factoring the costs associated with the program these will fall under an SSP5 Scenario. The following results were obtained after 100,000 simulations by using Palisade’s @Risk tool.

## Costs of the Program

As observed, the costs of the program are increasing exponentially over time. In the short term, the average costs are around Ꝕ 5-6 billion, eventually reaching an excess of Ꝕ 10 billion in the long term. In a 1% worst case scenario, these costs can reach upwards of 2.5 times the mean.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/113604900/230582848-573d8a23-dc8b-4978-803b-f54ec4e1fb2f.png">

## Costs Without the Program

Without the program it is projected that on average, Storslysia exhibits additional costs (Figure 3). These additional costs are exponential over time similar to the costs of the actual program, although are increasing at a higher rate. Whilst the costs of the program roughly double over the period of the scheme, the additional costs increase by a factor of 10 over the same time horizon.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/113604900/230583143-e63185c2-1f9f-46c3-be4f-e1061876fb38.png">

## Solvency

Figure 4 demonstrates the maximum cost exhibited for any year for each simulation. In a 99% worst case scenario, the program cost Ꝕ 28.9 billion. So long as this amount is kept reserved for the program each year, there is a strong certainty that the program will remain solvent. This reserve is needed to alleviate liquidity risk associated with the timing mismatch between tax revenues and program costs (Kessler, 2014).

<img width="500" alt="image" src="https://user-images.githubusercontent.com/113604900/230583257-b343417c-00e8-4489-ba43-95a9bc264979.png">

## Contrast of Voluntary and Involuntary Costs
As observed in Figures 5 and 6, the projected voluntary costs associated with the program are consistently higher than involuntary costs. On average, these voluntary costs are 4 times higher than those involuntary, and this appears consistent across the projected timeline.

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/113604900/230583454-6f3a219e-8c97-456e-803f-19868eeafce7.png">

---

# Assumptions 
## Key Assumptions 
![image](https://user-images.githubusercontent.com/113432792/230566497-dbb39785-6b3c-42a5-9c5a-dcdb9d8a6628.png)

---

# Data and Data Limitations 
## Data Limitations 
Lack of granular information on Storslysia on a yearly basis (such as population size and exchange rate), severely hampered the ability to utilise any linear or generalised linear model to predict Natural Hazard Events. Instead, fitting a distribution using maximum likelihood estimation, which would not be as accurate, had to be used. Next, as regional data was only provided for 2020, it was impossible to determine the economic trends that would occur including population growth and socioeconomic status. As a result, strongassumptions had to be made regarding these variablesas discussed in section 4. Additionally, anerroneous valuewas listed for the 2003 Ꝕinflation rate whereas no data was provided for the 1960 and 1961 Ꝕinflation rates –these data points were restored using the geometric mean of the remaining year’s rates. Extreme outliers existed in the provided hazard property damage data –these were evaluated to be legitimate losses arising from particularly catastrophic perils and retained.

---

## External Data
Australian interstate migration data was used to predict relocation rates to desirable regions and general population migration. Australian data was utilised on account of the similar population size, number of states and population distribution within states.It is recommended that Storslysia collects internal inter-region migrationdata effective immediately. The provided claim count model will allow for the convenient incorporationof new data from Storslysia’s realised migration experience–nothing else needs to be changed. 

---
---
---

# Appendix

## General Assumptions

<img width="827" alt="image" src="https://user-images.githubusercontent.com/113604900/230585397-66a9e608-8610-4088-a112-8744ae90ea60.png">

## Assumptions Affecting Modelling of Claim Rate

<img width="827" alt="image" src="https://user-images.githubusercontent.com/113604900/230585558-8daaae13-5197-45ec-a4a9-d0d5838cb4ce.png">

## Assumptions Affecting Claim Cost and Property Severity

<img width="826" alt="image" src="https://user-images.githubusercontent.com/113604900/230585680-573ce135-c543-4779-bb00-45b52d2bb243.png">

## Visualisations for Sensitivity Analysis

<img width="858" alt="image" src="https://user-images.githubusercontent.com/113604900/230585830-4048dd7c-02a5-4315-96d0-51e8262ca60d.png">

<img width="842" alt="image" src="https://user-images.githubusercontent.com/113604900/230585881-bb7a588d-2ecf-4bfc-b0b1-9b8d93644c24.png">

## Modelling and Input Processes

### World Growth Factors

World growth rates for each year were regressed according to the data provided. This included population, worldwide GDP, and the Risk Amplification Factor (RAF). The data provided had limited data, having estimates every 10 years for each SSP scenario. In R, quadratic regression was used to estimate values for each year, and so then growth factors could then be obtained. A GDP per capita factor was obtained by dividing the GDP growth factor by the population growth factor.

### Per Capita Cost Inputs

Cost inputs for the lump sum payment of our model included accommodation, food service, health care, social assistance, transportation, warehousing and retail sales. Since the data provided 2017 costs, these prices were inflated to 2020 values and divided by the 2020 population to obtain the cost per capita. The GDP per capita growth factor was then used to project these costs over time.

### Voluntary Lump Sum Payment

For voluntary claims, a lump sum payment is provided to each household that makes a claim. The value of this payment is equal to the total per capita costs inputs for that year, multiplied by a factor of 1.5.

### Involuntary Lump Sum Payment

For involuntary claims, a lump sum payment is provided to each claim that is made. The value of this payment is equal to the total per capita costs input for that year. There is no adjustment multiplication factor, unlike the lump sum payment from voluntary claims.

### Number of Hazard Events

The number of hazard encountered for each region per year was extracted from the dataset. A gamma, exponential, and lognormal distribution was used to fit the number of hazard events in a year per region. Of the three distributions, a Kolmogorov–Smirnov test showed the best fit for each region. 10,000 random sample distributions were used, and KS tests were conducted on each. Whichever gave the largest average p-value was the distribution chosen. In excel and using Palisade’s @Risk tool, these distributions were then used to simulate the number of hazard events in the year, across the duration of the program. The parameters of the distribution changed over time by multiplying the relevant RAF, attempting to model an increasing frequency of events as time progresses.

### Property Value

From the data provided, a distribution of each region’s property value could be modelled. A continuous probability density function was applied to model the associated price of each house for each region.

### Number of Fatalities, Injuries and Property Damage

The data provided the fatalities, injuries, and property damage values per event over time. For property damage, inflation factors derived from the data were used in order to find its 2021 cost. 

For all three considerations, no conventional models fit the data well enough, so exponential fits were chosen. By then separately estimating the exponential rate parameter for each region’s fatalities, injuries and property damage, the results were transferred to Excel where the @Risk tool was used to simulate the expected severity after each event. 

### Involuntary Claims

When determining the expected number of claims arising from a hazard event per region a few inputs are used. The predicted property damage was divided by the simulated property value, to get the number of full houses destroyed by the event. This was multiplied by a factor of 4 assuming that damage exceeding 25% of the property value would result in a claim. Another set of claims were derived from the fatalities per event, which was then multiplied the average people per household minus 1. This assumed that whenever a death from a household occurred, the other members would make a claim to relocate. Finally, the number of injuries per event was multiplied by the number of people in each household. Assuming that when a serious injury occurred, all people in the household file a claim. All these numbers are on a per event basis, and so were finally multiplied by the simulated number of events in that region for the year.

### Voluntary Claims

To determine the number of voluntary claims per year, the yearly population was multiplied by the proportion of individuals moving to a more at-risk region. These proportions were calculated based off Australian relocation data.

---

# References

Ma, M 2022, Can the National Flood Insurance Program survive its growing debts?, Policygenius. 

Harvey, C 2018, CO2 Can Directly Impact Extreme Weather, Research Suggests, Scientific American. 

Congressional Research Service 2023, Introduction to the National Flood Insurance Program (NFIP) Introduction to the National Flood Insurance Program (NFIP), 6 January. 

Kessler, D., 2014. Why (re) insurance is not systemic. Journal of Risk and Insurance, 81(3), pp.477-488. 

Earthquake Commission 2019, Briefing to the Incoming Minister Responsible for the Earthquake Commission. 

Adeagbo, A., Daramola, A., Carim-Sanni, A., Akujobi, C. and Ukpong, C., 2016. Effects of natural disasters on social and economic well being: A study in Nigeria. International journal of disaster risk reduction, 17, pp.1-12. 

Smolka, A. and Hollnack, D., 2008. Risk Management for Natural Perils–The View of a Global Reinsurer. Geomechanik und Tunnelbau: Geomechanik und Tunnelbau, 1(2), pp.103-111.  

Derrig, R.A., 2002. Insurance fraud. Journal of Risk and Insurance, 69(3), pp.271-287. 

Islam, M.R. and Khan, N.A., 2018. Threats, vulnerability, resilience and displacement among the climate change and natural disaster-affected people in South-East Asia: an overview. Journal of the Asia Pacific Economy, 23(2), pp.297-323.
