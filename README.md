# 🗳️ The Shan Voting System: A Simple Framework for Fair and Expressive Group Decisions

*By Shan Liu*

---

## 👋 Introduction

In group decisions — whether it's a product team, a DAO, or a creative collective — we often default to binary voting: *yes* or *no*. But real human sentiment isn’t binary.

What about the times we think:

> *“I don’t love this idea, but I’m not against it either…”*
> *“It’s okay — I won’t block it, but it’s not exciting.”*

These sentiments matter. Ignoring them leads to weak consensus, misaligned priorities, and low enthusiasm. That’s why I created the **Shan Voting System** — a lightweight and expressive way to vote that captures *how strongly* people feel, not just *what* they say.

---

## 🧠 What Is the Shan Voting System?

The Shan Voting System is a 3-tier framework designed for teams, communities, and organizations that want to make better decisions — with more nuance and more fairness.

### 🗳️ The 3 Voting Options:

| Vote Type   | Meaning                                        | Score |
| ----------- | ---------------------------------------------- | ----- |
| ✅ Full Vote | Strong support, excited to move forward        | 1.0   |
| ➗ Half Vote | Passive support — not opposed, but not excited | 0.5   |
| ❌ No Vote   | No support or abstain                          | 0.0   |

Rather than forcing people into YES or NO, this system adds a **neutral lane** — a half vote — for when you want to say, *“It’s fine, but not my top choice.”*

---

## 🔢 How It Works

1. Everyone casts one of the three vote types.
2. Scores are summed:

   * Full = 1 point
   * Half = 0.5 point
   * No vote = 0
3. The total score is divided by the max possible score (number of voters × 1).
4. This gives a percentage — which tells you not just if people approve, but how **strongly** they do.

```text
score_percentage = total_score / (num_voters × 1.0)
```

---

## 📊 How to Interpret the Result

You can define thresholds to guide decisions:

| Score (%) | Interpretation                               |
| --------- | -------------------------------------------- |
| 85 – 100  | ✅ Strong approval — full go                  |
| 70 – 84   | ⚠️ Moderate approval — proceed with caution  |
| 60 – 69   | 🔁 Needs discussion — lack of strong support |
| Below 60  | ❌ Not approved — not enough backing          |

This approach stops weak ideas from sliding through just because “nobody said no.”

---

## 🧪 Example: Two-Person Vote

Let’s say two team members are voting:

| Voter A | Voter B | Total Score | % Score | Outcome       |
| ------- | ------- | ----------- | ------- | ------------- |
| 1       | 1       | 2.0         | 100%    | ✅ Strong pass |
| 1       | 0.5     | 1.5         | 75%     | ⚠️ Moderate   |
| 0.5     | 0.5     | 1.0         | 50%     | ❌ Not enough  |

The half vote adds **dimension and clarity**, revealing enthusiasm — or its absence — behind a decision.

---

## 🌍 Real Use Cases

This system isn’t just theoretical. It solves real problems across different fields:

### 🧑‍💻 Product Teams

* Prioritize features by passion, not just politeness.
* Avoid shipping “meh” ideas just because no one blocks them.

### 🧱 DAOs and Cooperatives

* Bring emotional clarity to community governance.
* Reduce “passive approvals” and drive more intentional voting.

### 🤖 AI Agent Collectives

* Let agents express confidence levels in group decisions.
* Useful for multi-model coordination and LLM ensembles.

### 🧩 Peer Review & Creative Panels

* Express “this is okay but not exceptional” without hard rejection.
* Great for hackathons, grants, juries, and feedback sessions.

### 🗺️ Community Platforms

* Replace binary upvotes with expressive signals of support.
* Add nuance to public roadmaps and community requests.

---

## 💡 Why It Matters

The Shan Voting System is:

* **Expressive** — it captures subtlety and emotional intent.
* **Inclusive** — gives space to the uncertain or hesitant.
* **Fair** — stops the loudest voice from dominating.
* **Lightweight** — easy to implement in forms, tools, or conversations.

In a world of increasing complexity and collaboration, we need more than just thumbs up/down. We need better tools to hear the *gray areas* — and make decisions that reflect real group energy.

---

## 🧱 How to Use It

Use it in:

* Google Forms
* Discord bots
* Product voting boards
* DAO governance proposals
* AI simulations
* Even sticky-note retrospectives

All you need is a place to let people choose:
✅ | ➗ | ❌ — and a way to total and interpret the result.

Want to implement it in code? Here's the spec: [GitHub Repo](https://github.com/shanni)

---

## 🐣 Origin Story

I created this voting system because I kept seeing decisions get made on:

* Silence.
* Shrugging.
* “I guess it’s fine.”

The problem wasn’t that people were saying yes — it’s that they weren’t *excited*.

I wanted a way to design for **group enthusiasm**, not just group permission. That’s where the Shan Voting System began.

---

## 🧭 Try It, Use It, Fork It

Feel free to use this system, remix it, or build tools with it. If you do, I’d love to see how — tag me on [Twitter](https://twitter.com/shanni_talks) or GitHub!

This project is licensed under MIT and made to empower better decisions, by real humans (or intelligent agents) in the messy middle.

> *Let people say: “I’m not blocking, but I’m not excited either.” Let that shape the future.*
> — The Shan Voting System

---

## 🚀 Get Involved

* ⭐ Star the GitHub repo: [github.com/shanni/MISC](https://github.com/shanni/MISC)
* 🛠️ Use it in your team or project
* 🧵 Start a thread on Twitter or Farcaster with your feedback
* 🧰 Build a voting plugin or bot and credit “Shan Voting System”

---

Thanks for reading — and happy voting.

```

---

Would you like me to create a cover image and GitHub badge for the Medium post? Or export this to a Notion doc or HTML blog format?
```
