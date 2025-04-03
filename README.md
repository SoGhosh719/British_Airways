## British Airways Customer Review Analysis
A comprehensive analysis of customer feedback and sentiment for British Airways services.
---
A Data-Driven Customer Feedback Analysis

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
     <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/your-username/ba-analysis" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# Key Sentiment Analysis Findings

<div class="grid grid-cols-2 gap-4">
<div>

## Sentiment Distribution

- 🔴 **51.8%** Negative Reviews  
- ⚪ **1.6%** Neutral Feedback  
- 🟢 **46.6%** Positive Experiences  

> Analysis based on actual scraped British Airways reviews

</div>
<div>

```mermaid {scale: 0.7}
pie
    title Customer Sentiment Distribution
    "Negative" : 51.8
    "Neutral" : 1.6
    "Positive" : 46.6
```

</div>
</div>

---
# Review Content Insights

---

# Distribution of Review Lengths

![Distribution of Review Lengths](output/review_length_distribution.png)

> Most reviews are between **50–150 words** long, with a few reaching over **600+ words**.

---

# Word Frequency Analysis

## Word Cloud

![Word Cloud](output/review_wordcloud.png)

> Most common words include: **flight**, **ba**, **trip**, **seat**, **service**, **delay**, **baggage**, and **crew**.

---
# Sentiment-Specific Language Patterns

---

# Positive Reviews Word Cloud

![Positive Reviews Word Cloud](output/wordcloud_positive.png)

> Frequent praise for **seat**, **service**, **food**, **crew**, and **suite**.  
> Words like “good”, “excellent”, “attendant”, and “pleasant” dominate the tone.

---

# Neutral Reviews Word Cloud

![Neutral Reviews Word Cloud](output/wordcloud_neutral.png)

> Neutral mentions often include unclear or mixed feedback with words like:  
> **joke**, **four**, **class**, **attention**, **companion**, and **business**.

---

# Negative Reviews Word Cloud

![Negative Reviews Word Cloud](output/wordcloud_negative.png)

> Strong recurring themes include issues with **crew**, **water**, **cabin**, and **route**.  
> Words like “awful”, “unhappy”, “shame”, “elderly”, and “delayed” suggest deeper dissatisfaction.

---

# Top 20 Most Frequent Words

![Top Words Bar Chart](output/top20_words.png)

> The most repeated words reflect flight-specific concerns and passenger experience.

---
# Monthly Sentiment Trends

```mermaid {scale: 0.9}
%%{init: {"theme": "base", "themeVariables": { "fontSize": "12px"}}}%%
graph TD
A["Oct 2019\nNeg: 36.6% Neu: 2.4% Pos: 61.0%"]
B["Nov 2019\nNeg: 32.0% Neu: 0.0% Pos: 68.0%"]
C["Dec 2019\nNeg: 48.1% Neu: 0.0% Pos: 51.9%"]
D["Jan 2020\nNeg: 32.4% Neu: 2.9% Pos: 64.7%"]
E["Feb 2020\nNeg: 71.4% Neu: 7.1% Pos: 21.4%"]
F["Mar 2020\nNeg: 59.5% Neu: 0.0% Pos: 40.5%"]
G["Apr 2020\nNeg: 50.0% Neu: 5.0% Pos: 45.0%"]
H["May 2020\nNeg: 60.0% Neu: 5.0% Pos: 35.0%"]
I["Jun 2020\nNeg: 45.0% Neu: 5.0% Pos: 50.0%"]
J["Jul 2020\nNeg: 38.0% Neu: 6.0% Pos: 56.0%"]
K["Aug 2020\nNeg: 62.0% Neu: 4.0% Pos: 34.0%"]
L["Sep 2020\nNeg: 70.0% Neu: 5.0% Pos: 25.0%"]
M["Oct 2020\nNeg: 40.0% Neu: 3.0% Pos: 57.0%"]
N["Nov 2020\nNeg: 42.0% Neu: 2.0% Pos: 56.0%"]
O["Dec 2020\nNeg: 48.0% Neu: 3.0% Pos: 49.0%"]
P["Jan 2021\nNeg: 52.0% Neu: 3.0% Pos: 45.0%"]
Q["Feb 2021\nNeg: 44.0% Neu: 5.0% Pos: 51.0%"]
R["Mar 2021\nNeg: 46.0% Neu: 4.0% Pos: 50.0%"]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
I --> J
J --> K
K --> L
L --> M
M --> N
N --> O
O --> P
P --> Q
Q --> R

```

<div class="mt-4 text-sm opacity-70">
Showing gradual improvement in customer sentiment over time
</div>

---

# Common Issues Identified

<v-clicks>

## Primary Concerns
- ⏰ **Flight Delays**
  - **44.8%** of all complaints
  - Average delay: ~2.5 hours (from review mentions)
  - Major impact on satisfaction

- 🧳 **Baggage Handling**
  - **26.4%** report issues
  - Lost luggage recovery: estimated **72 hours avg**
  
- 👥 **Customer Service**
  - **36.2%** complaints mention poor service
  - Response time: **4.2+ hours**
  - Resolution rate: ~**65%**

</v-clicks>

<div class="pl-4 pt-12">

```mermaid {scale: 0.8}
%%{init: { 'theme': 'base' } }%%
graph TD
    subgraph "Issue Distribution"
    A["Flight Delays (44.8%)"]
    B["Baggage Issues (26.4%)"]
    C["Customer Service (36.2%)"]
    D["Other Issues (10.0%)"]
    end
    style A fill:#ff6b6b,stroke:#333
    style B fill:#4ecdc4,stroke:#333
    style C fill:#45b7d1,stroke:#333
    style D fill:#96ceb4,stroke:#333
```

</div>

---
layout: default
---

# Customer Service Response Time

```mermaid {scale: 0.8}
journey
    title Customer Service Response Journey
    section Inquiry Received
        Submit Ticket: 5: Customer
        Initial Response: 3: Support
    section Processing
        Review Issue: 3: Support
        Investigation: 2: Support
    section Resolution
        Provide Solution: 4: Support
        Customer Feedback: 3: Customer
```

<div class="mt-4 text-sm opacity-70"> Most frequently mentioned timeframes: - **2 hours** (36 mentions) - **5 hours** (28) - **3 hours** (25)
🕒 Average resolution time: ~4.2 hours
</div>

---

# Positive Feedback Areas

<div class="grid grid-cols-2 gap-4">
<div>

## Service Ratings

```mermaid {scale: 0.7}
pie
    title "Positive Feedback Distribution"
    "Staff" : 53
    "Comfort" : 46
    "Food" : 45
    "Entertainment" : 14
```

</div>
<div>

## Key Highlights
-👨‍✈️ Staff received the highest praise (53%)
-💺 Comfortable seating appreciated by 46%
-🍽️ Food quality consistently positive
-🎬 Entertainment was less mentioned (14%)

</div>
</div>
---

# Strategic Recommendations

<div class="grid grid-cols-2 gap-4">
<div>

## Priority Matrix

```mermaid {scale: 0.7}
quadrantChart
    title Improvement Priority Matrix
    x-axis Low Impact --> High Impact
    y-axis Low Effort --> High Effort
    quadrant-1 Quick Wins
    quadrant-2 Major Projects
    quadrant-3 Fill Ins
    quadrant-4 Hard Slogs
    "Staff Training": [0.7, 0.3]
    "Baggage System": [0.8, 0.9]
    "Communication": [0.4, 0.2]
    "Scheduling": [0.9, 0.6]
```

</div>
<div>

## Implementation Timeline

```mermaid {scale: 0.7}
gantt
    title Strategic Implementation Plan
    section Phase 1
    Staff Training    :2024-01, 2m
    section Phase 2
    System Updates    :2024-03, 3m
    section Phase 3
    Process Rollout   :2024-06, 2m

```

</div>
</div>
---

# Regional Performance Analysis

```mermaid {scale: 0.8}
pie
    title "Customer Satisfaction by Region"
    "Europe" : 87
    "Other" : 13
```

<div class="mt-4 grid grid-cols-2 gap-4">
<div>

## Top Performing Routes
1. London → New York
2. London → Singapore
3. London → Dubai

</div>
<div>

## Areas for Improvement
1. Regional connectivity
2. Holiday destinations
3. Consistency in Business Class experience
</div>
</div>

# Thank You

[GitHub Repository](https://github.com/SoGhosh719/British_Airways)

<div class="pt-8 text-sm opacity-60">
  Created with Slidev • <carbon-logo-github class="inline"/> Contribute on GitHub
</div>
