# Notes on Growing 25/17

> 🎯 ***Get into DPO***

## TUE
+ Learned about bucket sort  
    + Under specific conditions — linear time + space complexity only  
+ Cleaned up the notes inbox (notes → flashcards)  
    + Got a basic instruction set for generating flashcards, but it still felt like running errands  
    + Definitely need an agent — something to open notes, extract high-quality flashcards, and push to Anki... maybe with DSPy?

---

## WED
+ Back to DSPy — it’s been a while  
    + Way easier now — no need to bury myself in the docs anymore  
    + Heard about DSPy 3.0 dropping soon — perfect timing!  
+ Shifted my thinking on prompt engineering  
    + Used to think *shorter prompts = better performance* (intrinsic capacity ↑, less context pooling)  
    + Found some hacked prompts from proprietary orgs  
    + DSPy basically uses prompts for LLMs. How does that make output consistent?
    + Feels more like an annealing process now.

---

## THU
+ Built a local app to help me practice more natural English  
    + DSPy programming + free-tier Gemini API  
    + Super easy and fun — a few cracks here and there, but still rolling  
+ Thinking ahead:  
    + Should I focus on end-to-end flows, or maximize flexibility?  
    + Big decision points coming up as I extend this into a fuller app  
+ Published my notes to GitHub  
    + Strong need for a static site: searchable, wiki links, pandoc-rendered pages

---

## SAT
+ Prompting *all day!*  
    + Stepped back from hardcore building of the Anki flashcard generator  
        + Maybe a high-quality prompt is enough for now  
    + Learned some pinpoint lessons from OpenAI  
        + Watched a DeepLearning.AI video — huge step forward in understanding prompting  
    + Realized:  
        + You’re basically instructing an LLM where you want the next token sampled from  
        + Putting a Korean token in the instructions explicitly helped fix a bilingual problem

---

## SUN
+ Built an Obsidian plugin!  
    + Uses spaced repetition to sync Obsidian notes with Anki  
    + Starter code from Gemini — solid foundation  
+ Hit some syncing issues  	
    + Initial sync works, but errors pop up afterward  
    + Needs fixing — maybe add an auto-sync feature too  
+ For now: using it locally. Planning to polish and eventually release.

---

## Recap  
👏 Repo-based workflows locked in — marching toward real applications. Big improvements in my note-taking system.  
🔧 Pretty far off from the DPO goal I set for the week. Focus shifted day by day. Need more consistency in sticking to a plan.
