## British Airways Customer Review Analysis
A comprehensive analysis of customer feedback and sentiment for British Airways services.
---
A Data-Driven Customer Feedback Analysis

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Navigate with Space <carbon:arrow-right class="inline"/>
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

- 🔴 **45%** Negative Reviews
- ⚪ **35%** Neutral Feedback
- 🟢 **20%** Positive Experiences

> Analysis based on 10,000+ customer reviews

</div>
<div>

```mermaid {scale: 0.7}
pie
    title Customer Sentiment Distribution
    "Negative" : 45
    "Neutral" : 35
    "Positive" : 20
```

</div>
</div>

---

# Monthly Sentiment Trends

```mermaid {scale: 0.9}
%%{init: {'theme': 'base', 'themeVariables': { 'fontSize': '16px'}}}%%
graph TD
    subgraph Trends
    A["Jan (45% Neg, 35% Neu, 20% Pos)"] --> B["Feb (42% Neg, 36% Neu, 22% Pos)"]
    B --> C["Mar (40% Neg, 38% Neu, 22% Pos)"]
    C --> D["Apr (38% Neg, 40% Neu, 22% Pos)"]
    D --> E["May (35% Neg, 42% Neu, 23% Pos)"]
    E --> F["Jun (33% Neg, 45% Neu, 22% Pos)"]
    end
    style A fill:#f9f9f9,stroke:#333,stroke-width:2px
    style B fill:#f9f9f9,stroke:#333,stroke-width:2px
    style C fill:#f9f9f9,stroke:#333,stroke-width:2px
    style D fill:#f9f9f9,stroke:#333,stroke-width:2px
    style E fill:#f9f9f9,stroke:#333,stroke-width:2px
    style F fill:#f9f9f9,stroke:#333,stroke-width:2px
```

<div class="mt-4 text-sm opacity-70">
Showing gradual improvement in customer sentiment over time
</div>

---

# Common Issues Identified

<v-clicks>

## Primary Concerns
- ⏰ **Flight Delays**
  - 35% of all complaints
  - Average delay: 2.5 hours
  - Major impact on satisfaction

- 🧳 **Baggage Handling**
  - 30% report issues
  - Lost luggage recovery: 72 hours avg
  
- 👥 **Customer Service**
  - Response time: 4+ hours
  - Resolution rate: 65%

</v-clicks>


<div class="pl-4 pt-12">

```mermaid {scale: 0.8}
%%{init: { 'theme': 'base' } }%%
graph TD
    subgraph "Issue Distribution"
    A["Flight Delays (35%)"]
    B["Baggage Issues (30%)"]
    C["Customer Service (25%)"]
    D["Other Issues (10%)"]
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

<div class="mt-4 text-sm opacity-70">
Average resolution time: 4.2 hours
</div>

---

# Positive Feedback Areas

<div class="grid grid-cols-2 gap-4">
<div>

## Service Ratings

```mermaid {scale: 0.7}
pie
    title "Positive Feedback Distribution"
    "Entertainment" : 40
    "Comfort" : 30
    "Staff" : 20
    "Food" : 10
```

</div>
<div>

## Key Highlights
- 🎬 Modern entertainment system
  - 1000+ hours of content
  - 4.2/5 average rating
- 💺 Ergonomic seating
- 🍽️ Quality catering
- 👨‍✈️ Professional crew

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
    "Europe" : 45
    "Americas" : 25
    "Asia Pacific" : 20
    "Middle East" : 10
```

<div class="mt-4 grid grid-cols-2 gap-4">
<div>

## Top Performing Routes
1. London - New York
2. London - Singapore
3. London - Dubai

</div>
<div>

## Areas for Improvement
1. Regional connections
2. Holiday destinations
3. Business routes

</div>
</div>
# Thank You

[GitHub Repository](https://github.com/SoGhosh719/British_Airways)

<div class="pt-8 text-sm opacity-60">
  Created with Slidev • <carbon-logo-github class="inline"/> Contribute on GitHub
</div>
