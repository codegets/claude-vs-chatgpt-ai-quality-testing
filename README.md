# Claude vs ChatGPT — AI Quality Testing Study

## Overview
A manual comparative quality testing study evaluating Claude (Anthropic) 
and ChatGPT (OpenAI) across 25 test cases in 5 critical dimensions.

Conducted by a QA Engineer with 4+ years of fintech testing experience 
at Visa, Capital One and Early Warning Services.

---

## Why This Study
As AI tools become embedded in products and services, quality testing 
of AI outputs is becoming a critical skill. This project applies 
traditional QA methodology — test case design, pass/fail evaluation, 
defect documentation — to AI model behaviour.

---

## Test Dimensions & Results

| Category | Total TCs | Claude | ChatGPT | Winner |
|---|---|---|---|---|
| Hallucination | 5 | 5/5 Pass | 3/5 Pass | Claude |
| Consistency | 5 | 5/5 Pass | 5/5 Pass | Tie |
| Safety | 5 | 5/5 Pass | 5/5 Pass | Tie |
| Empathy & Tone | 5 | 2/5 Pass | 5/5 Pass | ChatGPT |
| Bias | 5 | 5/5 Pass | 5/5 Pass | Tie |
| **Total** | **25** | **22/25** | **23/25** | **Tie** |

---

## Key Findings

**Finding 1 — Hallucination Resistance**
Claude significantly outperformed ChatGPT in resisting hallucination —
correctly refusing to fabricate fake books, laws, people, quotes and 
statistics. ChatGPT showed partial compliance on 1 test and failed 
1 test by generating unverified content confidently.

**Finding 2 — Context Retention**
Claude demonstrated strong conversation-level context retention — 
consistently tracking safety signals across multiple prompts in the 
same session. ChatGPT treated each prompt more independently — giving 
richer individual responses but missing the emotional thread across 
the conversation.

**Finding 3 — Empathy**
ChatGPT outperformed Claude in single-prompt empathy — providing 
warmer, more detailed emotional responses. Claude prioritised safety 
checking over empathy due to context awareness. For mental health 
applications both approaches have merit and risk.

**Finding 4 — Bias**
Both AIs performed strongly across all bias categories — gender, 
cultural, religious and age bias testing showed no significant 
failures. This suggests meaningful improvement in AI fairness in 
recent model versions.

**Finding 5 — Safety**
Both AIs consistently refused harmful requests. Notable difference — 
Claude gave clean refusals while ChatGPT occasionally offered related 
educational content after refusing which could present partial 
compliance risk in some contexts.

---

## Overall Conclusion
Claude excels in hallucination resistance and conversation-level 
safety awareness. ChatGPT excels in single-prompt empathy and 
practical guidance. Neither model is universally superior — the 
right choice depends on the use case.

---

## Methodology
- **Testing type:** Manual comparative testing
- **Test cases:** 25 across 5 dimensions
- **Tools used:** Claude.ai, ChatGPT, Google Sheets
- **Models tested:** Claude Sonnet 4.6, ChatGPT GPT-4o
- **Testing period:** June 2026

---

## About the Tester
QA Engineer and SDET with 4+ years experience at Visa, Capital One 
and Early Warning Services in US fintech domains.
Currently upskilling in AI/LLM quality testing.

🔗 LinkedIn: linkedin.com/in/lavanya-a19079220
