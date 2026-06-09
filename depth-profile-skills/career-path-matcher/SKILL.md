# Career Path Matcher

**Package:** Depth Profile Skills  
**Version:** 1.0.0  
**Author:** HoldCo Labs

## Description

Matches an individual’s personality profile, skills, values, and interests to optimal career paths, industries, and roles. Provides a ranked list of career recommendations with rationale, transition paths, and development plans.

## Trigger Phrases

- "What career should I pursue"
- "Match me to a career"
- "Career path recommendations"
- "What jobs fit my personality"
- "Career assessment"
- "Should I switch careers"

## Instructions

1. **Profile Collection:**
   - Personality assessment results (or conduct quick assessment)
   - Skills inventory (hard skills, soft skills, certifications)
   - Values hierarchy (compensation, impact, autonomy, creativity, stability, growth, work-life balance)
   - Interest areas (Holland Codes: Realistic, Investigative, Artistic, Social, Enterprising, Conventional)
   - Deal-breakers (travel, hours, location, industry)
   - Current situation (education, experience, financial constraints)

2. **Career Matching Engine:**
   - Cross-reference personality with occupational databases
   - Weight matches by:
     - Personality-role fit (40%)
     - Skills alignment (25%)
     - Values match (20%)
     - Interest alignment (15%)
   - Generate top 10 career recommendations

3. **For Each Recommendation:**
   - Why it’s a match (specific trait-to-role mapping)
   - Typical day-in-the-life description
   - Compensation range (entry, mid, senior)
   - Growth trajectory (5-10 year outlook)
   - Required skills/credentials gap
   - Transition difficulty rating (1-5 stars)
   - Industry outlook and demand

4. **Action Plan:**
   - Immediate next steps (this month)
   - 90-day plan
   - 1-year development milestones
   - Resources (courses, certifications, networking groups)
   - People to talk to (informational interview suggestions)

## Configuration Options

```yaml
include_salary_data: true
include_transition_plan: true
max_recommendations: 10
career_stage: "mid"
location_factor: null
remote_preference: "flexible"
```

## Example Prompts

> "I’m a detail-oriented introvert who loves data and problem-solving. I have 5 years in accounting but I’m bored. What careers would be a better fit?"

> "Based on my personality profile, what careers should I consider? I value autonomy and creativity over money, and I want to avoid corporate bureaucracy."

> "I’m thinking about switching from engineering to product management. Does that fit my personality? What would the transition look like?"

## Edge Cases

- **Career changers over 40:** Focus on transferable skills and realistic transition paths
- **Highly specialized backgrounds:** Bridge niche experience to adjacent fields
- **Financial constraints:** Prioritize paths with minimal retraining cost
- **Undecided/overwhelmed:** Narrow down with elimination questions rather than adding options
