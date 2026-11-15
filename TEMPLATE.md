# Case: <short name>

| Field | Value |
| --- | --- |
| Date investigated | YYYY-MM-DD |
| Data source | <dataset, lab or KC7 module> |
| ATT&CK | <T-IDs> |
| Verdict | True positive / Benign / Inconclusive |
| Time spent | <hours> |

## Scenario

<What alert, tip or question started this, in 2-3 sentences.>

## Scope and hypothesis

- **Hypothesis:** <what you suspected>
- **In scope:** <users, hosts, IPs, time window>
- **Data examined:** <tables or log sources>

## Timeline

| Time (UTC) | Source | Event | Significance |
| --- | --- | --- | --- |
| | | | |

## Queries used

### 1. <purpose>

```kql
// query
```

**Result:** <what it returned and what it meant>

## Findings and IOCs

| Type | Value | Context |
| --- | --- | --- |
| IP | | |
| Domain | | |
| Hash | | |
| Account | | |

## Containment and remediation

1. <immediate action>
2. <eradication>
3. <recovery>
4. <who you would notify and when>

## Detection gap

<Which rule would have caught this earlier. Link to it in [sentinel-detections](https://github.com/jlam744/sentinel-detections) once written.>

## Lessons learned

- <what you would do differently>
- <what the organization should change>
