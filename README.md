# Assessment #1 - Depth of Field

**Name:** Sam Selvaraj
**Course:** CS 5330 - Assessment #1: Classical Vision Topics
**Topic:** Depth of Field

**Video link:** https://youtu.be/jzoFGU5RuRM

**Late days taken:** 2

---

## Reflection

I got depth of field as one of my two topics and picked it over the other one mostly because I actually take photos as a hobby, so I already had some intuition for it going in. I just didn't know the actual math behind why it works the way it does. 

Building the video around the thin lens model from lecture was the easiest part since we'd just covered it, so I could lean on that instead of re-deriving everything from scratch. The circle of confusion was the concept I spent the most time on. It's simple once it clicks (a blur disc that's small enough just looks like a point) but I went back and forth on how to explain "small enough" without it sounding hand-wavy, since the threshold really is just something we define, not a hard physical cutoff. I really enjoyed making the visualizations. They helped me explain the concept better!

I added the eye/accommodation slide because while researching I found it was a nice parallel. The eye does basically the same thing a camera does (change effective aperture via the pupil, refocus via the lens), and it gave me a way to connect the physics back to something everyone already has direct experience with, without adding a topic that overlaps with anyone else's assessment. I feel this was necessary to understand how depth of field causes the tilt-shift effect that we see!

I wanted to show a few pictures that I had editted to demonstrate how tilt-shift effect can be replicated by just applying a gaussian blur filter at an angle. Unfortunately, the video was too long for that!

So, here it goes :P

<img width="1920" height="2560" alt="tilt-shift using gradient blur" src="https://github.com/user-attachments/assets/c2cbccad-e7be-47f4-8792-676ed3dee5ad" />



## Resources Used

- Course lecture material and outline (thin lens model, pinhole model, perspective projection)
- [Depth of Field Explained](https://www.youtube.com/watch?v=Bs9L_9iBVLQ) — general refresher on DoF concept
- [Depth of Field video](https://www.youtube.com/watch?v=qfkvw-Lrn7Q) — additional explanation reference
- [Wikipedia: Depth of field](https://en.wikipedia.org/wiki/Depth_of_field) — near/far limit formulas, hyperfocal distance formula
- [Photo StackExchange: What exactly determines depth of field?](https://photo.stackexchange.com/questions/9624/what-exactly-determines-depth-of-field) — sanity-checking the four factors and the "why" behind each
- [Video reference](https://youtu.be/34jkJoN8qOI) — used for the eye/accommodation section
- [Video reference](https://youtu.be/6LuvQdGXb4M) — general background
- Tilt-shift example clip 1: https://www.youtube.com/shorts/kY_P0rY5z6Q
- Tilt-shift example clip 2: https://www.youtube.com/shorts/xV7XDF7PLQw

## Acknowledgement of LLM Use

I used Claude as a learning aid while preparing this topic, primarily for:
- Talking through and double-checking my understanding of the hyperfocal distance and near/far DoF formulas before I used them on screen
- Getting feedback on how to structure the explanation so it builds on the thin lens model from lecture instead of repeating it
- Building an interactive HTML visualization (ray diagram / circle of confusion / four-factors simulator) that I used as a reference while making my slides and to help me visualize the concepts myself

I did not use an LLM to write my narration or script word-for-word. I wrote and recorded that myself. I did not collaborate with another student on this topic.

## Optional: YouTube Channel

[x] Yes, I'd like my video considered for the optional non-commercial YouTube channel

---
