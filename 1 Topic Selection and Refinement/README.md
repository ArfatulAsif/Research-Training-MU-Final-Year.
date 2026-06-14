
##  Project Identity

**Research Title:**
*Rider-POV: A Multimodal Edge AI Approach for Detecting Camouflaged Road Anomalies in Unstructured Traffic*

**Clear Goals:**

1. Introduce a novel, two-wheeler dynamic dataset addressing the "unmarked hazard" corner case.
2. Demonstrate that Deep Metric Learning techniques outperform standard bounding-box detectors on zero-contrast infrastructure.
3. Deploy and benchmark an offline-first, real-time detection pipeline on resource-constrained edge hardware.

**Dataset Description:**
A synchronized visual-inertial dataset comprising real-world, dynamic two-wheeler driving scenes on unstructured roads. It specifically categorizes speed bumps by visibility (marked vs. unmarked) and lighting conditions, validated via localized accelerometer telemetry.



--
















# How to Do Research: A Practical Guide to Topic Selection

*For undergraduate Computer Science students*

This guide walks you through the single hardest part of any first research project: **choosing a topic that is original, doable, and publishable at your level.** Everything else — coding, experiments, writing — gets easier once the topic is right. Read it once end to end, then keep it open while you work.

---

## Part 1 — Start With What Interests You

Before anything else, ask yourself honest questions:

- What topics actually pull your attention?
- Have you ever opened a research paper just out of curiosity?
- Has a senior or teacher pointed you toward a problem worth exploring?
- What kind of projects have you enjoyed building so far?
- When you read a tech headline, does it excite you — or go straight over your head?

There are no wrong answers here. The goal is to notice where your natural curiosity lives, because you are going to spend weeks on this. A topic you find boring will feel impossible long before it is actually finished.

---

## Part 2 — Ground Rules: Using AI Tools the Right Way

Let's be very clear about this up front, because confusion here causes the most problems.

### Can I use GPT (or Claude, Gemini, etc.)?

**Yes — and you should.** Used well, large language models (LLMs) can fast-forward your research by miles:

- They cut literature-search time dramatically. What used to take a week of continuous reading, you can now rough-draft in one or two days.
- They can generate fairly complex ML/DL model code from a single well-written prompt — and it often works.
- They are excellent tutors. When you are a beginner, being able to ask "why does this happen?" and get an immediate explanation is genuinely valuable.

### Where you *can* use LLMs

- Initial brainstorming and discussion
- Topic selection and refinement
- Literature search and organizing your reading
- Answering any conceptual question about your research
- Writing and debugging code
- Editing, proofreading, and formatting your paper

### Where you absolutely *cannot* use LLMs

- **You cannot dump your entire code and results into GPT and tell it to "write the paper for you."** The output will read as generic and impersonal, it will not carry your own voice, and reviewers notice immediately. This is the fastest route to a desk rejection.
- **The final paper must read as your own work.** As a class rule, your submission must score **under 25% on our AI-detection check** before it even goes to review. (No detector is perfect, so treat this as a floor for genuine effort, not a number to game.)
- **You may not generate figures with AI and paste them into the paper.** All figures, charts, and result plots must come from your actual experiments and data.

> **The mental model:** an LLM is your research assistant and tutor — not your author. It helps you think faster; it does not think *for* you.

---

## Part 3 — Tools That Make Research Easier

Set these up before you start, not halfway through.

- **GitHub** — Open a repository for your project from day one. Maintain documentation, keep your literature notes, and commit your code regularly. Your commit history becomes living proof of *when* and *how* you did the work — useful for your supervisor, your defense, and your own sanity.
- **StackEdit** (<https://stackedit.io/app#>) — A clean, browser-based Markdown editor for fast note-taking, especially for collecting paper titles and abstracts as you read.

---

## Part 4 — Research at Your Level: Categories and Example Topics

Below are research directions that undergraduate CS students realistically complete and publish. Notice a pattern: **almost every one is built around a dataset.** (Part 5 explains why.) Use these as inspiration — not as topics to copy outright.

### 1. Medical / Healthcare Dataset Modeling

- Pneumonia classification from chest X-ray images using transfer learning
- Early detection of diabetic retinopathy from fundus images
- Skin-lesion (melanoma) classification from dermoscopic images
- Heart-disease risk prediction from tabular clinical data using ensemble methods
- A novel annotated ECG dataset from local patients for arrhythmia detection

### 2. Business / Finance

- Customer churn prediction for a telecom or subscription service
- Credit-card fraud detection on imbalanced transaction data
- Sales/demand forecasting for small retail businesses using time-series models
- Stock-movement prediction driven by news-headline sentiment
- A dataset of local e-commerce product reviews for rating prediction

### 3. Natural Language Processing (with a Bangla focus)

- **Bangla hate-speech detection** in social-media comments using transformer models
- A benchmark dataset for **Bangla fake-news detection**
- Detecting **cyberbullying in Bangla Facebook comments** (new annotated corpus)
- Sentiment analysis of Bangla restaurant or product reviews
- Bangla–English **code-mixed** text classification
- Abstractive summarization of Bangla news articles

> Bangla NLP is a strong area for students here: high-quality labeled datasets are still scarce, so a careful new dataset *is* a real contribution.

### 4. Voice / Audio

- Bangla spoken-digit or command recognition
- Environmental / urban-noise sound classification
- Cough-sound classification for respiratory screening
- Speaker gender or age identification from voice
- A speech dataset of Bangla regional dialects for accent classification

### 5. Computer Vision — Real-Time Detection (YOLO and friends)

- Real-time vehicle detection and classification in dense local traffic
- Fish-species detection for local fish markets or fisheries
- Bangladeshi currency-note recognition to assist the visually impaired
- Helmet detection for motorcycle riders
- Drone-based path or obstacle detection from aerial imagery
- Real-time pothole or road-hazard detection from dashcam footage

### 6. Agriculture / Plant Science

- Rice- or jute-leaf disease classification from a field-collected image dataset
- Crop pest-infestation detection using drone imagery
- Fruit ripeness or quality grading using computer vision

### 7. Education / EdTech

- Predicting student dropout from academic-performance records
- Automated short-answer grading (including for Bangla responses)
- Student-engagement detection in online classes from webcam frames

### 8. Cybersecurity / Networking

- Phishing-URL detection using machine learning
- Network-intrusion detection on benchmark traffic datasets
- Android malware classification from app-permission features

### 9. IoT / Sensor & Smart Systems

- Human-activity recognition from smartphone accelerometer data
- Air-quality prediction from low-cost urban sensors
- Fall detection for elderly care using wearable sensors

### 10. Recommendation & Information Systems

- Movie or book recommendation using collaborative filtering
- Personalized content recommendation for Bangla readers

### 11. Remote Sensing / Geospatial

- Flood-affected-area mapping from satellite imagery
- Land-use classification from Sentinel-2 imagery

**A fair question:** *"If a headline already exists, why not just ask ChatGPT to improve an existing study?"* You can — incremental work is valid. But the strongest, most publishable undergraduate papers don't just tweak someone else's setup; they bring **something genuinely their own.** Usually, that something is the data. Which brings us to the most important idea in this whole guide.

---

## Part 5 — Why the Dataset Is Your Most Important Contribution

At your level, **a paper built around a dataset is easier to understand, easier to defend, and easier to publish.** Here's the honest reasoning:

- If you think you can improve a *theory* or a *core algorithm*, think again. Those advances typically take PhD researchers or large teams a long time, and there are millions of papers already in the space. You are almost certainly not yet experienced enough to make that claim stand up to review — and that's completely normal.
- In nearly every kind of applied paper, **the dataset is treated as the prime novel contribution.** A new, well-built, well-documented dataset is something reviewers can immediately see the value of.

So make your dataset as **original** as you reasonably can: collect it yourself, target a setting nobody has covered, label it carefully, and document exactly how you built it. That documentation is half your paper.

---

## Part 6 — From Idea to Original Topic: A Worked Example

Let's make this concrete with a real-feeling idea.

> I ride a motorcycle. On the Tamabil road there are many speed bumps, and they're often unmarked or poorly painted — I frequently don't see them in time. **What if we built a dataset of exactly this problem?** Speed bumps photographed from a rider/driver's point of view, including both the white-painted (visible) ones and the unmarked, hard-to-see ones.

That instinct — "this real problem annoys me, and I bet there's no good dataset for it" — is *exactly* how good undergraduate topics are born.

### Step 1: Check whether the work already exists

Have a long, genuine conversation with several LLMs (GPT, Gemini, Claude — use more than one if you can). Ask things like:

- Does research like this already exist?
- If I build this, could it be novel — and *how* would I make it more novel?
- I don't want something overly complex, just solid. What's a realistic scope?

If the answers look promising, move on to a real paper search.

> **Critical caution:** never take an LLM's "I couldn't find anything like this" at face value. LLMs hallucinate, miss recent work, and sometimes invent citations. Their answer is a starting hypothesis — **you must verify it yourself in the actual databases** (Part 7).

---

## Part 7 — Literature Search

### Continue the same conversation to plan your search

Staying in the same LLM thread where you discussed your topic, ask it to help you *structure* the search. A good prompt:

> "Organize my literature-review section into sub-topics, and give me a Boolean query string for each one. I'll run those searches myself, read the results, and decide on my research direction."

### What is a query string? (Boolean search, explained)

A **query string** is a set of keywords combined with logical operators so the database returns precisely the papers you want — instead of thousands of loosely related ones. Learning this well is one of the highest-leverage research skills you can pick up. The core operators:

| Operator | What it does | Example |
|---|---|---|
| `AND` | Both terms must appear — **narrows** results | `road AND "speed bump"` |
| `OR` | Either term may appear — **widens** results | `"speed bump" OR "speed breaker"` |
| `NOT` (or `-`) | Excludes a term | `detection NOT acoustic` |
| `" "` (quotes) | Matches an **exact phrase** | `"object detection"` |
| `( )` (parentheses) | **Groups** logic so it evaluates in the right order | `("speed bump" OR "speed breaker") AND detection` |
| `*` (wildcard) | Matches word variations (where supported) | `detect*` → detect, detection, detecting |

A few rules of thumb:

- Use **OR inside parentheses** to gather all the synonyms for one concept, then join concepts with **AND**. Different countries call the same thing a *speed bump*, *speed breaker*, or *speed hump* — miss a synonym and you miss whole papers.
- Quote multi-word phrases so `"deep learning"` isn't matched as the word *deep* anywhere near the word *learning*.
- Start **broad** (two concepts), see what comes back, then add terms to **narrow** it. If you get 3 results, you're too narrow; if you get 30,000, you're too broad.

### Categorized query strings for the speed-bump project

For *"real-time detection of poorly visible / unmarked speed bumps from a driver's point of view, using a novel dataset of both white-painted and non-painted bumps,"* split the literature into these sub-sections and run these searches in each database:

**A. Speed-bump detection (the core — vision-based)**
- `("speed bump" OR "speed breaker" OR "speed hump" OR "road bump") AND (detection OR recognition)`
- `("speed bump" OR "speed breaker") AND ("deep learning" OR CNN OR "neural network")`
- `("speed bump" OR "speed breaker") AND (image OR vision OR camera)`

**B. Real-time object detection methods**
- `("real-time" OR "real time") AND "object detection" AND (YOLO OR SSD OR "Faster R-CNN")`
- `(YOLO OR YOLOv5 OR YOLOv8 OR YOLOv11) AND (road OR traffic OR driving)`

**C. Road-surface anomaly detection (the close cousin — potholes & cracks)**
- `(pothole OR "road crack" OR "road damage" OR "road anomaly") AND detection AND ("deep learning" OR CNN)`
- `("road surface" OR pavement) AND (defect OR anomaly OR distress) AND detection`

**D. Driving / road-scene datasets**
- `(road OR driving OR traffic) AND dataset AND ("object detection" OR "image dataset")`
- `(dashcam OR "dash camera" OR "driver point of view" OR "ego vehicle") AND dataset`

**E. Detection under poor visibility / low contrast** *(this is where your novelty lives)*
- `"object detection" AND ("low light" OR "poor visibility" OR "low contrast" OR "adverse conditions")`
- `(unmarked OR faded OR "poorly marked") AND (road OR lane OR marking) AND detection`

**F. ADAS & road-safety applications**
- `("advanced driver assistance" OR ADAS) AND (hazard OR obstacle) AND detection`
- `"road safety" AND ("speed bump" OR "speed breaker") AND (detection OR warning)`

**G. Sensor-based alternatives (to position your vision approach against)**
- `("speed bump" OR "speed breaker") AND (accelerometer OR smartphone OR sensor OR IMU)`
- `("road anomaly" OR "speed bump") AND (crowdsensing OR "smartphone sensor")`

Sub-sections **A, C, and E** are where you'll find your closest related work and where you'll argue your contribution. Sub-section **E** is the heart of it: existing speed-bump detectors mostly assume *visible, marked* bumps — your dataset of *unmarked, low-visibility* bumps is the gap.

### Research paper databases

For Computer Science, these are the sources worth your time:

**Essential — start here:**
- [Google Scholar](https://scholar.google.com) — best first stop for papers, citations, and related work
- [IEEE Xplore](https://ieeexplore.ieee.org) — major venue for CS, networking, security, and AI conferences/journals
- [ACM Digital Library](https://dl.acm.org) — one of the most important CS publication databases
- [arXiv](https://arxiv.org) — preprints; often the fastest place to find the newest AI/ML work
- [Semantic Scholar](https://www.semanticscholar.org) — frequently better paper discovery and recommendations than Google Scholar

**Also useful:**
- [SpringerLink](https://link.springer.com)
- [ScienceDirect](https://www.sciencedirect.com)

---

## Part 8 — Collect and Organize the Abstracts

Now turn your searches into structured reading:

1. Open a **separate, fresh LLM thread.** Give it the full context of your research topic *and* your literature plan. Tell it: "I'll paste abstracts one category at a time; for each, advise whether it belongs in this sub-section."
2. For **each sub-section, keep only the top 5–10 most relevant papers.** Resist the urge to hoard — quality over quantity.
3. Record every kept paper — **title + abstract** — in a StackEdit Markdown file, organized by sub-section.

You now have a clean, categorized literature map instead of a chaotic pile of PDFs.

---

## Part 9 — Refine and Finalize Your Topic

Bring it all together. Combine every sub-section's abstracts into one master prompt and ask the LLM to help you lock in the direction:

```
Here are the abstracts of all the literature I've collected on this topic,
organized by sub-section. Please look at all of them carefully and help me
refine my research goals and title.

Tell me:
- what type of data I should collect, gather, or modify
- how I should conduct the research
- a final research title, clear goals, and a dataset description
- the baseline(s) I should aim to match or beat

[paste all abstracts here, grouped by sub-section]
```

The output should give you a sharp title, concrete goals, a defined dataset, and a baseline to compete against. Read it critically — adjust anything that doesn't fit your scope or resources.

---

## Part 10 — If It Works (or Doesn't)

If you now have a tight, original, doable topic: **congratulations — that's the hardest part done.**

If it still feels weak, that's normal. Do one of two things:
- Iterate: go back to the LLM conversation, push harder on novelty and scope, and refine again, or
- Restart cleanly with a different topic from Part 4.

Either way, **don't stall.** And remember you don't have to carry it alone — split the dataset collection, the literature review, and the coding across your team, and keep going. Research is mostly persistence: continue, continue, continue.







# What would I, as your supervisor, do?

1. I will ensure that your selected topic is good, practical, feasible, and doable within the given timeframe.

2. I will guide you whenever you get stuck.

3. I will tell you exactly how to organize and conduct your research for your topic, especially how to annotate datasets, write code, and write the paper.

4. Regarding coding, trust me when I say this: **if my hardware or the available hardware supports it, no matter how complex the code is, I will be able to do it. I am very good at it.** So, you are safe on that end (hopefully, Insha'Allah).
