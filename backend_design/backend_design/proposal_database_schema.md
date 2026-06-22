Proposal Database Schema

Purpose

This schema defines how proposals are stored, evaluated, ranked, and analyzed.

The proposal system is the core engine of the PNG Youth Platform.

---

Proposal Record

Each proposal contains:

- proposalId
- title
- category
- problemStatement
- proposedSolution
- implementationSteps
- provinceOrigin
- createdBy
- createdAt
- updatedAt
- status

---

Community Metrics

- supportCount
- commentCount
- suggestionCount
- shareCount
- viewCount

---

Proposal Quality Metrics

- urgencyScore
- feasibilityScore
- impactScore
- diversityScore
- regionalInfluenceScore
- proposalScore

---

Proposal Score Formula V1

ProposalScore =

(2 × SupportCount)

+ (1 × CommentCount)

+ (1.5 × SuggestionCount)

+ UrgencyScore

+ CategoryWeight

+ RegionalInfluenceScore

+ DiversityScore

---

Diversity Formula

DiversityScore =

NumberOfSupportingProvinces × 3

Purpose:

Reward proposals that receive support from many provinces.

---

Regional Influence Formula

RegionalInfluenceScore =

Support × ProvinceWeight × ParticipationFactor

Purpose:

Incorporate provincial representation while preventing domination by large urban centers.

---

Future AI Metrics

Future versions may estimate:

- Expected Cost
- Expected Impact
- Implementation Difficulty
- Risk Level
- Success Probability
- National Priority Ranking

These metrics will support AI-assisted decision-making.