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
