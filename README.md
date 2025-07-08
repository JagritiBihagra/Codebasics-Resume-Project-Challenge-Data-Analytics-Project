# Codebasics-Resume-Project-Challenge-Data-Analytics-Project

This Project is a Codebasics Resume Project Challenge run by Codebasics. Hundreds of participants across the world participate in this and their work is then recognised by the Codebasics team and their connections on LinkedIn worldwide.

# About The Project
The project is about an imaginary beverage company called CodeX.

# CodeX Marketing Insights Dashboard
The project is about an imaginary beverage company called **CodeX**. CodeX is a German beverage company which has recently launched in India. They introduced their energy drink in **10 cities** across India.

CodeX conducted a survey in those cities and received results from **10,000 respondents**.  
The survey included consumer behavior questions like purchasing habits, feedback about energy drinks, pricing, packaging, etc.

The **Marketing Team** wants their **Data Analyst** to convert this data into meaningful insights and provide actionable recommendations.
CodeX is a German beverage company which is recently launched in India. They launched their energy drink in 10 cities in India.


##  Problem Statements & Solutions

###  Demographic Insights

- **Who prefers energy drinks more?**
  - 6,038 out of 10,000 respondents are male → **60% male preference**
- **Which age group prefers energy drinks more?**
  - Over **50% are aged 19–30**, and **70% between 15–30**
- **Which type of marketing reaches most youth (15–30)?**
  - **Online Ads** reached 3,373 respondents in this group

---

###  Consumer Preference

- **Preferred ingredients**:  
  - **Caffeine** is most expected, followed by **Vitamins**
- **Packaging preferences**:  
  - **Compact cans** and **innovative bottles** are most desired

---

###  Competition Analysis

- **Market leaders**:  
  - **Cola Coka** followed by **Bepsi**
- **Why do consumers prefer those brands?**  
  - Top reason: **Brand reputation**

---

###  Marketing Channels and Brand Awareness

- **Which marketing channel is most effective?**  
  - **Online Ads** (most reach, cost-effective)

---

###  Brand Penetration

- **What do people think about CodeX?**
  - Out of 980 who heard about CodeX, 455 rated the taste
  - Taste rating: **3.3**, same as industry average
- **Which cities need focus?**
  - Many show **neutral/negative** responses → marketing should aim to **increase positive response**

---

###  Purchase Behavior

- **Preferred purchase locations**:  
  - **Supermarkets** are most common
- **Consumption situations**:  
  - **Sports/exercise** and **Studying/working late**
- **Factors influencing purchase**:  
  - **43%** prefer price range **50–99**
  - **40%** of the consumers do not expect a change in the packaging
  - **39%** open to limited edition packaging

---

###  Product Development

- **Where to focus?**
  - **Availability** is a key issue (only 219 out of 980 had a positive view)
  - The taste experience rating is the same as the industry rating. This is not something that needs immediate attention. Taste is on par with competition
  - About **20%** of the consumers choose the product because it is available.
  - **Availability drives sales**, so it should be prioritized

---

###  Recommendations For CodeX
## What immediate improvements can we bring to the product?
- Availability: Expand product distribution to more cities and retail outlets.
- Health Concerns: Conduct another survey specifically addressing health-related expectations (targeting the 455 respondents who have heard about CodeX).
- Limited Edition Packaging: Introduce seasonal, event-themed, or festival-based packaging.
  
-**Product Composition:**
  -Add more natural ingredients
  -Reduce sugar content
  -Introduce more flavour options
  -Improve Positive Brand Perception: Focus on campaigns and community feedback to increase positive responses.

## What should be the ideal price of our product?
- Range: **₹50–₹150**
- In some cities (e.g., Ahmedabad, Chennai), people prefer **₹50–₹99**
- Others are okay up to ₹150
- Based on the data, consumers expect the price to fall between ₹50 to ₹150.
  
## What kind of offers and discounts can we run?
- City-wise pricing experiments
- **Combo packs** (e.g., 6-can offers)
- **Festival gift sets**: Launch seasonal or festival-based gift packs during events celebrated in each city.
  
## What kind of marketing campaigns can we run?
-**Social Media:** Most of our target audience (15–30 years) is highly active on platforms like Instagram, YouTube, and X (Twitter).
Online ads and social media campaigns are effective in reaching them.

-**Influencer Marketing:** Budget-Friendly: Collaborate with local influencers on barter deals or small payments.
Macro & Micro Influencers: Partner with creators who have 10k to 500k+ followers.
Giveaways & Coupons: Let influencers distribute products or share exclusive discounts to drive awareness and engagement.

-**Online Retailers & E-Commerce**
Use PPC ads on online grocery and e-commerce platforms.
Target consumers who are still unfamiliar with CodeX to drive trial.

-**Guerrilla Marketing**
Supermarkets: Set up branded stalls or displays at popular retail chains.
Event Participation: Join local food festivals like The Grub Fest and Horn OK Please to offer samples and collect feedback.

## Who can be a brand ambassador, and why?
To choose the right ambassador, consider:
- Budget: High-reach celebrities cost more.
- Relevancy: Energy drinks align well with athletes and fitness influencers.
- Impact: Influencers should actively influence purchasing decisions.

- Recommended Ambassadors:

**Virat Kohli**

A youth icon known for fitness and discipline.
Highly followed and experienced in endorsements.
Premium choice; may require a large budget.

**Neeraj Chopra**

Olympic gold medalist and rising sports star.
Gaining media coverage and popularity.
Ideal for a fresh, athletic brand image.

**MS Dhoni**

Retired cricketer but still extremely influential.
Viral impact
Perfect for campaigns around nostalgia and trust.

## Who should be our target audience, and why?
Youth aged 15–30:
Survey data shows 70% of our consumers fall in this age range.
This group is highly engaged with fitness, gaming, studying, and working late — all activities associated with energy drink consumption.
They are also highly responsive to digital and influencer marketing.


##  Dataset Provided by Codebasics

Includes 3 CSV files:
The dataset provided by the Codebasics
This file contains all the meta information regarding the columns described in the CSV files. We have provided 3 CSV files:

1. dim_respondents
2. dim_cities
3. fact_survey_responses

# 1. dim_respondents

1. Respondent_ID: Unique identifier for each respondent in the survey
2. Name: Name of the respondent
3. Age_Group: Categorized age group (e.g., 15–18, 19–30, etc.)
4. Gender: Gender of the respondent (Male, Female, Non-binary)
5. City_ID: ID linking the respondent to their city in dim_cities

# 2. dim_cities
1. City_ID: Unique identifier for the city
2. City: Name of the city (e.g., Delhi, Mumbai, Bangalore, etc.)
3. Tier: Tier classification of the city (e.g., Tier 1, Tier 2)

# 3. fact_survey_responses
1. Response\_ID: Unique identifier for each survey response
2. Respondent\_ID: Links to dim\_respondents to identify the respondent
3. Consume\_frequency: How often the respondent consumes energy drinks
4. Consume\_time: When the respondent typically consumes energy drinks
5. Consume\_reason: Reason for consuming energy drinks
6. Heard\_before: Whether the respondent had heard of CodeX before
7. Brand\_perception: Respondent’s perception of CodeX
8. General\_perception: General perception of energy drinks
9. Tried\_before: Whether respondent has tried CodeX before
10. Taste\_experience: Rating of the taste experience with CodeX
11. Reasons\_preventing\_trying: Reasons for not trying CodeX
12. Current\_brands: Brands the respondent currently consumes
13. Reasons\_for\_choosing\_brands: Why the respondent chooses those brands
14. Improvements\_desired: What improvements the respondent expects
15. Ingredients\_expected: Ingredients respondents want in energy drinks
16. Health\_concerns: Any health concerns about energy drinks
17. Interest\_in\_natural\_or\_organic: Interest in organic or natural drinks
18. Marketing\_channels: Channels where they saw marketing (e.g., online, offline)
19. Packaging\_preference: Preferred packaging style (e.g., cans, bottles)
20. Limited\_edition\_packaging: Preference for limited edition packaging
21. Price\_range: Ideal price range for the product
22. Purchase\_location: Where they usually buy energy drinks (e.g., supermarket)
23. Typical\_consumption\_situations: When they typically consume energy drinks (e.g., studying, workouts)


The PDF contains all the questions with the multiple-choice answers asked to the consumers.

---

##  Credits

Thanks to **Codebasics** for the Resume Challenge #6 — a brilliant real-world data analytics simulation.

🔗 [Challenge Link](https://www.codebasics.io/challenge)

