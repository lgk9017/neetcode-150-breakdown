# NeetCode 150: The Full Category Breakdown, a Study Order That Sticks, and How to Stop Just Watching Solutions

Search "NeetCode 150" and you're usually after one of three things: the actual list, an honest answer on whether 150 problems is enough, or a way to work through it without turning into a person who watches solution videos and calls it studying. This covers all three, plus the part most list-focused guides skip — what to do when you can solve a problem only because you already saw it.

## The list itself is free, portable, and slightly inconsistent between copies

The NeetCode 150 lives on neetcode.io as a roadmap, organized by topic, and it's free to browse. You'll also find it mirrored in LeetCode community problem lists, GitHub repos with solutions in Python, Java, and JavaScript, and assorted study trackers. That portability is a feature: the list is just 150 LeetCode problem numbers, so it copies cleanly into a spreadsheet.

It also means copies don't always match. Different snapshots swap a handful of problems in and out — you'll see **Valid Sudoku** in some versions of Arrays & Hashing and **Encode and Decode Strings (LC 271)** in others, partly because LC 271 is locked behind a paid LeetCode tier for some accounts. If you're following a GitHub copy from two years ago, expect two or three problems to sit in a different category than today's roadmap. Don't treat that as a problem to solve; the grouping matters more than the exact slot.

## What's actually in the 150

The list is 18 categories deep and expands the original Blind 75, adding topics Blind 75 barely touches: greedy, advanced graphs, 2D dynamic programming. Difficulty leans medium-heavy — the commonly circulated breakdown is **28 Easy, 97 Medium, 25 Hard**, which is worth internalizing before you plan a timeline. Two-thirds of the list is not a warm-up.

| Category | Typical problem count | Why it's there |
| --- | --- | --- |
| Arrays & Hashing | 9 | Hash lookup instincts: complement, frequency, grouping |
| Two Pointers | 5–6 | Converging and partitioning on sorted input |
| Sliding Window | 6 | Variable and fixed windows, plus monotonic deque |
| Stack | 7 | Matching, expression evaluation, monotonic stacks |
| Binary Search | 7 | Index search and "search on the answer space" |
| Linked List | 11 | Pointer surgery and in-place manipulation |
| Trees | 15 | Recursive traversal, BST invariants, serialization |
| Tries | 3 | Prefix structures, word search in grids |
| Heap / Priority Queue | 7 | Top-k, streaming medians, scheduling |
| Backtracking | 9 | Subsets, permutations, constraint search |
| Graphs | 13–19 | Grid BFS/DFS, topological sort, union-find, shortest paths |
| Dynamic Programming | 13–23 | 1-D and 2-D DP, memoization to tabulation |
| Greedy | 8 | Interval and locally-optimal proofs |
| Intervals | 6 | Merge, insert, scheduling overlaps |
| Math & Geometry | 8 | Matrix rotation, modular tricks, formatting |
| Bit Manipulation | 7 | XOR patterns, bit counting, bitwise arithmetic |

Counts for Graphs and DP shift depending on whether a given copy splits advanced graphs and 2-D DP into their own sections. Everything else is stable enough to plan around.

## NeetCode 150 vs Blind 75 vs LeetCode 75

| List | Size | Coverage | Best used for |
| --- | --- | --- | --- |
| Blind 75 | 75 | Core patterns, classic problems | A tight fundamentals pass in 3–4 weeks |
| LeetCode 75 | 75 | Official-feeling curated set | A guided first run, time-boxed |
| NeetCode 150 | 150 | Blind 75 plus greedy, advanced graphs, 2-D DP | Broad coverage once basics are stable |

If you're starting from near zero, the honest sequencing advice from people who've done both is: go smaller first, repeat harder. A 75-problem list you can actually revisit beats a 150-problem list you sample once and forget. Jump into the full 150 when you can already explain why a solution works without looking at notes.

## You can finish all 150 and still freeze in the room

Here's the failure mode that doesn't show up in the list: recognition instead of ownership. You see the problem title, your brain produces the solution, and it feels like mastery because the code runs. Then an interviewer changes one constraint and the whole thing collapses, because you memorized an artifact instead of a decision process.

A blunt test that costs nothing: close the tab and reimplement the problem from scratch, then narrate your approach out loud as if someone is listening — approach, why the invariant holds, edge cases, complexity. If that narration is shaky, you recognized the problem. You didn't learn it.

The fix isn't more problems. It's a longer loop per problem:

1. Attempt cold, with a timer, before any hints.
2. Test your own edge cases instead of trusting the acceptance screen.
3. Redo it from memory two days later, no tabs open.
4. Say the walkthrough out loud, timed, once.
5. Revisit the section three weeks later with two or three problems solved cold.

Volume drops. Interview performance generally doesn't.

## What the list doesn't teach: which pattern the problem needs

Every category in the NeetCode 150 tells you the answer in advance. Open Sliding Window and of course the problem is a sliding window problem. The interview doesn't give you the category header — it gives you a paragraph and a 45-minute clock, and the bottleneck most candidates hit is spending 15 of those minutes trying approaches that don't fit the problem's structure.

That's the specific gap pattern-first platforms target, and it's where AlgoMonster's approach is aimed. It's a text-and-diagram course built by ex-Google engineers that teaches reusable coding patterns — third-party reviews consistently cite 48 of them — with code templates and decision flowcharts designed to answer "which family does this problem belong to" before you write anything. The current checkout page lists 325 lessons and problems, 678 illustrations, and 3,000+ editorials, plus an AI assistant for explanations and hints and a Speedrun mode for timed review. Some reviews cite an older figure of around 231 lessons and problems, so treat the content counts as moving targets rather than fixed specs.

Two things to know before you spend anything:

- **There is no video.** AlgoMonster is entirely text and interactive diagrams. If you learn by watching someone else type, that's a real mismatch, not a small one.
- **System design and behavioral content are introductory.** Engineers targeting L5+ at big tech will need a dedicated resource for the design round. Third-party reviews are blunt about this, and they're right to be.

What it's genuinely good at is the part the NeetCode 150 leaves to you: recognizing the pattern, and having a template you can adapt mid-interview instead of reconstructing from scratch. 👉 [See how AlgoMonster's pattern flowcharts map to the problems you're already doing](https://algo.monster?fpr=li69)

## Every AlgoMonster plan currently listed

AlgoMonster runs annual and lifetime access only — there's no monthly tier. It also rotates promotions aggressively, so the number you see at checkout is the only number that counts. At the time of writing, the pricing page shows the yearly plan at **$99 billed annually** ($8.25/mo equivalent) with a 3-day free trial, and lifetime at **$189 one-time**. A separate checkout state lists **$119/year** and **$459 lifetime** when the deeper promotional pricing isn't running, which tells you the sale is real but not permanent. Budget for either range.

| Plan | Core access | Billing | Price | Purchase |
| --- | --- | --- | --- | --- |
| Free | Limited sample content; enough to judge the text-and-diagram teaching style | Free | $0 | [Start with the free tier](https://algo.monster?fpr=li69) |
| Pro - Yearly | All patterns, lessons and problems; unlimited AI assistant; unlimited Speedrun; company question sets updated monthly; 12 months of access | Billed annually, 3-day free trial on current promo | $99/year at promotional pricing ($8.25/mo equivalent); lists at $119/year outside the sale | [Get Pro Yearly access](https://algo.monster/subscribe?fpr=li69) |
| Pro - Lifetime | Everything in Yearly plus lifetime updates and an internal referral to a top tech company for qualified candidates; some checkout variants also advertise a 1:1 session with the founder | One-time | $189 at promotional pricing; lists at $459 outside the sale | [Buy Pro Lifetime](https://algo.monster/subscribe?fpr=li69) |

The break-even math is the only interesting decision here. At $99/year versus $189 lifetime, lifetime pays for itself in under two years — which matters if you job-hop or interview every couple of years and want to refresh. If this is one 6-week sprint and you're done, the yearly plan is cheaper upfront and you lose nothing but future updates. Note that AlgoMonster also publishes a job guarantee, with terms you should read at checkout rather than take on faith from a review.

## A six-week plan that uses both

This assumes 1–2 hours a day and a moderate baseline — you can write working code, just not quickly under pressure.

**Week 1 — Arrays & Hashing, Two Pointers, Stack.** Do the list problems cold first. If your first instinct on a new problem consistently lands on the wrong structure, read the pattern chapter for that family before continuing.

**Week 2 — Sliding Window, Binary Search, Linked List.** Binary search deserves the extra day. "Search on the answer space" (Koko Eating Bananas, and similar) is the version that trips people, and it's a template problem, not a memorization problem.

**Week 3 — Trees, Tries, Heap.** This is the first section where narration matters more than code. Say the traversal order out loud before writing the recursion.

**Week 4 — Backtracking, Graphs.** Grid BFS/DFS and topological sort cover most of what gets asked. Don't skip union-find just because it's boring.

**Week 5 — DP, 1-D and 2-D.** Expect this to take the full week and then some. Write the recurrence in plain language before touching the code.

**Week 6 — Greedy, Intervals, Math & Geometry, Bit Manipulation.** These four are the lightest sections and the best candidates for Speedrun-style timed reps, since they're narrow enough to drill in a single sitting.

Then stop adding problems and start the redo-and-narrate loop on everything you flagged. Every problem you got wrong in weeks 1–5 gets re-solved cold. That sixth-and-final week is where most of the retention actually happens.

## FAQ

**Is the NeetCode 150 free?**
Yes. The list and roadmap are free to browse on neetcode.io, and the problem links go straight to LeetCode. NeetCode's own paid tier is separate — third-party comparisons put it around $119/year or $219 lifetime — and it's the video-walkthrough route. Neither purchase is required to work through the list.

**Is 150 problems enough for big tech?**
For data structures and algorithms, it covers the ground thoroughly. It does not cover system design or behavioral rounds, which are separate interviews at mid-level and above. Treat 150 as your DSA track, not your whole prep.

**How long does it take?**
Roughly 4–6 weeks at 4–6 hours a day, or 2–3 months of evenings. The medium-heavy difficulty mix is why: 97 of the 150 are Medium, and the 25 Hards don't move fast.

**Do I need a paid platform if I'm already doing the list?**
Only if your bottleneck is choosing the right pattern on an unfamiliar problem. If you already pick the right approach reliably and just need volume, LeetCode plus the free list is enough. If you keep burning 15 minutes on approaches that don't fit, that decision layer is the missing piece — and it's what the flowcharts and templates are built to supply. 👉 [Compare the pattern-based curriculum against your current prep routine](https://algo.monster?fpr=li69)

**What about timed practice and mock interviews?**
Speedrun covers timed reps, but no platform's timer fully replaces a stranger watching you think. Line up at least two human or peer mock interviews before your loop, ideally in the last two weeks.

## The short version

The NeetCode 150 is a well-constructed list — 18 categories, medium-heavy difficulty, and enough coverage that finishing it honestly means you've seen the question space. What it can't do is force you to re-derive problems from memory or teach you to classify an unfamiliar problem in the first two minutes. Those two skills are what the interview actually scores, and they're the reason a pattern template layer is worth considering alongside the list rather than instead of it.
