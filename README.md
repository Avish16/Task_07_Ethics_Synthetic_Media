# Task_07_Ethics_Synthetic_Media

I built synthetic audio in Task 6. This repo is what came next: reasoning about what that capability means, then writing a policy a real office could actually use.

**Author:** Avi Sharma  
**Setting for the policy:** Syracuse University Athletics Communications

---

## Where this comes from

In [Task_06_Deep_Fake](https://github.com/Avish16/Task_06_Deep_Fake) I took a verified coach-style brief from my lacrosse stats work and turned it into speech with ElevenLabs and edge-tts. Everything was labeled synthetic. The process log captured where the audio sounded convincing and where it fell apart.

Listening again for ethics, the part that stuck was not the obvious machine voice — it was the stretch where ElevenLabs sounded enough like a real briefing that I briefly stopped thinking about the pipeline. That is the gap this project sits in.

No new synthetic media here. No pile of news deepfake cases. Just reasoning from what I built, then a concrete policy.

---

## Why Athletics Communications

Tasks 5 and 6 were about Syracuse women’s lacrosse numbers and a coach-adjacent analytical voice. Athletics communications is where that same toolkit is most tempting (faster content, more volume, “official” sounding audio) and most risky (coaches, student-athletes, recruits, boosters).

A policy written for “everyone” tends to hedge. A policy for this office can draw hard lines — especially on impersonation and recruiting.

---

## What’s in the repo

| File | Contents |
| --- | --- |
| [`analysis/phase_a_ethical_analysis.md`](analysis/phase_a_ethical_analysis.md) | Return to the Task 6 artifact, four thought experiments (truth, consent, context, scale), and a survey of mitigations with where each breaks |
| [`policy/athletics_communications_synthetic_media_policy.md`](policy/athletics_communications_synthetic_media_policy.md) | The policy itself — permitted and prohibited uses, consent, disclosure, review, incidents, refusal — plus an honest limitations section |
| [Task 6](https://github.com/Avish16/Task_06_Deep_Fake) | The audio and process log this analysis depends on (linked, not copied) |

---

## What surprised me

I went in thinking the main ethical problem was deepfaking a real named person. After Task 6, I think the quieter problem is just as important: a **generic** voice reading **true** content can still borrow authority, and free tools barely push back on that use case. Spoken disclosure felt fine on a full listen and useless the second I imagined someone clipping the middle sixty seconds. So the policy bans impersonation even with a label, and treats disclosure as required — but not enough on its own.

---

## How to read this

1. Skim this README.  
2. Read the analysis with the Task 6 repo open if you can.  
3. Read the policy as if you worked in Athletics Communications and had to decide whether a request was allowed on Monday morning.
