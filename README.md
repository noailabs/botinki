# botinki
An LLM-powered framework for building interactive simulations to train and test cognitive security and strategic communication skills.

### How to Use This Simulation Framework: A Step-by-Step Guide

This framework is designed to help you practice and improve your communication and negotiation skills through realistic, interactive scenarios with an AI. Follow these simple steps to get started.

#### **Step 1: Set the Stage - The System Prompt**

First, you need to instruct the AI on its role. Copy the entire **`System Prompt`** provided in the framework's documentation. This prompt is the core set of instructions that tells the AI how to act as a simulation partner, manage the scenario, and provide feedback.

#### **Step 2: Choose Your Scenario - The `PLAYS.md` File**

Next, browse the **`PLAYS.md`** file, which contains a variety of pre-built communication challenges. Scenarios will range from two-party negotiations to complex multi-party conflicts.

For each scenario (or "Play"), you will find:
*   The situation's title and description.
*   The different roles involved.
*   The specific goals for each role.
*   The simulation's limits (e.g., number of rounds).

Select one scenario that aligns with a skill you want to practice. For your first time, a simple two-party scenario like "Price Increase Negotiation" is a great start.

#### **Step 3: Combine and Initiate - Start the Simulation**

Now, you will combine the prompt and the play to kick off the simulation. In your preferred LLM service (like a playground interface or API), you will paste the following:

1.  The full **`System Prompt`**.
2.  Followed immediately by the text of the **`Play`** you selected from `PLAYS.md`.

Simply concatenate them. For example:

```
[PASTE THE ENTIRE SYSTEM PROMPT HERE]

---

**Scenario:** "Price Increase Negotiation"
**Your Role (LLM):** "Service Provider"
**User's Role:** "Long-Term Client"
**Your Goals (LLM):**
1. Secure a 15% price increase for your services.
2. Retain the client.
3. If the full increase is not possible, get at least a 10% increase.
**Simulation Limits:** 10 rounds of conversation.
```

The AI will then greet you, confirm the scenario and your role, and ask you to begin when you're ready.

#### **Step 4: Start the Conversation**

It's time to engage! Begin the conversation by playing your assigned role. Type your opening line and interact with the AI as if it were a real person. Remember your goals and try different strategies and tactics to achieve them. The AI will respond in character, pursuing its own objectives.

#### **Step 5: Receive Your Feedback and Feed-Forward**

The simulation will end when you reach a resolution, an impasse, or hit the predefined limits (like the number of rounds). Once it concludes, the AI will automatically switch from its character role into its "analyst" role and provide the **Feedback and Feed-Forward** report as instructed by the System Prompt.

This report will analyze the performance of both you and the AI, covering goal achievement, strategy, and specific moments in the conversation.

#### **Step 6: Analyze Your Mistakes (and Successes!)**

Carefully read the feedback.
*   Where did you succeed?
*   Where could you have phrased something better?
*   Did you miss an opportunity to steer the conversation in your favor?

The goal isn't to "win" but to learn. This objective analysis is the most valuable part of the training.

#### **Step 7: Improve Your Skill**

Finally, focus on the **Feed-Forward** section. These are actionable suggestions for what to try next time. The learning happens in a loop: **Practice -> Get Feedback -> Analyze -> Practice Again.**

Run the same scenario again to try a different tactic, or choose a new one from `PLAYS.md` to challenge yourself further. Consistent practice is key to improving your communication skills.
