User Database Schema

Purpose

This schema defines how users are represented and measured within the PNG Youth Platform.

The goal is to reward constructive participation rather than popularity.

---

User Profile

Each user stores:

- userId
- fullName
- username
- email
- province
- region
- ageRange
- joinDate
- verificationStatus

---

Activity Metrics

- proposalCount
- supportCount
- commentCount
- suggestionCount

---

Reputation Metrics

- acceptedSuggestions
- proposalSuccesses
- constructiveComments

---

Reputation Score Formula

ReputationScore =

(5 × AcceptedSuggestions)

+ (3 × ProposalSuccesses)

+ (2 × ConstructiveComments)

+ (1 × SupportsGiven)

Purpose:

Reward users who contribute useful ideas.

---

Civic Influence Score

CivicInfluenceScore =

ReputationScore

× ParticipationRate

× ConsistencyFactor

Purpose:

Measure long-term contribution to the platform.

---

Province Analytics

Each user contributes to:

- Provincial Participation Rate
- Provincial Influence Score
- National Consensus Metrics

---

Future AI Variables

Future versions may include:

- Expertise Areas
- Policy Interests
- Collaboration Score
- Leadership Score
- Trust Index

These variables will support recommendation systems and AI-assisted decision making.