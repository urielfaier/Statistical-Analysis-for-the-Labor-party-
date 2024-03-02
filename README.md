# Labor Party Election Analysis 

## Files
- **README.md**: You're reading it! An overview of the repository.
- **notebook**: Jupyter Notebooks containing code and visualizations with short explanations.

## Background

As we dive into the world of Israeli politics, it's important to understand how political parties change over time. So, let's take a closer look at what's been happening with the Labor Party in the last few elections. We'll explore who they've been teaming up with, who they've been breaking away from, and what all these shifts mean for where they stand now and what might happen next.

**Year 2020:**
- In January 2020, a strategic coalition was formed between Labor, Gesher, and Meretz, led by Amir Peretz, Orly Levi-Abekasis, and Nitzan Horowitz, respectively. This coalition, named Labor-Gesher-Meretz, aimed to enhance electoral prospects by consolidating resources and mitigating the risk of failing to meet the electoral threshold individually.
- However, internal discussions regarding Labor's potential participation in the government led to a split from the joint faction with Meretz. Subsequently, Labor and Gesher entered into a coalition with Netanyahu and Gantz.
  
**Year 2021:**
- In April 2021 The 23th Knesset was replaced by the 24th Knesset, the Labor Party witnessed leadership transitions as well, with Amir Peretz stepping back from the party leadership contest. Merav Michaeli emerged victorious in the subsequent party primaries, winning a significant majority.
- The party campaigned on a platform emphasizing principles of equal citizenship, combating gender violence, environmental sustainability, religious pluralism, rural development, and advancing the vision of a two-state solution for peace and security.
- the Labor Party secured 7 mandates in the new 24th Knesset, with 5.29% of the vote share.

**Year 2022:**
- Discussions arose regarding a possible merger between the Labor and Meretz parties following the Knesset's decision to advance elections for the 25th Knesset on June 30, 2022. Despite Prime Minister Yair Lapid's attempts to facilitate this merger, Merav Michaeli, the Labor Party leader, resisted, leading Labor to run independently in the elections.
However, the party faced a notable decrease in electoral backing, obtaining only 4 seats in the ensuing Knesset, with a vote share of 3.69%.

## Analysis in notebook 

### Part 1: Affected of overall voter turnout on the Labor party 

This analysis examines the voting percentages for the Labor Party, comparing sample data with predictions based on a 100% voter turnout. It entails bar plots that contrast projected and actual voting percentages. The aim is to assess how variations in the overall turnout rate influence political parties, particularly the Labor Party.

### Part 2: PCA Analysis
Principal Component Analysis (PCA) is performed to analyze voting patterns across polling stations using Socio-Economic data. 

### Part 3: Voter Transition Analysis
Changes in voting behavior between the years 2021 and 2022 are analyzed between all parties. 


### Data Files used

1. **Polling Stations File 2021-2022:**
   - This file encompasses comprehensive voting data from all polling stations across Israel for both election dates. It includes vital parameters such as the number of eligible voters, valid and invalid votes, settlement names, and party-wise vote counts.
   - Preprocessing of this data involved tasks like removing information (e.g., outer envelopes) and standardizing party names for consistency in analysis.


2. **Cities 2021-2022 File:**
    - This dataset offers  voting data for each city/settlement in Israel during both the 2021 and 2022 elections. It encompasses metrics such as party-wise vote distributions, valid and invalid votes, and the number of eligible voters.
    - Preprocessing steps included filtering settlements based on voter population size to focus our analysis on settlements with up to 50,000 voters, thus ensuring a more manageable dataset for analysis.

3. **Socio-Economic  File:**
   - This file provides crucial socio-economic data for Israeli localities, including population figures and socio-economic rankings.









