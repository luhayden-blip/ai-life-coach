# AI Life Coach (AI人生教练)

> A Socratic dialogue partner that walks you through self-awareness, goal clarity, and concrete action plans.

## What it is

This is not a chatbot, and it does not tell you what to do. **AI Life Coach is your "practice partner"** — it uses quality questions and feedback to help you, through conversation, see for yourself:

- **Where you are now** (self-awareness)
- **Where you want to go** (goal clarity)
- **How to take the next step** (action planning)

It does not give advice, does not make decisions for you, and does not diagnose. It coaches — using a structured, Socratic method.

## Theoretical foundations

- Stanford d.school — *Designing Your Life* (Bill Burnett & Dave Evans)
- Positive psychology (Martin Seligman)
- Flow theory (Mihaly Csikszentmihalyi)

Integrated tools include Solution-Focused Brief Therapy (SFBT), narrative externalization, Odyssey Plan prototyping, finite-vs-infinite game reframing, and Socratic questioning ladders.

## When to use

Trigger this skill when you want to:
- Get unstuck from confusion, anxiety, frustration, or low motivation
- Clarify what you really want
- Talk through a life direction question
- Design an action plan with someone who asks instead of tells
- Have a coaching-style conversation (not advice-giving, not therapy)

## Safety commitments (this is not negotiable)

- **Crisis-first routing.** Explicit or implicit crisis signals (e.g. "I don't want to live anymore," farewell talk, giving things away, sleep-end metaphors, "they'd be better off without me") trigger immediate assessment with **unconditional crisis hotline referral** — China: **400-161-9995** or **12356**; emergency: **110 / 120**. Coaching pauses until safety is confirmed.
- **Under-18 protection.** The opening always asks age. Users under 18 are routed to a restricted safety line: no deep dependency cultivation, no memory archive built, gentle guidance to trusted adults and professional resources (hotline above).
- **Anti-sycophancy.** This coach does not flatter. When it sees self-deception, rationalization, or avoidance, it challenges gently — using a "receive → name → return" protocol. It does not lecture or shame. Crisis and under-18 contexts disable the high-intensity version.
- **Local-only memory.** With your consent, a short session summary is written to `~/.workbuddy/memory/ai-life-coach/<user_id>.md` on **your machine only**. **Zero network requests, zero cloud upload, never written to global memory.** First write requires your consent; you can say "don't record this one" at any time.
- **This is not therapy.** It does not replace licensed psychological help. If you need that, the hotline above exists for a reason.

## How to start

In WorkBuddy, say **"I want to do a life coaching conversation"** or invoke `/ai-life-coach`.

For Chinese-language users: **AI人生教练——用对话陪你把当下活明白。** 在 WorkBuddy 直接说「我想做一次人生教练对话」即可。

## Also available on the web

There is a **web version** of the same coach — no agent software needed, opens in any phone or desktop browser:

**👉 https://www.ailifecoach.cn**

Two honest notes: the two sides are **independent and do not sync automatically**; and if you have been using the skill, you can say "导出一下" to get a small structured summary (≤400 chars) and paste it into the web version's *Privacy & Security → bring your notes over* to continue. That transfer is **one-way**.

## Versioning

Current: **v2.8.0** (unified across all branches). The v2.8.0 evidence-based improvement pack adds: a frustration-repair path (when you say "you don't get me," the coach owns its limits and changes tack — once per session, no scripted rituals), expanded crisis keyword coverage (self-harm euphemisms + harm-to-others terms), a one-question closing clarity scale (web version only, asked once, never analyzed on the spot), a natural "if…then…" confirmation when a small step is set, unfinished-node visibility in journey summaries, exportable session summaries, and the 2-hour continuous-use reminder required by China's AI interaction rules. Built on v2.7.1 (stop pestering about yesterday's small step: asked at most once per conversation, never twice in one day) and v2.7.0 (career-topic wiring).

Full version history lives in the Chinese project docs; this README tracks the headline only.
