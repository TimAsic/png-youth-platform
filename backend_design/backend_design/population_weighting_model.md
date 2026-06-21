# Population Weighting Model (Version 1)

This model is used to improve decision-making in the PNG Youth Platform by including regional population influence while maintaining fairness.

---

## 1. Province Weight System

Each province is assigned a weight based on population size:

- High population provinces: 1.2
  (e.g. NCD, Morobe)

- Medium population provinces: 1.0
  (e.g. Eastern Highlands, East Sepik)

- Low population provinces: 0.8
  (e.g. Manus, Oro, Gulf)

These weights ensure that population influence is considered without overpowering smaller provinces.

---

## 2. Regional Influence Score (RIS)

The Regional Influence Score measures how much a proposal is supported across different provinces.

Formula:

RIS = Support × ProvinceWeight × ParticipationFactor

Where:
- Support = number of users supporting the proposal
- ProvinceWeight = weight of user's province
- ParticipationFactor = 1 / sqrt(total users in that province)

---

## 3. Diversity Bonus

To ensure national representation, proposals gain bonus points when supported across multiple provinces.

Formula:

DiversityBonus = Number of provinces supporting × 3

This encourages ideas that are shared across PNG, not just one region.

---

## 4. Final Purpose

This model ensures:

- Fair representation of all provinces
- Reduction of urban dominance bias
- Encouragement of nationwide discussion
- Better data for decision-making and future AI analysis

---

## 5. Usage in Scoring System

The Regional Influence Score is combined with other metrics:

- Support count
- Comments
- Suggestions
- Urgency level
- Category importance
- Regional influence

to produce a final Proposal Score.