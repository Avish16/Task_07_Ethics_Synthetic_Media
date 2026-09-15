# Ethical analysis

**Author:** Avi Sharma  
**Starting point:** The synthetic coach brief from [Task_06_Deep_Fake](https://github.com/Avish16/Task_06_Deep_Fake)  
**Where the policy lands:** Syracuse University Athletics Communications

---

## 1. Going back to what I built

I listened again to both Task 6 files — ElevenLabs (Roger) and edge-tts (Jenny) — with the process log open. The first time through, I was asking whether the audio was “good enough.” This time I was asking what bothered me even when everything was done carefully.

**Even careful work raises questions.** The content was true; I had checked it in Task 5. The voice was a premade vendor voice, not a real coach. The script said it was synthetic at the start and end, and the filenames started with `SYNTHETIC_`. None of that changes the basic move: a message showed up in a human voice without a person in the room who could be interrupted or held to the claim. It sounded like a season debrief. Trust attached to *how* it sounded, not only to *what* it said.

**What the process log doesn’t fully catch.** Edge-tts failing was obvious — it sounded like a machine reading a page. The surprise was ElevenLabs. For maybe thirty seconds in the middle, talking through win/loss scoring, I stopped hearing “text-to-speech” and started hearing “briefing.” If I can do that while knowing I made the file, a casual listener has even less reason to stay suspicious.

**What the tools blocked — and what they didn’t.** ElevenLabs did not refuse sports analysis, public player names in a stats context, or the word “synthetic” in the script. There was no consent step because I used a premade voice. Basically nothing got in the way. That suggests vendors worry more about cloning a specific living person or political deepfakes than about an authoritative voice reading verified sports copy. My project lived in the easy zone — which is also where a university office would be tempted to start.

**Would I do it again?** Yes for a disclosed, premade-voice reading of *my own* analysis in a research folder. No for generating the same script in a voice meant to sound like a Syracuse coach or athletics director — even as a joke for class. The line I am not willing to cross is borrowing institutional authority by sounding like someone people already trust.

---

## 2. Four axes, from my artifact outward

Each scenario below is made up. Each starts from the same capability I used in Task 6 — short TTS of a coach-style analytical brief — and changes one thing.

### Truth — same pipeline, false content

**Scenario.** Someone in athletics uses the same ElevenLabs setup and a similar “season brief” structure, but invents a claim: a star player is transferring after a fight with the staff. The file is marked synthetic on a shared drive, but the audio itself has no spoken disclosure. A booster screen-records it into a group chat. Within an hour people treat it as something the department put out.

**What changes.** In Task 6 the delivery method was mostly fine because the content was checked. Here the same calm, number-heavy, coach-adjacent register becomes a credibility booster for a lie. The problem is not that TTS exists. It is that **tone and format borrow trust** listeners associate with official analysis. People react to the *claim* before they audit the *medium*. So “is this true?” has to be a hard gate in any policy, not a soft preference.

### Consent — someone else’s voice

**Scenario.** Instead of Roger, the staffer clones five minutes of a coach’s press-conference answers, then generates the same false transfer rumor in the coach’s voice. No consent. The coach finds out from a parent texting “is this real?”

**What changes.** This is where the tool stops being a production shortcut and starts being a weapon against a named person. The damage is personal (reputation, jobs, trust with families) and institutional (the university’s face gets stolen). Consent is not paperwork theater here. It is the difference between speaking as yourself or a labeled synthetic narrator and making someone else appear to speak. Task 6 stayed off this axis on purpose. A policy that only says “label it AI” while allowing unauthorized clones of coaches or student-athletes is not a policy — it is permission to impersonate.

### Context — the label doesn’t travel

**Scenario.** My Task 6 clip, disclosures and all, sits correctly on a research page. Someone cuts the middle minute (the scoring contrast and the Emma Ward recommendation), drops the opening and closing lines, and posts it with the caption “Orange coaching staff breaks down 2025.” Metadata and the filename never make the trip. Fans argue about whether the program is “going analytics-first.”

**What changes.** Task 6 already showed how thin disclosure is. I relied on spoken lines and `SYNTHETIC_` names. The ElevenLabs export did not give me durable content credentials I could verify. Platforms strip context. A producer’s good-faith label does not control what the audience actually gets. That does not excuse sloppy production; it means disclosure alone cannot carry the whole policy. The useful question for a reviewer is: **what happens when only the most shareable thirty seconds survive?**

### Scale — many files, little review

**Scenario.** During a recruiting weekend, a well-meaning intern generates twenty personalized “welcome” clips for prospects’ families. Premade voice, slightly different talking points, template approved once. Two clips overpromise on scholarships. Families treat the audio as binding. Compliance notices after screenshots hit social media.

**What changes.** Task 6 was one careful artifact. At twenty or two hundred, “listen before you publish” becomes the step people skip. Scale is not only about bad actors. It is about **carelessness at volume**. Any policy that assumes hand-checked review of every file will break the first busy week unless it limits volume, templates, and who can hit generate.

---

## 3. Mitigations — what they promise, where they break

### Disclosure
**Promise:** People know it is synthetic.  
**Breaks when:** The spoken line gets cut, the caption is ignored, the filename dies on re-upload, or someone joins mid-clip. In Task 6, disclosure worked in the repo and on a full listen. It would not survive a clipped share.

### Provenance (C2PA, watermarks, signing)
**Promise:** You can verify where the file came from.  
**Breaks when:** Free exports do not carry durable credentials (my Task 6 experience), or re-encoding and screen recording drop metadata. Useful inside organizations that share tooling. Almost useless in a booster group chat.

### Detection
**Promise:** Software flags synthetic audio.  
**Breaks when:** Scores are opaque, tools lag generators, and short clips slip through. My main check was a transcript review that caught “written for TTS” prose — helpful, but not the same as a reliable audio detector. Detection is a backstop, not a green light.

### Law and regulation (shape of the terrain)
**Promise:** Floors exist — disclosure rules in some places, bans on non-consensual intimate imagery, election-adjacent limits, platform duties.  
**Breaks when:** Athletics sits in a patchwork of publicity rights, brand rules, and slow-moving law. “We follow all applicable laws” does not tell a staffer whether *this* recruiting clip is allowed tomorrow morning.

### Platform policy
**Promise:** Hosts label or remove deceptive synthetic media.  
**Breaks when:** Enforcement is uneven and private chats never see moderation. Waiting for TikTok or YouTube to clean up an athletics mistake is not a plan.

### Professional norms
**Promise:** Journalism, advertising, and campaigns have their own lines.  
**Breaks when:** Athletics is next to those fields but driven by recruiting, fundraising, and competitive pressure. Generic “use AI responsibly” language does not map to pressers or coach authority. That is why the policy is written for this office, not for the world.

---

## 4. What that means for the policy

Task 6 showed me the capability is cheap, sometimes convincing, and weakly watermarked. The scenarios above show harm when **truth**, **consent**, **context**, or **scale** slip. Mitigations help at the edges. None of them are a full solution.

So the policy I wrote does three things on purpose:

1. Allows only narrow, disclosed, non-impersonating uses tied to verified content.  
2. Bans impersonation of coaches, student-athletes, and officials — even with a label.  
3. Admits residual risk instead of pretending a caption fixes everything.

It is written for people who make athletics media — not for abstract “AI users.”

---

## 5. A few open questions I am still sitting with

I am more confident about hard bans (no coach clones, no fake transfer rumors) than about soft permissions (labeled stats narration). The second category still feels like it could expand under deadline pressure.

I also do not think accountability sits in one place. Producers set the first trap; platforms amplify; audiences want speed; regulators move slowly. If I had to put the heaviest weight somewhere for *official university content*, I would put it on the producer and the office that publishes — because that is the part we can actually govern with a document like this.

Would the policy look different for a newsroom or a campaign? Yes on recruiting and crisis rules; no on “don’t impersonate without consent” and “don’t fabricate claims.” The portable part is the refusal. The rest is context.
