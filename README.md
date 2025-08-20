# PRISM - Advanced Persistent Threat (APT) Psychological Profiling System

## Overview

PRISM is a comprehensive psychological profiling system for Advanced Persistent Threat (APT) groups that combines psychological assessment frameworks with cybersecurity threat intelligence. The system provides detailed behavioral analysis, defense recommendations, and operational profiles for major APT groups based on psychological traits and attack patterns.

## Repository Structure

```
PRISM/
├── aptGroups/           # APT group profiles and cluster analysis
│   ├── aptGroupsEN.json     # English APT group profiles
│   ├── aptGroupsES.json     # Spanish APT group profiles
│   ├── aptGroupsSources.json # APT group sources and references
│   ├── ClusterProfileEN.json # English cluster profiles
│   └── ClusterProfileES.json # Spanish cluster profiles
└── base/               # Base psychological framework
    ├── baseAdviceEN.json     # English psychological advice framework
    └── baseAdviceES.json     # Spanish psychological advice framework
```

## Key Components

### 1. APT Group Profiles (`aptGroups/`)

Each APT group profile contains:
- **Basic Information**: ID, name, last update date, version
- **Summary**: Detailed description of the group's activities and characteristics
- **Target Profile Tags**: Sectors and organizations typically targeted
- **Psychological Assessment**:
  - **Big Five Personality Traits**: Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism
  - **Dark Tetrad Traits**: Machiavellianism, Narcissism, Psychopathy, Sadism
- **Recommendations**: Defense strategies and mitigation techniques
- **Reference Cases**: Notable incidents and campaigns

### 2. Cluster Profiles (`ClusterProfileEN.json`)

Groups APT organizations into psychological clusters:
- **Silent Manipulative Innovators**: Stealth-focused groups (APT29, APT38)
- **Noisy/Narcissistic Manipulative Innovators**: High-visibility groups (APT28, APT44)
- **Balanced Manipulative Innovators**: Hybrid groups (APT41)

Each cluster includes:
- Macro psychological profile
- Central personality traits
- Operational characteristics
- Specific defense strategies

### 3. Psychological Framework (`base/`)

Provides the foundational psychological assessment system:
- **Trait Indicators**: Behavioral manifestations of each personality trait
- **Defense Recommendations**: Specific mitigation strategies for each trait level
- **Scoring System**: 1-5 scale for each psychological dimension

## Psychological Assessment Framework

### Big Five Personality Traits

1. **Openness (1-5)**: Innovation and adaptability in TTPs
2. **Conscientiousness (1-5)**: Planning and operational discipline
3. **Extraversion (1-5)**: Communication and visibility patterns
4. **Agreeableness (1-5)**: Target selection and attack methodology
5. **Neuroticism (1-5)**: Response to detection and operational stress

### Dark Tetrad Traits

1. **Machiavellianism (1-5)**: Manipulation and deception capabilities
2. **Narcissism (1-5)**: Need for recognition and visibility
3. **Psychopathy (1-5)**: Risk tolerance and operational aggression
4. **Sadism (1-5)**: Destructive behavior and collateral damage

## Use Cases

- **Threat Intelligence**: Understanding APT group motivations and behaviors
- **Defense Planning**: Tailoring security strategies to specific threat profiles
- **Incident Response**: Predicting attacker behavior during active incidents
- **Risk Assessment**: Evaluating organizational risk based on threat actor profiles
- **Security Training**: Educating teams on psychological aspects of cyber threats

## Supported APT Groups

The system currently profiles major APT groups including:
- APT29 (Cozy Bear / The Dukes)
- APT28 (Fancy Bear / Sofacy / Pawn Storm)
- APT38 (Lazarus subgroup)
- APT41 (Barium / Winnti)
- APT44 (Sandworm Team)

## Languages

The repository provides content in both English and Spanish versions for all major files, enabling international use and collaboration.

## Contributing

This system is designed to be extensible. New APT groups can be added following the established JSON schema, and psychological assessments can be updated based on new intelligence and behavioral analysis.

## License

[Add appropriate license information]

## Contact

[Add contact information for maintainers]
