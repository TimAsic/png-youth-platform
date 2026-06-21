# Province Data Model

## Purpose

This file defines the province-level data used by the PNG Youth Platform.

The information supports:

- Proposal scoring
- Population weighting
- Map visualization
- AI decision support
- Provincial analytics

---

## Province Record Structure

Each province stores:

- Province Name
- Population
- Youth Population
- Active Users
- Proposal Count
- Support Count
- Average Proposal Score
- Top Issues

---

## Core Metrics

### Participation Rate

Participation Rate = Active Users / Population

Measures engagement within a province.

---

### Proposal Activity Rate

Proposal Activity Rate = Proposal Count / Active Users

Measures idea generation.

---

### Support Density

Support Density = Support Count / Population

Measures how strongly proposals are supported.

---

### Provincial Influence Score

Provincial Influence Score combines:

- Population
- Participation Rate
- Support Density
- Proposal Quality

This score is used in national rankings.

---

## Future Expansion

Additional metrics:

- Youth unemployment
- School enrollment
- Infrastructure access
- Healthcare indicators
- Economic indicators