# sigma-detection-rules

Sigma detection rules for MITRE ATT&CK techniques commonly encountered in SOC Tier 1 operations.

Each rule includes:
- A validated `.yml` Sigma rule
- A documentation file explaining the attack, detection rationale, and false positive analysis

Built as a hands-on portfolio project while studying for a SOC Analyst role.

---

## Rules

| Technique | Title | Severity | Rule | Docs |
|---|---|---|---|---|
| T1003.001 | LSASS Memory Access | High | [rule](rules/T1003.001_lsass_memory_access.yml) | [docs](docs/T1003.001_lsass_memory_access.md) |
| T1059.001 | Malicious PowerShell Execution | High | coming soon | coming soon |
| T1547.001 | Persistence via Registry Run Keys | Medium | coming soon | coming soon |
| T1021.001 | Lateral Movement via RDP | Medium | coming soon | coming soon |

---

## Repository Structure

```
sigma-detection-rules/
├── rules/      # Sigma YAML rules
└── docs/       # Detection rationale and false positive analysis per rule
```

---

## Tools & References

- [Sigma Project](https://github.com/SigmaHQ/sigma)
- [MITRE ATT&CK](https://attack.mitre.org)
- [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)
