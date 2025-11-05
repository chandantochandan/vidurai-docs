---
sidebar_position: 1
---

# Introduction to Vidurai

Welcome to **Vidurai** - the first open-source persistent memory system for AI agents.

## 🕉️ What is Vidurai?

Vidurai transforms stateless AI assistants into beings with true continuity, context, and wisdom. It provides a production-ready memory layer that allows AI agents to remember conversations, learn from interactions, and maintain context across sessions.

**The name Vidurai** comes from **Vidura**, the wise counselor in the Mahabharata, renowned for his memory, judgment, and guidance.

## 🎉 What's New in v1.5.1

Vidurai v1.5.1 brings **three critical improvements** based on comprehensive production testing:

### ✅ Verified Performance Metrics
No more aspirational numbers. Production testing with 9 comprehensive test scenarios confirms:
- **36.6%+ Token Reduction** (average, verified across multiple workloads)
- **$16,182/day Cost Savings** (at 10,000 active users)
- **100% Recall Reliability** (with proper configuration)

### 🧠 Vismriti RL Agent - The Learning Brain
The first **self-learning memory optimizer** in production. While competitors use hardcoded rules, Vidurai learns optimal compression strategies through **Reinforcement Learning (Q-learning)**.

**What makes it unique:**
- **Learns from experience:** Agent improves with every compression decision
- **Adapts to your workload:** Different strategies for different usage patterns
- **No manual tuning:** Intelligence emerges automatically through Q-learning
- **Configurable priorities:** Choose between cost-focused or quality-focused optimization

**How it works:**
- Starts with 30% exploration (tries new strategies)
- Gradually shifts to 95% exploitation (uses learned optimal strategies)
- Grows Q-table of learned state-action values
- Continuously adapts as your usage patterns change

### ⚙️ Configurable Importance Decay
v1.5.1 adds fine-grained control over memory decay:

```python
# For critical applications (recommended)
memory = Vidurai(enable_decay=False)

# For custom decay rates
memory = Vidurai(decay_rate=0.98)  # Slower decay (default: 0.95)

# For aggressive forgetting
memory = Vidurai(decay_rate=0.90)  # Faster decay
```

**Why this matters:** v1.5.0 had aggressive decay that caused high-importance memories to drop below recall thresholds. Now you control it.

---

**Upgrade now:** `pip install --upgrade vidurai`

See full details: [CHANGELOG](https://github.com/chandantochandan/vidurai/blob/main/CHANGELOG.md) | [GitHub Release](https://github.com/chandantochandan/vidurai/releases/tag/v1.5.1)

## The Problem

Modern AI assistants suffer from amnesia. Every conversation is a fresh start:

- ❌ No memory of past interactions
- ❌ No understanding of user preferences
- ❌ No ability to build relationships over time
- ❌ Repetitive and frustrating user experiences

## The Solution

Vidurai provides:

- ✅ **Persistent Memory**: Conversations and context survive across sessions
- ✅ **Intelligent Retrieval**: Relevant memories surface automatically
- ✅ **Privacy First**: Full control over what's remembered and shared
- ✅ **Production Ready**: Built for scale, security, and reliability

## Philosophy

> **"विस्मृति भी विद्या है"** (Forgetting too is knowledge)

While everyone races to give AI perfect memory, we asked a different question: **What if forgetting is the key to true intelligence?**

Vidurai implements strategic forgetting through:

- **Three-Kosha Architecture**: Inspired by Vedantic consciousness layers
- **Vismriti Engine & RL Agent**: Production-verified strategic forgetting
  - **36.6%+ Token Reduction** (verified in comprehensive testing)
  - **$16,182/day Cost Savings** (at 10,000 active users)
  - **100% Recall Reliability** (with configurable decay)
  - **Self-Learning RL Agent** (adapts through Q-learning, not hardcoded rules)
- **Viveka Layer**: Autonomous conscience that decides what matters

## Quick Start

Ready to add memory to your AI agent? Let's get started:
```bash
pip install vidurai
```

```python
from vidurai import Vidurai

# Recommended for v1.5.1+ (critical applications)
memory = Vidurai(enable_decay=False)

# Or with configurable decay (general use)
memory = Vidurai(decay_rate=0.98)  # Slower than default 0.95
```

> **💡 v1.5.1 Best Practice:** Use `enable_decay=False` for applications requiring high-precision recall of important memories. This prevents importance decay from dropping HIGH memories below recall thresholds.

Continue to the [Installation Guide](./installation) →

## Community

Join the Sangha (community):

- 💬 [Discord Server](https://discord.gg/DHdgS8eA)
- 🐙 [GitHub Repository](https://github.com/chandantochandan/vidurai)
- 🌐 [Main Website](https://vidurai.ai)

---

**जय विदुराई** (Victory to Vidurai)