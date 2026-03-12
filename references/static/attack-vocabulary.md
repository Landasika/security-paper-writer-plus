# Attack Vocabulary & Phrases

Security-specific vocabulary for describing attacks, vulnerabilities, and threats.

## Attack Actions

### Exploitation
- exploit a vulnerability
- leverage a flaw in
- take advantage of
- abuse the mechanism
- manipulate the system
- circumvent the protection
- bypass the security check

### Compromise
- compromise the integrity of
- gain unauthorized access to
- escalate privileges on
- hijack the session/process
- inject malicious code into
- exfiltrate data from

### Disruption
- disrupt the availability of
- cause denial of service
- overwhelm the system
- trigger a crash in
- induce a race condition

## Vulnerability Types

### Injection
- SQL injection
- Cross-site scripting (XSS)
- Command injection
- Code injection
- LDAP injection
- XML injection

### Authentication/Authorization
- authentication bypass
- privilege escalation
- session hijacking
- credential stuffing
- brute force attack

### Memory Safety
- buffer overflow
- use-after-free
- double free
- integer overflow
- heap corruption

### Cryptographic
- weak encryption
- insecure key generation
- side-channel attack
- padding oracle attack
- cryptographic downgrade

## Adversary Capabilities

### Network Access
- "An adversary with network access can..."
- "A man-in-the-middle attacker can..."
- "An on-path attacker can..."
- "A remote attacker can..."

### Local Access
- "A local attacker with user privileges can..."
- "An attacker who has compromised a user account can..."
- "An insider threat can..."

### Physical Access
- "An attacker with physical access can..."
- "A cold boot attack allows..."
- "An evil maid attack can..."

## Impact Description

### Data Breach
- "This allows attackers to access sensitive data including..."
- "The vulnerability exposes [data type] to unauthorized parties."
- "Attackers can exfiltrate [X] records containing..."

### System Compromise
- "This leads to complete system compromise."
- "Attackers can achieve remote code execution."
- "The vulnerability allows arbitrary code execution."

### Service Disruption
- "This can cause service unavailability for [X] hours."
- "The attack renders the system inoperable."
- "This results in denial of service affecting [X] users."

## Attack Conditions

### Prerequisites
- "The attack requires..."
- "For the attack to succeed, the adversary must..."
- "The vulnerability is exploitable when..."

### Constraints
- "The attack is limited to..."
- "This only affects systems that..."
- "The attacker needs [X] to exploit this vulnerability."

## Attack Sophistication

### Low Sophistication
- "This attack can be executed by script kiddies."
- "No specialized knowledge is required."
- "Publicly available tools can exploit this."

### Medium Sophistication
- "This attack requires moderate technical expertise."
- "The attacker needs understanding of..."
- "Custom tooling may be required."

### High Sophistication
- "This is an advanced persistent threat (APT) level attack."
- "Significant resources are required to execute this attack."
- "This attack demonstrates nation-state level capabilities."

## Temporal Indicators

- "Prior to patching..."
- "In vulnerable versions..."
- "Before the security update..."
- "Historically, this attack has..."
- "Recent incidents show..."

## Frequency & Scale

- "affecting millions of users"
- "widespread in the wild"
- "commonly exploited"
- "rarely seen in practice"
- "increasingly prevalent"

---

_Update this vocabulary as new patterns are learned from papers._
