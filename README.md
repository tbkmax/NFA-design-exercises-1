[n06r.md](n06r.md)  

[n08r.md](n08r.md)  

[n10r.md](n10r.md)  

[n12r.md](n12r.md)  

[n14r.md](n14r.md)  


1. which problem(s) gave you the most trouble? Did you avoid any problem that is too challenging to finish by deadline? Did you ask questions to AI/instructor?
   1. No
   2. No
   3. Ask about what is "gold-st-ring"

2. which problem(s) surprised you with a "gold-st-ring"? Which next state(s) did you not account for in the subset of next states? why? How to make sure you avoid such errors in your future flight/traffic/compiler state controller tasks, or in the near future, the course projects/exams?

   - Problems: `n10` surprised me with a "gold-st-ring" that I omitted states reachable only via ε-transitions, which later produced unexpected accepting behaviour.
   - Why: I computed moves before computing full ε-closures and simplified subsets prematurely, overlooking indirect ε-paths.
   - How to avoid this: keep a small transition table and a checklist for the subset construction steps
3. Other insights/comments/questions that you want the grader/instructor to know.
   1. No

