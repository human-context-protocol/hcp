# Human Context Protocol (HCP)
### *A proposed open standard for representing how humans think, communicate, decide, and collaborate — for use by AI systems, agents, and other humans.*

---

## ⭐ What Is HCP?

AI systems today build internal models of us based on **inference** — our tone, our past prompts, our emotional signals, and our interaction history.  
This creates powerful personalization, but also:

- opaque reasoning  
- unpredictable misalignment  
- “sticky” misunderstandings  
- inconsistent identities across systems  
- ethical ambiguity  
- lack of user agency  

HCP proposes a simple, transparent alternative:

> **A user-authored, portable schema that declares how a specific human prefers to be understood and interacted with.**

Instead of AI guessing “who you are,”  
you define your own interface.

HCP is an **opt-in, editable, human-centered specification**  
that aims to stabilize personalization across AI agents and platforms  
while respecting boundaries, emotional safety, and user autonomy.

---

## 🧠 Why HCP Exists  
As AI systems become collaborators — not just tools — the *absence* of a human-side specification is becoming a real limitation.

Software has:

- OpenAPI  
- OAuth  
- JSON Schema  
- MCP (Model Context Protocol)

Humans have:

- no shared interface  
- no portable identity  
- no explicit preferences  
- no declared communication patterns  
- no cognitive operating manual  

AI learns this implicitly.  
HCP makes it explicit.

This is not about controlling AI.  
It’s about controlling **how AI understands *you***.

---

## 🎛 What HCP Represents  
A Human Context Profile can describe:

### **Cognitive Style**
- how the person processes information  
- strengths and friction points  
- preferred reasoning patterns  

### **Communication Preferences**
- tone that works vs tone that shuts them down  
- density (concise / exploratory / structured)  
- pacing and interruptibility  

### **Emotional Profile**
- triggers  
- calming inputs  
- escalation signals  
- how to repair misunderstanding  

### **Decision Style**
- risk tolerance  
- preferred framing (narrative, numeric, systems)  
- temporal orientation  

### **Values & Non-Negotiables**
- what matters most  
- lines that shouldn’t be crossed  

### **Collaboration Style**
- working rhythms  
- feedback preferences  
- conflict style  

### **Memory Permissions**
- what an agent *can* remember  
- what it must never store  
- retention or expiration rules  

### **Boundaries**
- topics to avoid  
- conversational red flags  

All fields are **optional**, **user-controlled**, and **portable** across systems.

---

## 🙅 What HCP Is NOT
- ❌ a personality test  
- ❌ a psychological diagnosis  
- ❌ a manipulation tool  
- ❌ a proprietary identity layer  
- ❌ a behavioral prediction engine  

HCP emphasizes transparency over inference.  
It is fundamentally **non-coercive**.

---

## 📦 Examples
See `/examples/` for working profiles:

- `clay-api.yaml` — a fully detailed human context profile  
- `minimal-profile.yaml` — the smallest valid schema  
- `team-profile.yaml` — an example for collaborative environments  

These examples help illustrate how the specification can be used.

---

## 🧩 HCP v0.1 Specification  
The draft specification lives in: /spec.md
