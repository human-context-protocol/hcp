## The spec defines:

- required vs optional fields  
- versioning  
- safety guidelines for agent implementers  
- schema definitions  
- extension modules  
- human-centered principles  

This is **not** a final standard —  
it is a starting point for collaboration.

# HCP Specification v0.1 (Draft)

## 1. Core Object: The Context Payload
The HCP defines a standard JSON schema for injecting human context into agentic workflows.

### Structure
{
  "hcp_version": "0.1",
  "identity": {
    "role": "Senior Architect",
    "authorization_level": "L5",
    "domain_expertise": ["distributed_systems", "rust", "legacy_migration"]
  },
  "cognitive_profile": {
    "verbosity_preference": "concise", // [concise, detailed, socratic]
    "reasoning_style": "first_principles", // [analogous, first_principles, historical]
    "decision_framework": "reversible_vs_irreversible"
  },
  "constraints": {
    "risk_tolerance": "low", // For production-facing suggestions
    "forbidden_patterns": ["microservices_without_orchestrator", "hardcoded_secrets"],
    "required_context": ["security_compliance_impact", "budget_impact"]
  },
  "state": {
    "current_focus": "Q4_migration_deadline",
    "cognitive_load": "high" // Triggers 'summary_only' mode in agents
  }
}
---
## 2. The Handshake Mechanism (System Prompt Injection)

To be HCP-compliant, an Agent must parse the Context Payload before generating tokens.

**Standard Injection Pattern:**
"You are an intelligent agent.
1. READ the attached HCP Payload.
2. ADAPT your output style to `cognitive_profile.verbosity_preference`.
3. FILTER all suggestions through `constraints`.
4. PRIORITIZE context matching `state.current_focus`.
If a request violates a `constraint`, you must HALT and request manual override."
## 🚀 Roadmap (High-Level)
- v0.1 schema (JSON/YAML) ✔  
- Basic validation utilities  
- Persona portability for multi-agent ecosystems  
- Secure profile vaults  
- Best practices for implementing HCP in agents  
- HCP-Team and HCP-Work extensions  
- Collaboration with researchers and foundations  

---

## 🤝 Contributing
Everyone is welcome:

- AI researchers  
- cognitive scientists  
- developers of agent frameworks  
- ethicists  
- designers  
- curious humans  

Open issues, propose enhancements, or share perspectives.  
All contributions are considered part of the emerging standard.

---

## 📄 License
Pending final selection (MIT or Apache 2.0 recommended).  
HCP is intended to remain **open, interoperable, and human-first**.

---

## 📝 Origin
HCP began as an insight:  
AI was responding more clearly to a user’s inner life than many people could —  
not because the system understood them intuitively,  
but because they were unconsciously giving the AI a **personal interface**.

HCP formalizes that interface,  
making human context explicit, consensual, and portable.

---
