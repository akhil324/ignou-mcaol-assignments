# 📘 MCS-211 — Assignment Workbook
**Course:** Design and Analysis of Algorithms (MCS-211) · **Assignment:** MCA_NEW(I)/211/Assign/2026 · **Session:** Jul-2026 (pp. 3–5)
**Assignment pattern:** 4 questions × 20 marks = 80 marks + 20 marks viva — **all 17 parts answered in this workbook**.
**TEE pattern (MCAOL online):** Short 5×4 + Medium 5×10 + Long 2×15 = 100 marks
**Subject profile:** numerical/method — algorithms, step-by-step solves, curves/graphs/trees (`assignment-workbook/references/subject-profiles.md`).
**Book coverage:** complete for MCS-211 (Blocks 1–4, pp. 2–290). Note: the unit does not print pseudo-code for binary search or insertion sort (mentioned only) — those two algorithms are presented from standard references and marked in Q1(c)/Q1(f).
**Audience:** written for a **first-time student with no programming background** (MCAOL does not require a CS degree). Every symbol is read aloud, every algorithm is traced on a tiny input, and `*If you code:*` notes are **optional extras** — skip them without losing anything. If `for`, `A[i]`, bits, graphs or logs are new, read the 📗 primer just below before Q1.

> **🧭 How this workbook works (design rules)**
> 1. **Order:** questions are processed in assignment order, which follows the syllabus (Block 1 → Block 2 → Block 3 → Block 4). Q1 must be processed before Q2, and so on.
> 2. **Add-only study:** a concept is taught once, where it first appears. Later questions *link* to it instead of repeating it — the registry below is the index of what has been explained where.
> 3. **Per question block:** Prerequisite bridge → Lessons (new concepts only) → Traps/self-check → Exam trail → Assignment answer → TEE layer → Verification. Every answer embeds its **verbatim question text (+ question figure, if any)** so no other PDF is ever needed.
> 4. **Out-of-order guard:** if a question needs a concept from an uncovered unit, add only a short "missing prerequisite" note (1–3 lines) and continue; its full treatment comes with its own question.
> 5. **Two layers:** the *assignment layer* builds knowledge + submission answers. The *TEE layer* answers **actual past TEE questions only** — never a made-up "TEE version" of an assignment question. A past question unlocks only when every concept it needs is already in the registry.
> 6. **Dedup applies to teaching, not to exam answers:** a concept is taught once in the study blocks, but every answer (assignment or TEE) is written standalone — it must work in the exam hall with no cross-references.
> 7. **Symbols rule:** never show a symbol without (a) a sentence in plain words, (b) how to read it aloud, (c) why it exists, (d) a tiny example. A code analogy may follow, but only as an optional `*If you code:*` aside. Expand every abbreviation on first use.
> 8. **Figures rule:** anything a table cannot explain cleanly gets a picture — generated with `matplotlib`/`networkx`, or extracted from the source PDF (PyMuPDF clip). Files live in `<workbook>.assets/` and are referenced beside the concept with a numbered caption.
> 9. **Zero-background rule:** the workbook assumes you have never written a program. Universal basics (pseudo-code, binary, arrays, graphs, logs, Σ) are taught once in the 📗 primer; every question block then starts with what it assumes (🧰 L0) and gives a 🔰 explanation for anything not yet covered.

**Marks & time budget (100 marks / 180 min ≈ 1.8 min per mark):**

| TEE slot | Marks | Time | Answer size | Structure |
|---|---|---|---|---|
| Short | 4 | ~7 min | 100–150 words | definition + key points or tiny example |
| Medium | 10 | ~18 min | 300–400 words + small table | definition → method → solve → result |
| Long | 15 | ~27 min | 450–600 words | full treatment, comparison or derivation |

## 🗂️ Progress

| Question | Topic | Book location | Status |
|---|---|---|---|
| Q1(a) | Sieve of Eratosthenes; primes 2…10000 | Block 1 U1/U3, pp. 2–68 | ✅ |
| Q1(b) | Quadratic-time vs exponential-time algorithms | Block 1 U1, pp. 2–28 | ✅ |
| Q1(c) | Binary search with duplicates; worst case | Block 1 U1/U3, pp. 2–68 | ✅ |
| Q1(d) | Big-O / Big-Θ / Big-Ω; asymptotic bounds | Block 1 U2, pp. 29–45 | ✅ |
| Q1(e) | Right-to-left binary exponentiation; 5²³ | Block 1 U3 §3.4.3, pp. 46–68 | ✅ |
| Q1(f) | Insertion sort; best and worst case | Block 1 U1/U3, pp. 2–68 | ✅ |
| Q1(g) | Recurrences; Master method | Block 1 U4, pp. 69–85 | ✅ |
| Q2(a) | Greedy technique & fractional knapsack | Block 2 U1, pp. 86–110 | ✅ |
| Q2(b) | Huffman codes; tree and decoding | Block 2 U1 §1.7, pp. 86–110 | ✅ |
| Q2(c) | Quicksort PARTITION; worst case | Block 2 U2 §2.5.2, pp. 111–147 | ✅ |
| Q2(d) | D&C matrix multiplication; Strassen | Block 2 U2 §2.7, pp. 111–147 | ✅ |
| Q2(e) | Topological sorting; SCCs | Block 2 U3 §3.5–3.6, pp. 148–162 | ✅ |
| Q3(a) | Kruskal & Prim; MST of Figure 1 | Block 3 U1 §1.2, pp. 163–194 | ✅ |
| Q3(b) | Bellman-Ford; shortest paths from A | Block 3 U1 §1.3.2, pp. 163–194 | ✅ |
| Q3(c) | Optimal Binary Search Tree | Block 3 U2 §2.5, pp. 195–218 | ✅ |
| Q3(d) | Matrix-chain multiplication | Block 3 U2 §2.4, pp. 195–218 | ✅ |
| Q3(e) | KMP string matching | Block 3 U3 §3.4, pp. 219–228 | ✅ |
| Q4(a) | Intractable problems; TSP; clique | Block 4 U1–U2, pp. 229–264 | ✅ |
| Q4(b) | NP and NP-complete classes | Block 4 U1 §1.3, pp. 229–264 | ✅ |
| Q4(c) | P / NP / NP-complete / NP-hard | Block 4 U1–U2, pp. 229–264 | ✅ |
| Q4(d) | 3-CNF SAT; 0/1 knapsack; vertex cover; colouring | Block 4 U1–U3, pp. 229–290 | ✅ |

## 🧾 Concept registry

| Concept | First taught | Later links |
|---|---|---|
| 📗 primer: pseudo-code reading, maths toolbox, binary numbers, arrays/indices, graph & tree words, complexity intuition, symbol master table | 📗 Start here (before Q1) | every block links into it |
| Σ notation | Q1(g) L0 | Q2(a) L0 |
| O(·), Θ(·), Ω(·) | Q1(d) L2 | Q1(g), Q2(a) L0 |
| Algorithm properties (finite, ordered, correct, efficient) | Q1(a) L0 | — |
| Sieve of Eratosthenes; O(n log log n) | Q1(a) L1–L2 | — |
| Quadratic vs exponential growth | Q1(b) L1 | Q1(d) L3 |
| Binary search; find-one-then-expand for duplicates | Q1(c) L1–L2 | TEE Jun-2026 2(b) |
| Asymptotic bounds: need and shortcomings | Q1(d) L1/L3 | — |
| Binary exponentiation (left-to-right and right-to-left) | Q1(e) L1–L2 | TEE Dec-2024 1(d) |
| Insertion sort; loop invariant; best/worst | Q1(f) L1–L2 | — |
| Recurrence relation; base + recursive case | Q1(g) L1 | — |
| Master theorem; three cases | Q1(g) L2–L3 | Q2(d) L2, TEE Jun-2025 5(b) |
| Optimisation problem; objective; constraint; feasible; optimal | Q2(a) L1 | — |
| Greedy recipe (select → feasible → include → repeat) | Q2(a) L2 | Q2(b) Huffman |
| Local vs global optimum | Q2(a) L3 | — |
| Fractional knapsack; ratio pᵢ/wᵢ; xᵢ fraction | Q2(a) L4 | — |
| Prefix codes; Huffman merge-two-smallest; decoding | Q2(b) L1 | — |
| Divide and conquer (divide / conquer / combine) | Q2(c) L1 | Q2(d) |
| Quicksort PARTITION with last-element pivot | Q2(c) L2 | TEE Jun-2025 2(b) |
| Best/worst/average sorting complexity | Q2(c) L4 | Q1(f) |
| Block matrix multiplication; Strassen's 7 products | Q2(d) L2 | TEE Jun-2025 2(a) |
| DAG; topological ordering; Kahn's algorithm | Q2(e) L1–L2 | TEE Jun-2026 4(b) |
| Strongly connected components | Q2(e) L3 | — |
| Spanning tree; MST; safe edge / cut property | Q3(a) L1 | — |
| Kruskal's algorithm; disjoint sets | Q3(a) L2 | TEE Jun-2026 1(h) |
| Prim's algorithm | Q3(a) L3 | — |
| Edge relaxation; Bellman-Ford; negative cycles | Q3(b) L1–L2 | — |
| Expected search cost; dummy keys pᵢ, qᵢ | Q3(c) L1 | — |
| OBST tables e, w, root | Q3(c) L2 | — |
| Principle of optimality; overlapping sub-problems | Q3(d) L1 | Q3(c) |
| Matrix-chain m/s tables; parenthesization | Q3(d) L2 | TEE Jun-2026 1(e), Jun-2025 1(g) |
| Naive string matching; Θ(nm) baseline | Q3(e) L1 | — |
| LPS array; KMP linear search | Q3(e) L2 | — |
| Tractable vs intractable; TSP; clique | Q4(a) L1–L3 | Q4(c) TEE |
| Decision problem; certificate; verification | Q4(b) L1 | — |
| P class; NP class | Q4(b) L2 | Q4(c) |
| Polynomial reduction; NP-hard; NP-complete | Q4(b) L3 | Q4(c) TEE |
| 3-CNF SAT | Q4(d) L1 | TEE Dec-2025 1(g) |
| 0/1 knapsack | Q4(d) L1 | — |
| Vertex cover | Q4(d) L1 | Q4(c) TEE |
| Graph colouring; chromatic number | Q4(d) L1 | — |
| Prime / composite / divisor / multiple | Q1(a) L0 | — |
| Binary numbers, bits, LSB/MSB | 📗.3 | Q1(e) L0, Q2(b) |
| Disjoint sets: MAKE-SET / FIND-SET / UNION | Q3(a) L2 | — |
| Binary search tree (structure, root/leaf/depth) | Q3(c) L0 | — |
| Hamiltonian cycle | Q4(a) L2 | — |
| Boolean connectives ∧ ∨ ¬; literal / clause / CNF | Q4(d) L1 | TEE Dec-2025 1(g) |

---

## 📗 Start here — the zero-background primer

> **Who this is for.** This workbook assumes you have **never written a program** and may not have used formal maths since school. Every idea it needs is taught below, once, in plain words. If you *do* have a programming background, skim this section and then skip every `*If you code:*` note in the workbook — they are optional throughout.
>
> **The reading recipe for every question block:** ① read the question text, ② read the *Read it aloud* line, ③ follow the worked example with pen and paper, ④ try the self-check before moving on, ⑤ then read the ✍️ answer — that is what you write; the lessons exist only to make it make sense.

### 📗.1 What an algorithm is — and how to read the pseudo-code here

An **algorithm** is a finite, ordered, unambiguous list of steps that turns an input into an output and always stops. "Finite, ordered, unambiguous, stops" is the whole definition; anything less is not an algorithm.
- *Everyday analogy:* a cooking recipe. "Add salt" is ambiguous; "add 1 teaspoon of salt" is a step an algorithm may contain.
- *Example:* to find the largest of three numbers — compare the first two and keep the larger; compare that with the third; the larger of those two is the answer.

**Pseudo-code** is how this book writes algorithms: English-like lines, not a real programming language. You are not expected to run it — you are expected to *read* it and trace it by hand. Everything it uses is in this table:

| Notation | Read it as | What it means |
|---|---|---|
| `x ← 5` | "x gets 5" | store the value 5 in the box named x (the only way to change a value) |
| `A[i]` | "A sub i" | the value in box number i of the numbered shelf (array) A |
| `A[i] ← v` | "A sub i gets v" | put v into box i; its old value is overwritten |
| `for i ← 2 to n:` | "for i from 2 to n" | repeat the indented steps with i = 2, 3, …, n |
| `for j ← i*i to n step i` | — | start at i·i and jump by i each time: i·i, i·i+i, i·i+2i, … |
| `while condition:` | — | keep repeating while the condition is true (checked before each round) |
| `if … / else …` / `elif` | "else if" | choose exactly one branch (`elif` = "otherwise, if …") |
| `return x` | — | the algorithm's answer is x |
| `TRUE` / `FALSE` | — | a two-valued flag: yes/no, on/off |
| `# comment` | — | a note for humans; not a step |
| `{ … }` | "the set of …" | a collection; its members are listed inside |
| `=` | — | **is equal to** (a comparison). To store a value the book writes `←`, never `=` |

**How to trace by hand** — the one skill used in every question: draw a table with a column for each value that changes (`i`, `j`, `A`, `result`); one row per loop round; write the values *after* each step. Start from the smallest sensible input (n = 3 or 4, not 10000). If you can reproduce the book's trace, you understand the algorithm.

### 📗.2 The maths toolbox (the non-school notation, explained once)

| Tool | Read it aloud | Plain meaning | Tiny example |
|---|---|---|---|
| aⁿ | "a to the power n" | a multiplied by itself n times | 2⁴ = 16; 5²³ = 5 multiplied 23 times |
| √n | "root n" | the number that times itself gives n | √36 = 6; √10 ≈ 3.16 |
| ⌊x⌋ | "floor of x" | round **down** to a whole number | ⌊3.7⌋ = 3; ⌊(1+6)/2⌋ = 3 |
| ⌈x⌉ | "ceiling of x" | round **up** to a whole number | ⌈3.1⌉ = 4 |
| n! | "n factorial" | 1 × 2 × 3 × … × n | 4! = 24; 5! = 120; grows very fast |
| Σ (sigma) | "sum of" | add the terms while the index runs from the lower to the upper limit | Σᵢ₌₁³ i² = 1 + 4 + 9 = 14 |
| log₂ n | "log base 2 of n" | how many times you can halve n until you reach 1 | log₂ 8 = 3 (8→4→2→1); log₂ 1000 ≈ 10 |
| ∈ / ∊ | "is a member of" | belongs to the set | xᵢ ∈ [0, 1] means 0 ≤ xᵢ ≤ 1 |
| \|V\|, \|E\| | "size of V / E" | how many vertices / edges a graph has | Figure 16 has \|V\| = 7, \|E\| = 9 |
| ≤, ≥ | "at most", "at least" | comparisons that allow the equal case | Σwᵢxᵢ ≤ W — the bag never exceeds W |

**Fractions and percentages:** 4/5 = 0.8 = 80% — three ways to write the same amount. Probabilities are fractions of 1: if every case is covered, the probabilities add to 1 (Q3(c) uses this as a check).
**Expanding a Σ:** Σᵢ₌₁ⁿ pᵢxᵢ means "for each item number i, multiply its profit pᵢ by its fraction xᵢ, then add all those products" = p₁x₁ + p₂x₂ + … + pₙxₙ.

### 📗.3 Binary numbers (0s and 1s) — enough for Q1(e) and Q2(b)

Computers store numbers as switches that are either off (0) or on (1). Writing a number in **binary** means writing it as a sum of powers of 2. Each 0/1 digit is a **bit**, and each position is worth twice the position to its right:

> 16 · 8 · 4 · 2 · 1 → `1 0 1 1 1` → 16 + 0 + 4 + 2 + 1 = **23**, i.e. 23 = 10111₂.

- Reading: 2⁴ = 16, 2³ = 8, 2² = 4, 2¹ = 2, 2⁰ = 1.
- To convert a number to binary, subtract the largest power of 2 that fits, then repeat with the remainder: 23 − 16 = 7; 7 − 4 = 3; 3 − 2 = 1; 1 − 1 = 0 → bits for 16, 4, 2, 1 → 10111.
- The **least significant bit** is the rightmost one (the "1s" column); the **most significant bit** is the leftmost.
- *If you code:* many languages print this as `bin(23)` → `'0b10111'`.

### 📗.4 Arrays and indices — the "numbered shelf"

An **array** is a shelf of numbered boxes holding related values: A = [5, 2, 4] has A[1] = 5, A[2] = 2, A[3] = 4. The number in brackets is the **index** (which box); the value is what sits in the box. **This workbook uses 1-based indexing — the first box is A[1]** — because the IGNOU units do. (Many programming languages start at A[0]; *if you code*, check the convention before copying.)
- Two operations cover everything: *read* a box (`A[j]`), and *write* a box (`A[i] ← v`, which destroys the old value).
- A **swap** exchanges two boxes: `swap A[i] with A[j]` needs a temporary holding place unless done with the three-step exchange trick.
- *In place* means the algorithm rearranges the same shelf; it does not build a second one.
- Tracing example: A = [5, 2, 4]; `key ← A[2]` gives key = 2; `A[3] ← A[2]` makes A = [5, 2, 2].

### 📗.5 Graphs and trees — dots, lines and arrows

```
GRAPH — dots joined by lines                 TREE — a graph with no loop

      A ─────20───── B                              o          ← root
      │              │                            /   \
      8             20                           o     o
      │              │                          / \   / \
      E ─────25───── C                         a   b c   d       ← leaves

  ● a VERTEX (or node) is a dot.     ● an EDGE is a line joining two dots.
  ● a WEIGHT is a number on an edge (cost, distance, time).
  ● a PATH is a route along edges.   ● a CYCLE is a route that returns to its start.
  ● DIRECTED graph: edges are arrows (A → B is not B → A). UNDIRECTED: plain lines.
  ● In a tree there is exactly one route between any two dots and no cycle — which is
    why a tree with |V| dots has exactly |V|−1 edges. The top dot is the ROOT;
    dots with no children are LEAVES; DEPTH counts steps down from the root.
  ● DEGREE of a vertex = how many edges touch it. IN-DEGREE = how many ARROWS
    point into it (Q2(e) uses this to start topological sorting).
```

### 📗.6 Complexity without tears — "how the work grows"

**Time complexity** counts *basic steps* (comparisons, additions, swaps) as a function of the input size n — not seconds, because seconds depend on the machine. **Space complexity** counts the extra memory boxes used.
- **Best case** = the luckiest input; **worst case** = the most punishing input; **average case** = typical input. Unless stated otherwise, "the complexity" means the **worst case**, because a guarantee must hold on every input.
- We care about **large n**. A table of step counts makes the warning visible:

| Input size n | n steps | n log₂n steps | n² steps | 2ⁿ steps |
|---|---|---|---|---|
| 10 | 10 | ~33 | 100 | 1,024 |
| 100 | 100 | ~664 | 10,000 | 1.3 × 10³⁰ |
| 1000 | 1,000 | ~9,966 | 1,000,000 | ~10³⁰¹ |

- **Big-O** ignores constants and smaller terms: 3n² + 5n + 7 is written **O(n²)** — "grows no faster than n²". **Big-Ω** is the mirror image ("grows no slower"), **Big-Θ** means both hold ("grows exactly like"). The formal definitions with c and n₀ are in Q1(d); Figure 2 in Q1(b) shows the curves.
- Polynomial (n, n², n³) = practical; exponential (2ⁿ, n!) = practical only for small n. That single split separates tractable from intractable problems (Q4).

### 📗.7 Symbol master table — every symbol used later in this workbook

| Symbol | Read it aloud | Plain meaning | First taught |
|---|---|---|---|
| `←` | "gets" | store the right-hand value into the left-hand name | 📗.1 |
| `A[i]`, `A[1..n]` | "A sub i" | box i of shelf A; boxes 1 to n | 📗.4 |
| n | "n" | the size of the input (number of items, boxes, vertices) | Q1(a) |
| Σ | "sum of" | add a list of terms | 📗.2, Q1(g) |
| T(n) | "T of n" | the running time of an algorithm on input size n | Q1(g) |
| O(g), Ω(g), Θ(g) | "big-Oh / big-Omega / big-Theta of g" | upper bound / lower bound / tight bound on growth | Q1(d) |
| c, n₀ | "c", "n-nought" | the constant and the starting size from which a bound holds | Q1(d) |
| a, b, f(n) | "a", "b", "f of n" | sub-problems per recursion, shrink factor, split/join cost | Q1(g) |
| n^(log_b a) | "n to the log base b of a" | total work at the bottom (leaf) level of a recursion | Q1(g) |
| ε | "epsilon" | some positive amount you can name; marks a real gap in size | Q1(g) |
| pᵢ, wᵢ, xᵢ | "p sub i", "w sub i", "x sub i" | profit, weight, fraction of item i | Q2(a) |
| ∞ | "infinity" | no route/value found yet — anything real beats it | Q3(b) |
| k | "k" | a count (number of duplicates, clique size, capacity bound…) | Q1(c) |
| lps[i] | "L-P-S of i" | longest proper prefix that is also a suffix, ending at position i | Q3(e) |
| e[i,j], w[i,j], m[i,j], s[i,j] | — | dynamic-programming table entries (cost, weight, minimum, split) | Q3(c)–Q3(d) |
| dist[v] | "dist of v" | best-known distance from the source to vertex v | Q3(b) |
| ∈ | "is a member of" | belongs to a set | 📗.2, Q2(a) |
| ∧, ∨, ¬ | "AND", "OR", "NOT" | Boolean connectives (true/false logic) | Q4(d) |
| P, NP, NP-complete, NP-hard | — | classes of problems by how hard they are to solve or check | Q4(b)–Q4(c) |
| χ(G) | "chi of G" | chromatic number — fewest colours needed to colour a graph | Q4(d) |

### 📗.8 If you get stuck

1. Unknown **word or symbol** → find it in 📗.7; if it is not there, it must be defined in the question block's 🧰 L0 table — that table is the block's list of assumptions.
2. Unknown **maths** (power, root, log, Σ, floor) → 📗.2. Unknown **bits** → 📗.3. Unknown **graph words** → 📗.5.
3. **Pseudo-code looks unreadable** → read the *Read it aloud* line just below it and the trace above it; if it still resists, skip the code — the prose carries the same information.
4. **Lost in the middle of a question** → its 🧰 L0 table lists what the question assumes; the 🧾 registry says where each was taught.
5. **Asking for help** (study group, mentor, forum): quote the block title (`Q3(a) — Kruskal & Prim`) and the exact line or table row that stops you — the section names (L0, L1, e-table …) are stable, so anyone can find it in seconds.

---

# Q1 — Foundations of Algorithms (20 marks)
*Assignment p. 3 · Book: Block 1, Units 1–4, pp. 2–85 · Progress: ⬜→✅ in this pass*

---

# Q1(a) — All primes in 2…10000 (2 marks)
*Assignment p. 3 · Book: Block 1 U1 (what an algorithm is / efficiency) and U3 (complexity of simple algorithms), pp. 2–28, 46–68*

## 🧰 L0. Prerequisite bridge — what this question silently assumes

| Term | Read it as | What it is & why it exists | Example |
|---|---|---|---|
| algorithm | — | a finite, ordered, unambiguous list of steps that turns input into output and always stops (📗.1) | a recipe with exact quantities |
| input size n | "size n" | the number that measures how big the problem is; complexity is expressed in it | n = 10000 (the range limit) |
| correct algorithm | — | for **every** legal input it gives the right output | no composite survives, no prime is missed |
| efficiency | — | how the work grows as n grows; measured with O(·) (📗.6) | the sieve is far faster than testing every number |
| prime number | — | a whole number > 1 whose only divisors are 1 and itself | 2, 3, 5, 7, 11, … |
| composite | — | a whole number > 1 that is **not** prime — it can be split as a × b with both factors > 1 | 9 = 3×3, 15 = 3×5 |
| divisor | — | a number that divides another exactly, leaving no remainder | 3 divides 9; 4 does not divide 9 |
| multiple | — | what you get by multiplying a number by 1, 2, 3, … | multiples of 3: 3, 6, 9, 12, … |
| array | — | a numbered shelf of boxes holding related values (📗.4) | isPrime[7] records “is 7 prime?” |

**Read aloud:** "Find every prime from 2 to 10000, then say how the work grows with the limit."

*If `for`, `←` or `A[i]` are unfamiliar, read 📗.1 first. In this algorithm `isPrime` is just a shelf of n yes/no boxes (one per number), and “cross out a multiple” means writing “no” in that number's box.*

## 🔁 L1. Sieve of Eratosthenes — strike out multiples, keep what survives

**Key fact:** if a number m ≤ n is composite, it has a divisor ≤ √n. So once every multiple of every prime ≤ √n is crossed out, whatever is left must be prime.

```
Algorithm Sieve(n)                      # all primes up to n; here n = 10000
    for i ← 2 to n:  isPrime[i] ← TRUE
    isPrime[1] ← FALSE
    for i ← 2 to floor(√n):             # only primes ≤ √n can mark new composites
        if isPrime[i] = TRUE:
            for j ← i*i to n step i:    # start at i*i, not 2i
                isPrime[j] ← FALSE
    return { k : 2 ≤ k ≤ n and isPrime[k] = TRUE }
```

**Read it aloud:** "Start with every number assumed prime. For each surviving number i up to √n, cross out i², i²+i, i²+2i, … . Everything still marked at the end is prime."

Why `i*i`? A composite marked first by i, say m = i·k with k < i, was already crossed out when the smaller factor k was processed — so i can begin at i². Why stop at √n? If i > √n then i² > n, so the inner loop would do nothing.

**Example for n = 30:** i = 2 crosses 4,6,8,…,30; i = 3 crosses 9,12,…,30 (6,12,18 were already crossed); i = 5 (< √30 ≈ 5.5) crosses 25,30. Survivors: 2,3,5,7,11,13,17,19,23,29.

![Sieve of Eratosthenes on 1..100](MCS-211_Assignment_Workbook.assets/fig_sieve.png)
*🖼️ Figure 1 — The same idea on 1…100: after removing multiples of 2, 3, 5, 7 only the 25 primes remain (97 is the largest below 100).*

## ⏱️ L2. Complexity — why O(n log log n)

- For each prime i ≤ √n the inner loop runs about n/i times, so the total work is n·(1/2 + 1/3 + 1/5 + 1/7 + …).
- The sum of 1/p over primes p ≤ n grows like **log log n** (standard number-theory result), giving **O(n log log n)** time.
- The boolean array needs **O(n)** extra space. For n = 10000 this is ~10,000 cells and well under 100,000 markings — instant on any machine.

## ⚠️ Before you move on — traps and self-check

**Traps**
1. Setting `isPrime[0]` or `isPrime[1]` to TRUE — 0 and 1 are not primes.
2. Crossing out 2 itself while marking multiples of 2 (start at 4).
3. Starting the inner loop at `2*i` — correct but slower.
4. Writing the complexity as O(n·√n) — that is trial division, not the sieve.

**Self-check**

| Question | Answer |
|---|---|
| Why is √n the loop limit? | Any composite ≤ n has a factor ≤ √n; larger i mark nothing new |
| What does the algorithm output for n = 10? | 2, 3, 5, 7 |
| Why is the sieve better than testing each number for divisibility? | O(n log log n) ≈ n operations vs O(n√n) ≈ n^1.5 |

## 🧪 Exam trail — primes in past MCS-211 TEE papers

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| — | — | — | No archived question on prime generation in the 4 sessions | — |
| Jun-2025 | 1(a) | 5 | Define algorithm; state four characteristics | ☆ related (algorithm basics) — queued |

**Pattern:** prime generation itself was never asked in 4 sessions; the framework (what an algorithm is) and complexity analysis are what the paper tests.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(a) [2 marks]**
> Design and develop an efficient algorithm to find all the prime numbers in the range 2 to 10000. Access the complexity of this algorithm?

*⚠️ The paper prints “Access” — the intended word is “Assess”. No figure in this question.*

**Algorithm (Sieve of Eratosthenes).** Because every composite m ≤ n has a divisor ≤ √n, it is enough to cross out multiples of the primes up to √n; every number left untouched is prime.

```
Algorithm Sieve(n)                      # n = 10000
    for i ← 2 to n:  isPrime[i] ← TRUE
    isPrime[1] ← FALSE
    for i ← 2 to floor(√n):
        if isPrime[i] = TRUE:
            for j ← i*i to n step i:    # cross out i², i²+i, i²+2i, …
                isPrime[j] ← FALSE
    return all k in 2..n with isPrime[k] = TRUE
```

**Step trace (small n = 30):** 2 removes 4, 6, 8, …, 30; 3 removes 9, 12, 15, 18, 21, 24, 27, 30; 5 removes 25, 30. Survivors: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29. Running the same code with n = 10000 gives the 1229 primes up to 10000.

**Complexity.** The outer loop runs √n times. The inner loop for prime i performs about n/i markings, so the total is

> (n/2 + n/3 + n/5 + n/7 + …) = n·(sum of 1/i over primes i ≤ n).

Since that sum grows as log log n, the work is **O(n log log n)**. Space is **O(n)** for the boolean array. For n = 10000 the algorithm finishes in well under a million operations — far better than testing each number separately, which would cost O(n√n).

**Hence, all primes in 2…10000 can be listed by the Sieve of Eratosthenes in O(n log log n) time using O(n) space.**

## 📝 TEE layer — coverage sweep

No past question on this topic was found, so there is nothing new to answer here. The related algorithm-definition question (Jun-2025 1(a)) is kept `⏳ blocked` until the “characteristics of an algorithm” lesson is added in a later pass.

---

# Q1(b) — Quadratic-time vs exponential-time algorithms (2 marks)
*Assignment p. 3 · Book: Block 1 U1 §1.4 “A survey of common running times”, pp. 2–28*

## 📈 L1. The two growth classes

| | Quadratic time | Exponential time |
|---|---|---|
| Order | O(n²), O(n³) — **polynomial** | O(2ⁿ), O(n!) — **non-polynomial** |
| What it means | doubling n makes the work 4× (or 8× for cubic) | doubling n **squares** the work (or worse) |
| Behaviour at n = 50 | 2,500 steps — trivial | 2⁵⁰ ≈ 1.1 × 10¹⁵ steps — years |
| Solvable in practice? | yes, up to large n | only for small n (≤ 40–50 typically) |
| Typical example | insertion/bubble sort (sorting n items); naive n×n matrix multiplication | brute-force TSP (n! tours); trying all 2ⁿ subsets of a set; Tower of Hanoi |

**Read aloud:** “Quadratic — work grows with the square of the input; exponential — work grows by a constant factor *per item added*, so the curve shoots up almost vertically.”

*New to powers and growth?* 📗.2 defines aⁿ and n!, and 📗.6 gives the n vs n² vs 2ⁿ step table. Read those two short boxes first — the question becomes obvious once the step counts are visible.

![Quadratic vs exponential growth](MCS-211_Assignment_Workbook.assets/fig_growth.png)
*🖼️ Figure 2 — On a log scale 2ⁿ is a straight, steep line: it overtakes n² at n = 4 and by n = 50 is astronomically larger.*

**Book anchor (B1 U1):** the unit uses the maximum independent set of a graph to show the 2ⁿ explosion — checking all 2ⁿ subsets costs O(n²·2ⁿ), and factorial-time matching costs O(n!).

## ⚠️ Traps
1. Calling O(n³) “exponential” — cubic is still polynomial (exponential means the **variable is in the exponent**).
2. Comparing only at small n: n² beats 2ⁿ until n = 4; asymptotic statements describe **large** n.
3. Assuming every exponential problem is impossible — some have special cases or approximation algorithms (Block 4 U3).

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(b) | 5 | Arrange growth rates O(n²), O(2ⁿ), O(n log n), O(2!), O(1), O(log n) in increasing order | ☆ answered in Q1(d) TEE layer |

**Pattern:** the paper tests **ordering/classification of growth rates**, not a definition of “quadratic vs exponential”.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(b) [2 marks]**
> Differentiate between Quadratic-time and Exponential-time algorithms. Give example of one problem each for these two running times.

*No figure in this question.*

**Quadratic-time algorithm.** Its running time is O(n²): doubling the input size multiplies the work by about 4. It remains practical for large inputs, and it belongs to the polynomial class P. *Example:* **Insertion sort** of n numbers — the worst case performs about n(n−1)/2 comparisons, i.e. O(n²). Naive multiplication of two n×n matrices is another (O(n³), cubic).

**Exponential-time algorithm.** Its running time is O(2ⁿ) or O(n!): the input size appears in the exponent, so adding one more item doubles or multiplies the work. Such algorithms become unusable very quickly and are the hallmark of intractable problems. *Example:* the **brute-force travelling salesman problem** — checking every possible tour of n cities takes (n−1)! steps; trying all subsets of a set (e.g. the maximum independent set) takes 2ⁿ subsets, each verified in polynomial time.

| Basis | Quadratic | Exponential |
|---|---|---|
| Class | polynomial, efficient | non-polynomial, intractable |
| Doubling n | work ×4 | work ×(2ⁿ) |
| Example | insertion sort | brute-force TSP / all-subsets search |

**Hence:** quadratic algorithms stay usable as inputs grow, while exponential algorithms are practical only for small n — the difference that separates tractable from intractable problems.

---

# Q1(c) — Search in a sorted array with duplicates (2 marks)
*Assignment p. 3 · Book: Block 1 U3 (linear search analysis) and U1 §1.7 (divide-and-conquer examples), pp. 2–28, 46–68*

## 🧰 L0. Prerequisite bridge — what this question assumes

| Term | Read it as | Plain meaning | Tiny example |
|---|---|---|---|
| sorted array | — | a numbered shelf whose values run in increasing (non-decreasing) order | [1, 3, 3, 5, 8] |
| index | — | the box number of an array element; this workbook counts from 1 (📗.4) | in [1, 3, 3, 5, 8], A[4] = 5 |
| duplicates | — | the same value stored in several boxes | the two 3s above |
| search window [lo, hi] | "lo to hi" | the boxes still worth looking at; everything outside is already ruled out | initially lo = 1, hi = 5 |
| ⌊(lo+hi)/2⌋ | "floor of lo plus hi, over 2" | add the two ends, halve, round **down** to a whole box number (📗.2) | ⌊(1+5)/2⌋ = 3 |

*The code below uses 1-based boxes, and `=` inside `if` means "is equal to" — the primer's 📗.1 has the full notation table.*

## 🔁 L1. Binary search in one picture

Binary search keeps a window [lo, hi] and compares the key with the middle element A[mid]: equal → found; key smaller → search the left half; key larger → the right half. Each comparison halves the window, so after k comparisons at most n/2ᵏ elements remain; the search stops when n/2ᵏ = 1, i.e. k = log₂n.

**Read aloud:** “Cut the sorted list in half, keep the half that can still contain the key, repeat.”

## 🔁 L2. Handling duplicates: find-one-then-expand

Binary search alone returns **one** index, but the question wants **all** indexes of the value. The standard design is:

1. Binary search for the key; if absent, report “not found”.
2. From the found index, walk **left** while A[i] = key, then walk **right** while A[j] = key. Every index visited is part of the answer.

![Binary search probe and duplicate scan](MCS-211_Assignment_Workbook.assets/fig_binsearch_dup.png)
*🖼️ Figure 3 — Mid-probe finds one 5 at index 6; expanding left and right reports indexes 3–7.*

```
Algorithm SearchAll(A, n, key)
    lo ← 1; hi ← n; found ← 0
    while lo ≤ hi:                     # classic binary search
        mid ← floor((lo + hi) / 2)
        if A[mid] = key:  found ← mid; break
        elif A[mid] < key: lo ← mid + 1
        else: hi ← mid − 1
    if found = 0: return empty list
    i ← found; while i ≥ 1 and A[i] = key: i ← i − 1        # scan left
    j ← found + 1; while j ≤ n and A[j] = key: j ← j + 1    # scan right
    return indexes i+1, i+2, …, j−1
```

## ⏱️ L3. Worst-case complexity

- Finding one occurrence: **O(log n)**.
- Reporting k occurrences: **O(k)** (the answer itself has k indexes).
- Worst case: the whole array is the key (k = n), so the scan is O(n) → total **O(log n + n) = O(n)**.

**Point of record:** any algorithm must output k indexes, so **no correct algorithm can beat O(k)**; when duplicates can fill the array the worst case is Θ(n).

## ⚠️ Traps
1. Saying the answer is O(log n) — that ignores the output cost.
2. Using a plain linear scan to find the first occurrence → O(n), losing the binary-search advantage.
3. Assuming the array is sorted only when it is not — the question guarantees sorted order.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(e) | 5 | Write binary search; evaluate best and worst case | ☆ same algorithm — queued |
| Jun-2026 | 2(b) | 8 | Write binary search; show best, worst and average case | ✅ answered below |

**Pattern:** binary search appears in **2 of 4** sessions; the paper asks for the algorithm plus its three-case analysis, slightly wider than this assignment part.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(c) [2 marks]**
> A sorted array of size n contains several duplicate values. Design an algorithm to search a value in the array. The algorithm should output all the indexes where the searched value exists. Explain the worst time complexity of this algorithm.

*No figure in this question.*

**Design.** Since the array is sorted, first locate **one** occurrence with binary search; then expand left and right to collect the rest.

```
Algorithm SearchAll(A, n, key)
    lo ← 1; hi ← n; found ← 0
    while lo ≤ hi:
        mid ← floor((lo + hi) / 2)
        if A[mid] = key:  found ← mid; break
        elif A[mid] < key: lo ← mid + 1
        else: hi ← mid − 1
    if found = 0: return “key not present”
    i ← found; while i ≥ 1 and A[i] = key: i ← i − 1
    j ← found + 1; while j ≤ n and A[j] = key: j ← j + 1
    return all indexes from i+1 to j−1
```

**Why this is correct.** Because the array is sorted, all copies of the key are contiguous. Binary search returns one copy, and the two scans move outward while the value remains equal — so exactly the copies are reported, and nothing else.

**Worst-case complexity.** The binary search costs at most ⌈log₂n⌉ + 1 comparisons, i.e. **O(log n)**. If there are k copies, the two scans cost O(k). Adding a constant to each scan for the boundary checks, the total is **O(log n + k)**. The worst case occurs when the array consists of the same value (or the key fills a long block): then k = n, so the complexity is **O(log n + n) = O(n)**.

**Hence: the algorithm reports all indexes in O(log n + k) time, which is O(n) in the worst case.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2026 | 2(b) | 8 | binary search algorithm, best/worst/average analysis | ✅ answered below |
| Dec-2024 | 1(e) | 5 | binary search, best/worst | 🔓 unlocked — queued (same algorithm as Jun-2026 2(b)) |

### ✍️ TEE answer — Jun-2026, Q2(b) [8 marks]

**📄 Question — Jun-2026 TEE, Q2(b) [8 marks]**
> Write the binary search algorithm. Show the best case, worst case and the average case of binary search.

**Algorithm.** The array A[1..n] is sorted in non-decreasing order.

```
Algorithm BinarySearch(A, n, key)
    lo ← 1; hi ← n
    while lo ≤ hi:
        mid ← floor((lo + hi) / 2)
        if A[mid] = key:  return mid        # found
        elif A[mid] < key: lo ← mid + 1     # go right
        else: hi ← mid − 1                  # go left
    return 0                                # not present
```

Each iteration halves the search window, so the key is located — or shown absent — after at most ⌈log₂(n+1)⌉ comparisons.

**Best case.** The key is exactly at the first middle position: **1 comparison**, T(n) = O(1).

**Worst case.** The key is not present (or is at the last surviving position): the window is halved until it is empty. T(n) = T(n/2) + c, whose solution is T(n) = O(log n).

**Average case.** On the assumption that each of the n positions is equally likely to be searched, the average number of comparisons is about log₂n − 1, i.e. **Θ(log n)**. Binary search therefore runs in O(log n) comparisons in both the average and worst case, and needs no extra storage.

**Hence: binary search completes in O(1) comparisons in the best case and O(log n) in the average and worst cases.**

---

# Q1(d) — Big-Θ and Big-Ω; asymptotic bounds (4 marks)
*Assignment p. 3 · Book: Block 1 U2 “Asymptotic Bounds”, pp. 29–45*

## 🧰 L1. Why asymptotic bounds exist

Two machines, two programmers, one algorithm — absolute timings differ. Asymptotic analysis ignores machine-dependent constants and describes **how the work grows with n**. Big-O gives an upper bound, Big-Ω a lower bound, Big-Θ a tight bound.

## 🧮 L2. The three notations (formal definitions)

| Notation | Read it as | Formal meaning | Intuition |
|---|---|---|---|
| **O(g(n))** | “f of n is big-Oh of g of n” | ∃ c > 0, n₀ > 0 : 0 ≤ f(n) ≤ c·g(n) for all n ≥ n₀ | f grows **no faster than** g — upper bound |
| **Ω(g(n))** | “big-Omega” | ∃ c > 0, n₀ > 0 : 0 ≤ c·g(n) ≤ f(n) for all n ≥ n₀ | f grows **no slower than** g — lower bound |
| **Θ(g(n))** | “big-Theta” | ∃ c₁, c₂ > 0, n₀ : c₁g(n) ≤ f(n) ≤ c₂g(n) for all n ≥ n₀ | f and g grow at the **same rate** — tight bound |

**Read the Θ-line aloud:** “There is a starting point n₀ beyond which c₁·g(n) stays below f(n) and f(n) stays below c₂·g(n) — the two curves are trapped between the same two sandwiches.”

The three notations are connected by one theorem (B1 U2): **f(n) = Θ(g(n)) if and only if f(n) = O(g(n)) and f(n) = Ω(g(n)).**

![O, Omega and Theta bounds](MCS-211_Assignment_Workbook.assets/fig_asym.png)
*🖼️ Figure 4 — Upper bound (O), lower bound (Ω) and the sandwich (Θ); n₀ is the point beyond which the inequality always holds.*

**Symbol card — ∃, c and n₀ (why the definition sounds strange).** ∃ reads “there exists” — the definition promises that *some* constants c and n₀ work; it never asks you to find the smallest ones. *c* is the constant multiplier that makes the bound true (constants are ignored, so any sufficiently large c is allowed); *n₀* is the threshold input size from which the bound must hold (small inputs may behave differently, so they are excluded). Tiny example: n + 10 ≤ 2n is false at n = 3 (13 > 6) but true for every n ≥ 10, so n + 10 = O(n) with c = 2 and n₀ = 10. “For all n ≥ n₀” simply means “forget every input smaller than n₀”.

## 🧭 L3. Need for, and shortcomings of, asymptotic bounds

**Why we need them.** (i) They compare algorithms **independent of hardware, language and compiler**; (ii) they reveal behaviour for **large inputs**, which is where efficiency matters; (iii) they simplify analysis — constants and lower-order terms are dropped; (iv) they classify problems (polynomial vs exponential) and decide feasibility.

**Shortcomings (B1 U2 §2.6.2 lists the first two explicitly).**

| Shortcoming | Illustration |
|---|---|
| Constants are ignored | Algorithm A (1000n²) beats algorithm B (5n⁴) only after n ≈ 14; below that B is faster, yet asymptotically both are judged by n² |
| Worst case vs average case | A may have a better worst case while B is faster on typical inputs — the bound alone cannot choose |
| Small inputs not described | O(1) vs O(log n) is irrelevant at n = 10 but decides at n = 10⁹ |
| No memory/extra-space view | Two O(n log n) sorts can differ hugely in space (merge vs heap sort) |
| Same class ≠ same speed | 2n and 1000n are both O(n) |
| Model assumptions | Bounds assume unit-cost operations; big-number arithmetic breaks that |

## ⚠️ Traps
1. Writing “Θ(n³)” when only an upper bound is proved — Θ needs **both** O and Ω.
2. Using Θ when f(n) = n² and g(n) = n³ — the rates differ, so no Θ exists.
3. Forgetting c > 0 and the “for all n ≥ n₀” part in the definition.
4. Dropping the domain: every asymptotic statement is about n → ∞.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(b) | 5 | Arrange growth rates in increasing order | ✅ answered below |
| Jun-2025 | 1(f) | 5 | Define big-Θ; show n² + 3log n = Θ(n²) | ✅ answered below |
| Jun-2026 | 1(c) | 5 | Differences between big-O and big-Ω with examples | ✅ answered below |

**Pattern:** asymptotic notation appears in **3 of 4** sessions, always **5 marks** — a short-slot topic. Definitions + one proof/ordering is the recurring shape.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(d) [4 marks]**
> Explain the Big Theta (Θ) and Big Omega (Ω) notations with the help of a diagram. What is the need of asymptotic bounds? Also, list the shortcomings of the asymptotic bounds. Find the Big O, Θ and Ω bounds for the following function:
> f(n) = 999n³ + 999999n + 100

*The diagram is drawn below (Figure 4); no figure is printed in the question.*

### (i) Big-Ω (lower bound) and Big-Θ (tight bound)

**Big-Ω.** f(n) = Ω(g(n)) if there are positive constants c and n₀ such that **0 ≤ c·g(n) ≤ f(n) for all n ≥ n₀**. It says f grows at least as fast as g: g(n) is a lower bound. *Example:* 3n² + 4n − 2 = Ω(n²) because 3n² + 4n − 2 ≥ 3n² for n ≥ 1 (c = 3).

**Big-Θ.** f(n) = Θ(g(n)) if there are positive constants c₁, c₂ and n₀ such that **0 ≤ c₁g(n) ≤ f(n) ≤ c₂g(n) for all n ≥ n₀**. The lower and upper curves trap f between them — the growth rates are the same. *Example:* 3n² + 4n − 2 = Θ(n²).

**Relation:** f(n) = Θ(g(n)) ⟺ f(n) = O(g(n)) and f(n) = Ω(g(n)).

*[Figure 4 shows the three panels: O from above, Ω from below, Θ as the sandwich.]*

### (ii) Need for asymptotic bounds
They compare algorithms **without depending on machine, language or compiler**; they describe the growth of work for **large inputs**; they ignore constants and lower-order terms, so analysis stays simple; and they separate tractable polynomial algorithms from intractable exponential ones.

### (iii) Shortcomings of asymptotic bounds
Asymptotic bounds **ignore constants** (1000n² is “better” than 5n⁴ only beyond n ≈ 14), describe **large n only**, do not distinguish algorithms in the **same class**, say nothing about **space**, and a better **worst case** need not mean a better **average case** on real inputs.

### (iv) Bounds for f(n) = 999n³ + 999999n + 100

| Bound | Working | Conclusion |
|---|---|---|
| Ω | 999n³ + 999999n + 100 ≥ 999n³ for n ≥ 1 (c = 999) | **f(n) = Ω(n³)** |
| O | 999n³ + 999999n + 100 ≤ (999 + 999999 + 100)n³ = 1001098n³ for n ≥ 1 (c = 1001098) | **f(n) = O(n³)** |
| Θ | 999n³ ≤ f(n) ≤ 1001098n³ for n ≥ 1 (c₁ = 999, c₂ = 1001098) | **f(n) = Θ(n³)** |

*(The unit proves this in general: a polynomial of degree m satisfies f(n) = O(n^m), Ω(n^m) and Θ(n^m).)*

**Hence: f(n) = O(n³), f(n) = Ω(n³) and f(n) = Θ(n³) — the polynomial is tightly cubic.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Dec-2024 | 1(b) | 5 | growth-rate ordering | ✅ answered below |
| Jun-2025 | 1(f) | 5 | Θ definition, proof | ✅ answered below |
| Jun-2026 | 1(c) | 5 | O vs Ω differences | ✅ answered below |

### ✍️ TEE answer — Jun-2026, Q1(c) [5 marks]

**📄 Question — Jun-2026 TEE, Q1(c) [5 marks]**
> What are the differences between Big ‘O’ and Big ‘Ω’ notations? Explain with examples.

| Basis | Big-O, O(g(n)) | Big-Ω, Ω(g(n)) |
|---|---|---|
| Type of bound | **upper** bound on f(n) | **lower** bound on f(n) |
| Formal condition | 0 ≤ f(n) ≤ c·g(n) for n ≥ n₀ | 0 ≤ c·g(n) ≤ f(n) for n ≥ n₀ |
| Meaning | f grows no faster than g | f grows no slower than g |
| Use | worst-case running time | guarantee that at least this much work is needed |
| Example | 3n² + 4n − 2 = O(n²) | 3n² + 4n − 2 = Ω(n²) |

**Examples.** (i) f(n) = 5n + 7. Since 5n + 7 ≤ 6n for n ≥ 7, f(n) = O(n); and 5n + 7 ≥ 5n for n ≥ 1, so f(n) = Ω(n). Both hold, hence also f(n) = Θ(n). (ii) f(n) = 2ⁿ: f(n) = O(2ⁿ) and f(n) = Ω(2ⁿ) trivially, but f(n) is **not** O(n²) and not Ω(n²) — the growth rates differ.

**Hence: Big-O caps the growth from above, Big-Ω pushes it from below; when both hold with the same g(n), the bound is Θ(g(n)).**

### ✍️ TEE answer — Jun-2025, Q1(f) [5 marks]

**📄 Question — Jun-2025 TEE, Q1(f) [5 marks]**
> Define the big theta notation. Show that n² + 3log n = Θ(n²).

**Definition.** f(n) = Θ(g(n)) if and only if there exist positive constants c₁, c₂ and n₀ such that **c₁·g(n) ≤ f(n) ≤ c₂·g(n) for all n ≥ n₀**. It means f and g have the same order of growth, and is equivalent to f = O(g) and f = Ω(g).

**Proof for f(n) = n² + 3log n, g(n) = n².**

*Upper bound (O).* For n ≥ 1, log n ≤ n² (in fact log n ≤ n ≤ n²), so
n² + 3log n ≤ n² + 3n² = 4n². Hence f(n) = O(n²) with c₂ = 4, n₀ = 1.

*Lower bound (Ω).* For n ≥ 1, n² + 3log n ≥ n², since 3log n ≥ 0. Hence f(n) = Ω(n²) with c₁ = 1, n₀ = 1.

*Conclusion.* n² ≤ n² + 3log n ≤ 4n² for all n ≥ 1, so c₁ = 1, c₂ = 4, n₀ = 1 satisfy the definition and **n² + 3log n = Θ(n²)**.

### ✍️ TEE answer — Dec-2024, Q1(b) [5 marks]

**📄 Question — Dec-2024 TEE, Q1(b) [5 marks]**
> Arrange the following growth rates in increasing order: O(n²), O(2ⁿ), O(n log n), O(2!), O(1), O(log n).

*(The paper prints “O(2 !)”; the only meaningful reading is O(2ⁿ) with the exponent lost in typesetting — otherwise “2!” is just the constant 2.)*

**Increasing order:**

> **O(1) < O(log n) < O(n log n) < O(n²) < O(2ⁿ) < O(n!)**

Reason: constants do not grow; log n grows slower than n log n; n log n grows slower than n² (the extra n beats log n); n² grows slower than 2ⁿ (at n = 4 they are both 16, and 2ⁿ pulls away afterwards); 2ⁿ grows slower than n! for n ≥ 4.

**Hence the arrangement is O(1), O(log n), O(n log n), O(n²), O(2ⁿ), O(n!).**



# Q1(e) — Right-to-left binary exponentiation; 5²³ (4 marks)
*Assignment p. 3 · Book: Block 1 U3 §3.4.3 “Exponent Evaluation”, pp. 46–68*

## 🧰 L0. Prerequisite bridge — what this question assumes

| Term | Read it as | Plain meaning | Tiny example |
|---|---|---|---|
| binary / bit | — | a number written with only 0s and 1s; each digit is one **bit** | 23 = 10111₂ |
| positional value | — | each bit is worth twice the bit on its right: 16, 8, 4, 2, 1 | 10111₂ = 16+0+4+2+1 = 23 |
| least significant bit (LSB) | — | the rightmost bit — the “1s” column; it is A[0] in the unit's numbering | 1011**1**₂ → LSB = 1 |
| most significant bit | — | the leftmost bit — the largest power of 2 | **1**0111₂ |
| aⁿ | “a to the n” | a multiplied by itself n times (📗.2) | 5³ = 125 |
| squaring | — | multiplying a number by itself: x ← x·x | 25² = 625 |

*If binary numbers are new, read 📗.3 first (half a page) — the whole method is “read n's 0/1 digits from right to left”.*

## 🔁 L1. The idea — square the base, read the exponent's bits

A naive aⁿ performs n − 1 multiplications. Binary exponentiation uses the binary form of n:

> aⁿ = product of a^(2^i) over all bits i of n that are 1.

**Read aloud:** “Repeatedly square the running power a, a², a⁴, a⁸, …; whenever the corresponding bit of n is 1, multiply it into the result.”

Example from the unit: 4¹¹, 11 = 1011₂, so 4¹¹ = 4⁸ · 4² · 4¹ — only 3 multiplications instead of 10, using the pre-computed squares 4, 16, 256, 65536.

**Symbol card — A[i]:** read “A sub i”; it is the i-th binary digit of n, with A[0] the **least significant** bit (why: right-to-left processing reads the bits in increasing significance); example: n = 23 = 10111₂ gives A = [1, 1, 1, 0, 1] (the bits read from the right — see 📗.3). *If you code:* `bin(23)[2:]` reversed.

## 🧮 L2. Right-to-left algorithm (pseudo-code of the unit)

```
Algorithm RightToLeft(a, n)
    A[0..s-1] ← binary digits of n, A[0] = least significant bit
    x ← a
    if A[0] = 1 then result ← a else result ← 1
    for i ← 1 to s − 1:
        x ← x * x                       # x = a^(2^i)
        if A[i] = 1 then result ← result * x
    return result                       # = a^n
```

**Read it aloud:** “Start with x = a and result = a or 1 according to the lowest bit. Square x at every step; if the current bit is 1, fold x into the result.”

## 🧪 L3. Demonstrated on 5²³

23 = (10111)₂, so s = 5 and A = [1, 1, 1, 0, 1].

| Step | i | x = a^(2^i) | A[i] | result |
|---|---|---|---|---|
| start | — | x = 5 | A[0] = 1 | result = 5 |
| 1 | 1 | 5 × 5 = 25 | 1 | 5 × 25 = 125 |
| 2 | 2 | 25² = 625 | 1 | 125 × 625 = 78,125 |
| 3 | 3 | 625² = 390,625 | 0 | unchanged = 78,125 |
| 4 | 4 | 390,625² = 152,587,890,625 | 1 | 78,125 × 152,587,890,625 = **11,920,928,955,078,125** |

**Check:** 5²³ = 5¹⁶ · 5⁴ · 5² · 5¹ = 152,587,890,625 × 625 × 25 × 5 = 11,920,928,955,078,125. ✔

**Multiplication count:** the loop always squares (4 times) and adds one multiplication for each 1-bit after the leading one (3 times) → 7 multiplications, against 22 for naive repeated multiplication.

## ⏱️ L4. Worst-case complexity

If n has s = ⌊log₂n⌋ + 1 bits, the loop runs s − 1 times and performs **s − 1 squarings plus at most s − 1 included multiplications**, so the number of multiplications is between s − 1 and 2(s − 1). Because s = O(log₂n), the complexity is

> **O(log n) multiplications** (time), with O(1) extra space.

## ⚠️ Traps
1. Reading bits most-significant-first in the right-to-left method (then the A[0] initialisation is wrong).
2. Squaring only when the bit is 1 — the square must be updated on **every** iteration.
3. Confusing the loop count with n instead of log₂n.
4. Forgetting that O(log n) counts **multiplications**; big-integer multiplication is not unit cost.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(d) | 5 | Compute x²⁸³ by **left-to-right** binary exponentiation | ✅ answered below |

**Pattern:** asked in **1 of 4** sessions, **5 marks**; the paper used the left-to-right variant, the assignment the right-to-left one — same family. The unit's own solved exercise (B1 U3, CYPP-3) computes a²⁸³ both ways, so this question is book-work.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(e) [4 marks]**
> Write the Right to Left binary exponentiation algorithm. Demonstrate the use of this algorithm to compute the value of 5²³. Show all steps of the computation. Explain the worst-case complexity of this algorithm.

*No figure in this question.*

**Algorithm.** Let n have the binary representation A[s−1]…A[1]A[0], where A[0] is the least significant bit and s is the number of bits.

```
Algorithm RightToLeft(a, n)
    A[0..s-1] ← binary digits of n with A[0] least significant
    x ← a
    if A[0] = 1 then result ← a else result ← 1
    for i ← 1 to s − 1:
        x ← x * x
        if A[i] = 1 then result ← result * x
    return result
```

**Computation of 5²³.** 23 = (10111)₂, so s = 5 and the bits from least to most significant are A[0]=1, A[1]=1, A[2]=1, A[3]=0, A[4]=1.

| Iteration | i | x = a^(2^i) | A[i] | result |
|---|---|---|---|---|
| Initialise | — | 5 | A[0] = 1 | 5 |
| 1 | 1 | 5² = 25 | 1 | 5 × 25 = 125 |
| 2 | 2 | 25² = 625 | 1 | 125 × 625 = 78,125 |
| 3 | 3 | 625² = 390,625 | 0 | 78,125 (no change) |
| 4 | 4 | 390,625² = 152,587,890,625 | 1 | 78,125 × 152,587,890,625 = 11,920,928,955,078,125 |

**Verification:** 5²³ = 5¹⁶ · 5⁴ · 5² · 5¹ = 152,587,890,625 × 625 × 25 × 5 = 11,920,928,955,078,125.

**Worst-case complexity.** The exponent n needs s = ⌊log₂n⌋ + 1 bits. The loop performs s − 1 squarings and at most one extra multiplication per set bit; therefore the total number of multiplications lies between s − 1 and 2(s − 1), which is **O(log n)**. Brute-force multiplication would need n − 1 multiplications, so exponentiation by squaring is exponentially faster in the exponent.

**Hence, 5²³ = 11,920,928,955,078,125, computed in O(log n) multiplications (7 multiplications for n = 23).**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Dec-2024 | 1(d) | 5 | left-to-right binary exponentiation | ✅ answered below |

### ✍️ TEE answer — Dec-2024, Q1(d) [5 marks]

**📄 Question — Dec-2024 TEE, Q1(d) [5 marks]**
> Compute x²⁸³ by using left-to-right binary exponentiation.

**Algorithm (left-to-right).** Start with the leading bit; for every following bit, square the result and, if the bit is 1, multiply by the base.

```
Algorithm LeftToRight(a, n)
    A[0..s-1] ← binary digits of n (A[0] most significant)
    result ← a
    for i ← 1 to s − 1:
        result ← result * result
        if A[i] = 1 then result ← result * a
    return result
```

**Computation for x²⁸³.** 283 = (100011011)₂, s = 9. Processing the bits after the leading 1:

| Iteration | i | Bit | result |
|---|---|---|---|
| start | 0 | 1 | x |
| 1 | 1 | 0 | x² |
| 2 | 2 | 0 | x⁴ |
| 3 | 3 | 0 | x⁸ |
| 4 | 4 | 1 | (x⁸)² · x = x¹⁷ |
| 5 | 5 | 1 | (x¹⁷)² · x = x³⁵ |
| 6 | 6 | 0 | (x³⁵)² = x⁷⁰ |
| 7 | 7 | 1 | (x⁷⁰)² · x = x¹⁴¹ |
| 8 | 8 | 1 | (x¹⁴¹)² · x = x²⁸³ |

**Result:** x²⁸³. The run uses 8 squarings and 4 additional multiplications = 12 multiplications instead of 282.

---

# Q1(f) — Insertion sort; best and worst case (3 marks)
*Assignment p. 3 · Book: Block 1 U1 §1.4 (running-time survey) and U3 §3.4.4 (internal sorts), pp. 2–28, 46–68*

## 🃏 L1. Insertion sort — the card-hand idea

Insertion sort keeps a sorted prefix A[1..j−1] and inserts A[j] into its correct place by shifting larger elements one position right.

```
Algorithm InsertionSort(A, n)
    for j ← 2 to n:
        key ← A[j]
        i ← j − 1
        while i > 0 and A[i] > key:
            A[i+1] ← A[i]        # shift right
            i ← i − 1
        A[i+1] ← key             # place key
    return A
```

**Read it aloud:** “Take the next card; slide the bigger cards one place right; drop the card into the gap.”

**Words this topic uses, in plain English:** *in place* = it rearranges the same shelf and needs almost no extra memory; *stable* = equal values keep their original relative order (important when records are sorted by one field after another); *adaptive* = it automatically does less work on nearly-sorted input — that is exactly the best case below; *shift vs swap* = moving an element one box right versus exchanging two elements (shifting writes less).

**Trace on A = [5, 2, 4]:** j = 2: key 2 shifts 5 → [2, 5, 4]; j = 3: key 4 shifts 5 → [2, 4, 5]. Sorted.

**Loop invariant (why it is correct):** at the start of iteration j, A[1..j−1] holds the original first j−1 values in sorted order. The while-loop shifts exactly the elements larger than key, and key is placed after them — so A[1..j] is sorted; after j = n the whole array is sorted.

## ⏱️ L2. Best, worst and average cases

| Case | Input | Work | Complexity |
|---|---|---|---|
| **Best** | already sorted — the `while` test fails at every j | ≈ n − 1 comparisons, 0 shifts | **Θ(n)** |
| **Worst** | reverse sorted — A[j] is smaller than every prefix element | (n−1) + (n−2) + … + 1 = n(n−1)/2 comparisons and shifts | **Θ(n²)** |
| Average | random order — half the prefix is larger on average | ≈ n²/4 operations | **Θ(n²)** |

Space is O(1) (in-place), and the algorithm is **stable** and **adaptive** — exactly the traits the unit uses it to illustrate. Insertion sort is the best choice for small or nearly-sorted arrays, and is used inside hybrid sorts (e.g. Timsort) below a cutoff size.

**Recurrence view:** worst case T(n) = T(n−1) + Θ(n) → Θ(n²); best case T(n) = T(n−1) + Θ(1) → Θ(n).

## ⚠️ Traps
1. Swapping instead of shifting — correct but with more writes.
2. Reporting O(n²) for the best case.
3. Using `≥` in the while condition (loses stability).
4. Applying the shifting loop beyond the sorted prefix (off-by-one gives wrong output).

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 2(b) | 10 | Bubble sort + number of comparisons | ⏳ blocked — needs bubble sort lesson |
| Dec-2024 | 3(a) | 10 | Merge sort + trace | ⏳ blocked — needs merge sort lesson |
| Jun-2025 | 3(a) | 10 | Merge sort + best/worst analysis | ⏳ blocked — needs merge sort lesson |
| Dec-2025 | 1(a) | 5 | Apply merge sort to an array | ⏳ blocked — needs merge sort lesson |
| Jun-2026 | 2(a) | 12 | Merge sort step by step | ⏳ blocked — needs merge sort lesson |

**Pattern:** no direct insertion-sort question in 4 sessions; the paper instead asks **bubble/merge sort** (sorting pair appears in **4 of 4** sessions). Those stay blocked until their lessons are added — the assignment asks only insertion sort.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(f) [3 marks]**
> Write and explain the Insertion sort algorithm. Discuss its best and worst-case time complexity.

*No figure in this question.*

**Algorithm.** Insertion sort builds the sorted array one element at a time. For j = 2 to n, the element A[j] is lifted into `key`; every element of the sorted prefix A[1..j−1] that is larger than key is shifted one position right; then key is inserted into the gap.

```
Algorithm InsertionSort(A, n)
    for j ← 2 to n:
        key ← A[j]
        i ← j − 1
        while i > 0 and A[i] > key:
            A[i+1] ← A[i]
            i ← i − 1
        A[i+1] ← key
    return A
```

**Explanation with example.** For A = [5, 2, 4]: j = 2 lifts 2, shifts 5 right, giving [2, 5, 4]; j = 3 lifts 4, shifts 5 right, giving [2, 4, 5]. At every stage A[1..j−1] is sorted, so after the last insertion the whole array is sorted. The algorithm is in-place (O(1) extra space), stable, and works well on nearly-sorted data.

**Best case.** If the array is already sorted, the condition A[i] > key is false immediately for every j: one comparison per element, no shifts. Total work ≈ n − 1 → **Θ(n)**.

**Worst case.** If the array is in reverse order, element j must be compared with, and shift, the whole prefix: 1 + 2 + … + (n−1) = n(n−1)/2 comparisons and shifts. Total work → **Θ(n²)**.

**Hence: best case Θ(n), worst case Θ(n²); the algorithm is efficient for small or nearly sorted arrays but too slow for large random inputs.**

---

# Q1(g) — Recurrence relations and the Master method (3 marks)
*Assignment p. 3 · Book: Block 1 U4 “Solving Recurrences”, pp. 69–85*

## 🧰 L0. Prerequisite bridge — notation the Master method needs

| Symbol | Read it as | What it is & why it exists | Example |
|---|---|---|---|
| T(n) | “T of n” | the running time of an algorithm on input size n | T(n) = 2T(n/2) + n |
| a | “a” | number of **sub-problems** the recursion creates | merge sort: a = 2 |
| b | “b” | factor by which the sub-problem size **shrinks** | merge sort: b = 2 |
| f(n) | “f of n” | cost of dividing + combining outside the recursion | merge sort: f(n) = n |
| n^(log_b a) | “n to the power log base b of a” | the **work at the bottom (leaf) level** of the recursion = number of leaves × work per leaf; equally, n raised to the number of levels | 2T(n/2)+n → n^(log₂2) = n; 8T(n/2)+n² → n³ |
| Σ | “sum of” | shorthand for adding a list of terms | Σ from i=0 to k of n = n(k+1) |

**Read the master-form aloud:** “The algorithm does a pieces of size n/b and pays f(n) for the split-and-join; the answer is decided by comparing n^(log_b a) with f(n).”

**Tiny example of the comparison (this is the whole method).** For T(n) = 2T(n/2) + n: a = 2, b = 2, so the leaf term is n^(log₂2) = n¹ = n, exactly equal to f(n) = n → **Case 2** → Θ(n log n). For T(n) = 8T(n/2) + n²: the leaf term is n^(log₂8) = n³, one power of n bigger than f(n) = n² → **Case 1** → Θ(n³). Comparing the **exponents of n** decides the case; the extra log n in Case 2 simply counts the levels of the recursion.

## 📚 L1. What a recurrence relation is, and where it is used

A **recurrence relation** defines a quantity by referring to smaller instances of itself, together with a base case that stops the recursion. For a recursive algorithm it captures the running time: the base case is the cost of the smallest input, the recursive case is *cost of splitting* + *cost of sub-solutions* + *cost of combining*.

**Worked base example — factorial:** T(n) = T(n−1) + c, T(1) = c ⟹ T(n) = c·n = Θ(n).

**Where they are used:** merge sort T(n) = 2T(n/2) + n; binary search T(n) = T(n/2) + c; quicksort T(n) = T(n−1) + n (worst); Strassen T(n) = 7T(n/2) + n²; Tower of Hanoi T(n) = 2T(n−1) + 1, T(1) = 1.

The unit lists three solution methods: **substitution**, **recursion tree**, and the **Master method** (“cookbook”).

## 🍳 L2. Master theorem and its three cases

For T(n) = a·T(n/b) + f(n), with a ≥ 1, b > 1, compare f(n) with the leaf cost n^(log_b a):

| Case | Condition | Solution | Who dominates |
|---|---|---|---|
| **1** | f(n) = O(n^(log_b a − ε)) for some ε > 0 | T(n) = Θ(n^(log_b a)) | leaves |
| **2** | f(n) = Θ(n^(log_b a)) | T(n) = Θ(n^(log_b a) · log n) | all levels equally |
| **3** | f(n) = Ω(n^(log_b a + ε)) and a·f(n/b) ≤ c·f(n) for some c < 1 | T(n) = Θ(f(n)) | root (split/join) |

**What ε means, in plain words.** f(n) = O(n^(log_b a − ε)) says “f is smaller than the leaf term by a genuine power of n”, not merely by a constant factor — e.g. n² is genuinely smaller than n³. ε is any positive amount you can name; it exists only to rule out near-ties. Case 3's “regularity condition” is a technical check that the root's cost really dominates every level below it; it holds for every polynomial f(n) in this course.

![Master theorem cases](MCS-211_Assignment_Workbook.assets/fig_master_cases.png)
*🖼️ Figure 5 — Case 1: leaves dominate; Case 2: every level contributes equally and a log factor appears; Case 3: the divide/combine work dominates.*

## 🧮 L3. The two assignment recurrences, fully solved

**(a) T(n) = 16T(n/4) + n².**
Here a = 16, b = 4, f(n) = n². Leaf cost = n^(log₄16) = n². Since f(n) = Θ(n²), **Case 2** applies:

> T(n) = Θ(n² · log n).

*Intuition:* each level of the recursion costs n² (16 sub-problems each of size n/4 → 16·(n/4)² = n²) and there are log₄n levels.

**(b) T(n) = 8T(n/2) + n².**
Here a = 8, b = 2, f(n) = n². Leaf cost = n^(log₂8) = n³. Since f(n) = n² = O(n^(3−ε)) with ε = 1, **Case 1** applies:

> T(n) = Θ(n³).

*Intuition:* the number of leaves grows as 2^(3·log₂n) = n³, and n³ outgrows the n² split/join cost.

## ⚠️ Traps
1. Swapping a and b when computing log_b a (a is the number of calls, b the shrink factor).
2. Using Case 2 whenever f(n) and n^(log_b a) look “similar” but differ by a polynomial factor — the comparison must be by n^ε.
3. Forgetting the extra **log n** factor in Case 2.
4. Applying the Master method when a < 1 or b ≤ 1 — not allowed.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 1(c) | 5 | Solve T(n) = T(n/2) + n, T(1) = 1 | ✅ answered below |
| Jun-2025 | 5(b) | 10 | Explain the master method; state and interpret all three cases | ✅ answered below |
| Jun-2026 | 1(b) | 5 | Solve T(n) = T(n/2) + 2 by the recurrence-tree method | ✅ answered below |

**Pattern:** recurrences appear in **2 of 4** sessions (3 questions) — both short (5 marks) and long (10 marks); the Master method itself is explicitly asked in one session. This is reliable exam material.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q1(g) [3 marks]**
> What is a recurrence relations? When are they used? Solve the following recurrence relations using the Master's method:
> a. T(n) = 16T(n/4) + n²  b. T(n) = 8T(n/2) + n²

*No figure in this question.*

**Recurrence relation.** A recurrence relation expresses a function T(n) in terms of its own value on smaller inputs, together with a base case that ends the recursion. For a recursive algorithm, the base case gives the cost of the smallest input; the recursive case gives (split cost) + (cost of the recursive calls) + (combine cost).

**When they are used.** Whenever an algorithm solves a problem by calling itself on smaller sub-problems — merge sort T(n) = 2T(n/2) + n, binary search T(n) = T(n/2) + 1, quicksort, matrix-chain multiplication, etc. The recurrence is then solved to obtain the order of growth of the running time.

**Master method.** For T(n) = a·T(n/b) + f(n) with a ≥ 1, b > 1, compare f(n) with n^(log_b a):

| Case | Condition | Solution |
|---|---|---|
| 1 | f(n) = O(n^(log_b a − ε)), ε > 0 | T(n) = Θ(n^(log_b a)) |
| 2 | f(n) = Θ(n^(log_b a)) | T(n) = Θ(n^(log_b a) log n) |
| 3 | f(n) = Ω(n^(log_b a + ε)) and a·f(n/b) ≤ c·f(n), c < 1 | T(n) = Θ(f(n)) |

**(a) T(n) = 16T(n/4) + n².**
a = 16, b = 4, f(n) = n². The leaf work is n^(log₄ 16) = n^(2) = n². Since f(n) = n² = Θ(n²), this is **Case 2**:

> **T(n) = Θ(n² log n).**

**(b) T(n) = 8T(n/2) + n².**
a = 8, b = 2, f(n) = n². The leaf work is n^(log₂ 8) = n³. Since f(n) = n² = O(n^(3−1)), this is **Case 1**:

> **T(n) = Θ(n³).**

**Hence (a) T(n) = Θ(n² log n) and (b) T(n) = Θ(n³).**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2025 | 1(c) | 5 | recursion tree / Master, T(n) = T(n/2) + n | ✅ answered below |
| Jun-2026 | 1(b) | 5 | recursion-tree method | ✅ answered below |
| Jun-2025 | 5(b) | 10 | Master method: three cases | ✅ answered below |

### ✍️ TEE answer — Jun-2025, Q1(c) [5 marks]

**📄 Question — Jun-2025 TEE, Q1(c) [5 marks]**
> Solve the following recurrence equation: T(n) = T(n/2) + n for n > 1; T(n) = 1 for n = 1.

**Recursion-tree method.** Level 0 contributes n. Level 1 contributes n/2. Level 2 contributes n/4, and so on. The levels end when the sub-problem size reaches 1, i.e. after log₂n levels.

Total = n + n/2 + n/4 + … + 1 = n(1 + 1/2 + 1/4 + …) ≈ 2n = Θ(n).

**Master method check.** a = 1, b = 2, f(n) = n. The leaf work is n^(log₂1) = n⁰ = 1. Since f(n) = n = Ω(n^(0+1)) (and the regularity condition (1)·f(n/2) = n/2 ≤ c·n holds for c = 1/2 < 1), this is **Case 3**: T(n) = Θ(n).

**Hence T(n) = Θ(n).**

### ✍️ TEE answer — Jun-2026, Q1(b) [5 marks]

**📄 Question — Jun-2026 TEE, Q1(b) [5 marks]**
> Solve the following recurrence relation using the Recurrence Tree Method: T(n) = 1 if n = 1; T(n) = T(n/2) + 2 if n > 1.

At every level the single sub-problem of size n/2^k has combine cost 2. The number of levels: the sub-problem size reaches 1 when n/2^k = 1, i.e. k = log₂n.

| Level k | Sub-problem cost | Number of calls |
|---|---|---|
| 0 | 2 | 1 |
| 1 | 2 | 1 |
| 2 | 2 | 1 |
| … | 2 | 1 |
| log₂n | 1 (base) | 1 |

Total = 2 + 2 + … (log₂n times) + 1 = 2·log₂n + 1 = Θ(log n).

**Master method check.** a = 1, b = 2, f(n) = 2 = Θ(1) = Θ(n^(log₂1)). **Case 2** gives T(n) = Θ(n⁰·log n) = Θ(log n).

**Hence T(n) = Θ(log n).**

### ✍️ TEE answer — Jun-2025, Q5(b) [10 marks]

**📄 Question — Jun-2025 TEE, Q5(b) [10 marks]**
> Explain the use of master method. Write and interpret all the three cases of the master method to solve recurrence relation problem.

**Use.** The Master method is a cookbook for recurrences that appear when an algorithm divides a problem of size n into a sub-problems of size n/b, solves them recursively, and spends f(n) time on the divide-and-combine work:

> T(n) = a·T(n/b) + f(n),  a ≥ 1, b > 1.

Instead of unrolling the recursion, it compares the **cost of the leaves**, n^(log_b a), with the **cost of the split/join work**, f(n); the larger one determines the answer.

**The three cases.**

**Case 1 — leaves dominate.** If f(n) = O(n^(log_b a − ε)) for some ε > 0, the split/join work is polynomially smaller than the leaf work, so the leaves decide the total:

> T(n) = Θ(n^(log_b a)).

*Interpretation:* the multiplication of sub-problems outruns the local work. Example: T(n) = 9T(n/3) + n → n^(log₃9) = n², f(n) = n = O(n^(2−1)) → T(n) = Θ(n²).

**Case 2 — balanced.** If f(n) = Θ(n^(log_b a)), every level contributes the same order of work; there are log_b n levels, hence an extra log factor:

> T(n) = Θ(n^(log_b a) · log n).

*Interpretation:* the work is spread evenly down the tree, and the number of levels shows up directly. Example: T(n) = 2T(n/2) + n → n^(log₂2) = n, f(n) = n → T(n) = Θ(n log n) — merge sort.

**Case 3 — root dominates.** If f(n) = Ω(n^(log_b a + ε)) for some ε > 0 **and** the regularity condition a·f(n/b) ≤ c·f(n) holds for some c < 1 (and all large n), the split/join work dominates:

> T(n) = Θ(f(n)).

*Interpretation:* the very first divide-and-combine step outweighs everything below it. Example: T(n) = 2T(n/2) + n² → n^(log₂2) = n, f(n) = n² = Ω(n^(1+1)), and 2·(n/2)² = n²/2 ≤ c·n² for c = 1/2 → T(n) = Θ(n²).

**Hence the Master method solves recurrences by one comparison — n^(log_b a) vs f(n) — and yields Θ(n^(log_b a)), Θ(n^(log_b a) log n) or Θ(f(n)) according to the winning side.**

---

# Q2(a) — Greedy Technique & Fractional Knapsack (4 marks)
*Assignment p. 3 · Book: Block 2, Unit 1, pp. 86–96*

*(If Q1/Block 1 is already studied, this is revision. These items are NOT re-taught later — their full lessons belong to Q1.)*

| Symbol | Read it as | What it is & why it exists | Example |
|---|---|---|---|
| Σ | "sum of" | shorthand for adding a list of values; saves writing every term | Σpᵢxᵢ = p₁x₁ + p₂x₂ + … + pₙxₙ |
| subscript i | "i-th" | labels which item is meant (item 1, item 2, …) | p₃ = profit of item 3 |
| ∈ | "is a member of" | says x must be one of the allowed choices | x ∈ S (x is one of the options in S) |
| ≤, ≥ | "at most / at least" | compares a value against a limit | Σwᵢxᵢ ≤ W (“total weight is at most W”) |
| O(·) | "big-oh of" | growth of running time as input grows; constants dropped, fastest-growing term kept | sorting n items takes O(n log n) |
| s.t. | "subject to" | introduces the conditions that must hold | max f(x) s.t. constraints |

**Read aloud:** Σᵢpᵢxᵢ → "add up, for every item i, its profit pᵢ times the fraction xᵢ taken." · O(n log n) → "for large n the work grows a little faster than n." · `s.t.` → "subject to" (the limits that must hold).

*(Full lessons: Q1(g) for Σ, Q1(d) for O, Q1(f) for sorting.)*

**Concept map — learn in this order:**
```
[Σ notation]   [O(n log n)]                ← L0 (from Block 1)
      └───────────┬───────────┘
                  ▼
   Optimisation problem:  max/min f(x), x ∈ S,  s.t. constraints     ← L1
                  ▼
   Greedy recipe: Select → feasible? → include/discard → repeat      ← L2
                  │
                  └─► Local optimum vs Global optimum                ← L3
                  ▼
   Fractional Knapsack: p/w → sort desc → fill (fraction last)       ← L4
                  ▼
   Answer: x = (1, 4/5, 1, 0, 1); weight 10 kg; profit 49            ← solution
```

## 🎯 L1. Optimisation problem

**Definition:** a problem in which the best (optimal) solution must be found among all possible solutions.

**Mathematical form:**

> **Maximise / Minimise f(x), subject to x ∈ S**
> with constraints: **aᵢ(x) ≥ 0, bⱼ(x) = 0, cₖ(x) ≤ 0**

| Symbol / term | Read it as | What it is & why it exists | In the A→B example |
|---|---|---|---|
| x | "x" | A candidate solution — one possible choice | one travel mode |
| S | "set S" | All choices the problem allows | {bike, car, train, plane} |
| f(x) | "f of x" | The score being optimised (cost, profit, time); called *cost function* even for profit. The *objective* is to maximise or minimise it | total cost of that mode |
| aᵢ, bⱼ, cₖ | "a sub i, …" | General constraint forms: ≥ 0, = 0, ≤ 0. Most problems use only one kind | time ≤ 12 h |
| feasible solution | "feasible" | Passes **all** constraints — like passing input validation | train, plane |
| optimal solution | "optimal" | The feasible solution with the best f(x) | train (minimum cost) |

**Read the formula aloud:** "Choose x from the allowed set S so that f(x) is as large (or small) as possible, while the constraints hold."

**Example:** A journey from A to B must be done at minimum cost within 12 hours. Minimum cost is the objective, time ≤ 12 hours is the constraint. Bike and car (slow) are infeasible; train and plane are feasible; the cheaper train is optimal.

**Engineering intuition:** objective = the metric you optimise; constraints = validation rules; feasible = passes validation; optimal = best among everything that passes.

## 🔁 L2. Greedy recipe

A greedy solution is built input by input, choosing what looks best at each stage:

1. **Select** the most promising element of the candidate set A using the selection criterion, and remove it from A.
2. **Check feasibility** — can it be added to the partial solution set S without violating a constraint?
3. **Include or discard** — feasible: add to S; infeasible: reject permanently.
4. **Repeat** until a complete (optimal) solution is obtained or A becomes empty.

Mnemonic: **S-F-I-R** (Select, Feasibility, Include, Repeat).

## ⛰️ L3. Local vs global optimum

| Local optimal solution | Global optimal solution |
|---|---|
| Best solution in a nearby region | Best among all feasible solutions |
| Many may exist | Exactly one exists |
| Need not be the overall best | Overall best (maximum/minimum) |

Mountain-range picture: every valley bottom is a local minimum; the lowest valley is the global minimum. Greedy commits to the best local choice, so with a wrong criterion it may stop at a local optimum; with the right criterion its *first* solution is the global optimum.

![Solution space with local optima and one global optimum](MCS-211_Assignment_Workbook.assets/fig_local_global.png)
*🖼️ Figure 6 — A non-convex solution space: several local optima, exactly one global optimum.*

## 🎒 L4. Fractional knapsack

**Definition:** fill a knapsack of capacity W with items that may be taken in fractions, so that total profit is maximum.

**Formulation:** maximise Σpᵢxᵢ subject to Σwᵢxᵢ ≤ W, 0 ≤ xᵢ ≤ 1 (xᵢ = fraction of item i taken).

**Recipe:**
1. Compute ratio **pᵢ/wᵢ** (profit per kg) for every item.
2. Sort items in **decreasing** ratio.
3. Take items **fully** while they fit; for the first item that does not fit, take only the fraction that fills the bag exactly.
4. Stop at capacity 0; record xᵢ and add up profits.

![Items sorted by profit per weight](MCS-211_Assignment_Workbook.assets/fig_ratio_order.png)
*🖼️ Figure 7 — Step 1: items sorted by pᵢ/wᵢ (assignment data).*

![Filling the 10 kg bag in ratio order](MCS-211_Assignment_Workbook.assets/fig_knapsack_fill.png)
*🖼️ Figure 8 — Step 2: the bag filled with the assignment data; only I2 is split (4/5).*

**Why pᵢ/wᵢ?** The book's counter-example (n = 3, W = 20; p = 25, 24, 15; w = 18, 15, 10):

| Greedy criterion | What it picks | Profit |
|---|---|---|
| Max profit first | O1 full + 2/15 of O2 | 28.2 |
| Min weight first | O3 full + 2/3 of O2 | 31.0 |
| **Max p/w first** | O2 full + 1/2 of O3 | **31.5 ← optimal** |

![Profit by greedy criterion](MCS-211_Assignment_Workbook.assets/fig_criteria_compare.png)
*🖼️ Figure 9 — Same instance, three greedy criteria: only p/w reaches the optimum.*

**Symbol card — xᵢ:** read "x sub i". The fraction of item i placed in the bag: 0 = skip it, 1 = take all, 0.8 = take 80%. *Purpose:* makes "take part of an item" expressible — this is exactly why greedy works here (0/1 knapsack allows only 0 or 1, and greedy fails there).

**Algorithm (cleaned from the unit; the unit's printed version has a typo — `weight = M` should read `weight = W`):**

```
Algorithm FractionalKnapsack(p[1..n], w[1..n], W)
    sort items so that p[i]/w[i] is decreasing
    X[1..n] ← 0; weight ← 0; profit ← 0
    for i ← 1 to n
        if weight + w[i] ≤ W
            X[i] ← 1                        # take item i fully
        else
            X[i] ← (W − weight) / w[i]      # take only the fraction that fits
        weight ← weight + w[i] · X[i]
        profit ← profit + p[i] · X[i]
        if weight = W then break            # bag full
    return X, profit
```

**Read it aloud:** "Go through items from the highest value-density down. If the next item fits, take all of it; otherwise take just the fraction that fills the bag; update weight and profit; stop when the bag is full."

## ⏱️ L5. Complexity

Sorting the ratios dominates: **O(n log n)**; the fill pass is O(n). Greedy works here because items are divisible — for 0/1 knapsack it is not guaranteed.

## ⚠️ Before you move on — traps and self-check

**Traps**
1. Applying 0/1 logic to the last item — in the fractional problem a part of it is allowed.
2. Inverting the ratio (wᵢ/pᵢ instead of pᵢ/wᵢ).
3. Forgetting to update the remaining capacity after each pick.
4. Mixing profit and weight while totalling.
5. Believing greedy always works — here only because items are divisible.

**Self-check**

| Question | Answer |
|---|---|
| Why is Item 3 picked before Item 2 though Item 2 has the highest profit? | Higher p/w: 18/3 = 6 > 20/5 = 4 |
| If W = 8, what is the maximum profit? | 18 + 10 + 5 + (2/5)×20 = 33 + 8 = 41 |
| Why can't greedy solve 0/1 knapsack? | Items are indivisible; a locally best pick can leave an unusable gap |
| Time complexity of greedy fractional knapsack? | O(n log n) — dominated by sorting the ratios |

## 🧪 Exam trail — fractional knapsack in past MCS-211 TEE papers

Source: `SEM1/Question Papers/MCS-211 .../*.md` (archived MCA_NEW papers; MCAOL pattern may differ, but topic frequency is the best available signal).

| Session | Q | Marks | What was asked | Data | Practice answer |
|---|---|---|---|---|---|
| Dec 2024 | 4(b) | 10 | Solve fractional knapsack using greedy | n=7, W=5; w=(2,3,5,7,1,4,1); p=(10,5,15,7,6,18,3) | **25 units** (unit prints 24 — see note) |
| Jun 2025 | 4(a) | 10 | Write the algorithm, then solve | n=5, W=5; w=(2,3,5,7,1); p=(10,5,15,7,6) | 22 units |
| Dec 2025 | 2(b) | 10 | Define as an optimisation problem; write greedy method; find complexity | — | O(n log n) |
| Jun 2026 | 3(a) | 10 | Find the optimal solution | n=5, W=15; p=(15,30,40,35,55); w=(5,9,3,7,2) | 140 units |

**Pattern:** asked in **4 of 4** archived sessions, always **10 marks** — i.e., a *medium-answer* topic for the 5×10 slot. Dec 2024 reused the book's Example 1 verbatim; Jun 2025 reused its first 5 items.

> **Unit typo alert:** for Example 1 the unit prints total profit **24**, but the arithmetic gives **25** (10 + 1×6 + (2/4)×18 = 10 + 6 + 9 = 25). Verified against page image (printed p. 11). Show every step; trust the arithmetic.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 3, Q2(a) [4 marks]**
> (a) How can an optimisation problem be represented mathematically. Explain with the help of an example. Explain the steps of designing a Greedy solution for an optimisation problem. Also explain the concept of local and global optimal solutions. Solve the following fractional Knapsack problem using greedy approach. Show all the steps.
>
> Suppose there is a knapsack of capacity 10 Kg and the following 5 items are to packed in it. The weight and profit of the items are as under:
> (p1, p2,…, p5) = (10, 20,18,15,5), (w1, w2,…, w5) = (2, 5, 3, 5, 1)

*No figure in this question — all data is in the text.*

### (i) Mathematical representation of an optimisation problem

An optimisation problem seeks the best (optimal) solution among all possible solutions. It is written as:

> **Maximise / Minimise f(x), subject to x ∈ S**
> with constraints: **aᵢ(x) ≥ 0, bⱼ(x) = 0, cₖ(x) ≤ 0**

- **x** — a candidate solution from the set **S** of all possible solutions
- **f(x)** — the cost function; its maximisation/minimisation is the objective
- **aᵢ, bⱼ, cₖ** — the constraints a valid solution must satisfy

A solution satisfying all constraints is a **feasible solution**; the best feasible solution is the **optimal solution**.

**Example:** A journey from A to B must be done at minimum cost within 12 hours. Minimum cost is the objective, time ≤ 12 hours is the constraint. Bike and car (slow) are infeasible; train and plane are feasible; the cheaper train is optimal.

### (ii) Steps of designing a greedy solution

A greedy solution is built input by input, choosing what looks best at each stage:

1. **Select** the most promising element of the candidate set A using the selection criterion, and remove it from A.
2. **Check feasibility** — can it be added to the partial solution set S without violating a constraint?
3. **Include or discard** — feasible: add to S; infeasible: reject permanently.
4. **Repeat** until a complete (optimal) solution is obtained or A becomes empty.

### (iii) Local and global optimal solutions

| Local optimal solution | Global optimal solution |
|---|---|
| Best solution in a nearby region | Best among all feasible solutions |
| Many may exist | Exactly one exists |
| Need not be the overall best | Overall best (maximum/minimum) |

Every feasible solution need not be locally optimal, and every local optimum need not be global. Greedy takes the best local choice, so with a wrong criterion it may stop at a local optimum; with the right criterion its first solution is the global optimum.

### (iv) Solution of the given fractional knapsack problem

**Given:** W = 10 kg; n = 5
(p₁, …, p₅) = (10, 20, 18, 15, 5); (w₁, …, w₅) = (2, 5, 3, 5, 1)

**Formulation:** Maximise Σpᵢxᵢ subject to Σwᵢxᵢ ≤ 10 and 0 ≤ xᵢ ≤ 1, where xᵢ is the fraction of item i taken.

**Criterion:** highest pᵢ/wᵢ first (maximum profit per kg) — optimal for divisible items.

**Step 1 — Ratios, in decreasing order:**

| Item | pᵢ | wᵢ | pᵢ/wᵢ | Priority |
|---|---|---|---|---|
| 1 | 10 | 2 | 5 | 2 |
| 2 | 20 | 5 | 4 | 4 |
| 3 | 18 | 3 | 6 | 1 |
| 4 | 15 | 5 | 3 | 5 |
| 5 | 5 | 1 | 5 | 3 |

Order: **Item 3 → 1 → 5 → 2 → 4** *(Items 1 and 5 tie at ratio 5; both fit fully, so their order does not matter.)*

**Step 2 — Fill the knapsack:**

| Step | Item | Capacity left | Decision | xᵢ | Weight | Profit |
|---|---|---|---|---|---|---|
| 1 | 3 | 10 | 3 ≤ 10 → take fully | 1 | 3 | 18 |
| 2 | 1 | 7 | 2 ≤ 7 → take fully | 1 | 2 | 10 |
| 3 | 5 | 5 | 1 ≤ 5 → take fully | 1 | 1 | 5 |
| 4 | 2 | 4 | 5 > 4 → take 4/5 | 4/5 | 4 | 16 |
| 5 | 4 | 0 | no capacity → discard | 0 | 0 | 0 |

**Step 3 — Result:**
- Solution set: (x₁, x₂, x₃, x₄, x₅) = (1, 4/5, 1, 0, 1)
- Total weight = 1(2) + (4/5)(5) + 1(3) + 0(5) + 1(1) = 2 + 4 + 3 + 0 + 1 = **10 kg = W** (fully used)
- Total profit = 1(10) + (4/5)(20) + 1(18) + 0(15) + 1(5) = 10 + 16 + 18 + 0 + 5 = **49 units**

**Hence, maximum profit = 49 units**, obtained by taking Items 3, 1, 5 fully and 4/5 of Item 2.

## 📝 TEE layer — past-paper bank & coverage sweep

> **Rule:** TEE answers are written only for **actual past TEE questions**, labelled by the paper's own coordinates and sized by that question's marks. Dedup never applies here — each exam answer is standalone.

**Sweep after Q2(a):** all four archived fractional-knapsack questions are now coverable and answered below.
*Every question is quoted in full before its answer; if a question had a figure, it would be extracted with the figure-toolkit.*

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Dec 2024 | 4(b) | 10 | L4 (solve), L5 | ✅ answered below |
| Jun 2025 | 4(a) | 10 | L4 (algorithm + solve), L5 | ✅ answered below |
| Dec 2025 | 2(b) | 10 | L1, L2, L4 (algorithm), L5 | ✅ answered below |
| Jun 2026 | 3(a) | 10 | L4 (solve), L5 | ✅ answered below |

### ✍️ TEE answer — Dec-2025, Q2(b) [10 marks]

**📄 Question — Dec-2025 TEE, Q2(b) [10 marks]**
> Define a fractional Knapsack problem as an optimization problem. Write a Greedy method to find an optimal solution to the problem. Find the complexity of the algorithm.

**1. Fractional knapsack as an optimisation problem**

A knapsack of capacity W and n items are given; item i has profit pᵢ and weight wᵢ. Items may be divided, so a fraction xᵢ ∈ [0, 1] of item i can be taken. The aim is to choose the fractions so that total profit is maximum while total weight stays within W:

> **Maximise Σᵢpᵢxᵢ subject to Σᵢwᵢxᵢ ≤ W, 0 ≤ xᵢ ≤ 1**

- Objective function: Σpᵢxᵢ (total profit)
- Constraints: total weight ≤ capacity W; each fraction between 0 and 1
- Any choice satisfying the constraints is a **feasible solution**; the feasible choice with the largest profit is the **optimal solution**.

**2. Greedy method**

Selection criterion: take the item with the highest profit per unit weight **pᵢ/wᵢ** first, because it earns the most profit per kilogram.

```
Algorithm FractionalKnapsack(p[1..n], w[1..n], W)
    sort items so that p[i]/w[i] is decreasing
    X[1..n] ← 0; weight ← 0; profit ← 0
    for i ← 1 to n
        if weight + w[i] ≤ W
            X[i] ← 1                        # take item i fully
        else
            X[i] ← (W − weight) / w[i]      # take the fraction that fits
        weight ← weight + w[i] · X[i]
        profit ← profit + p[i] · X[i]
        if weight = W then break            # bag full
    return X, profit
```

The algorithm sorts once, then fills the bag in a single pass; only the last item can be split. The criterion is optimal for the fractional case: replacing part of a lower-ratio item by the same weight of a higher-ratio item can never reduce profit, and divisibility always allows that replacement.

**3. Complexity**

Sorting the ratios takes O(n log n); the fill loop runs at most n times (O(n)). Hence total time = **O(n log n)**, dominated by sorting.

### ✍️ TEE answer — Dec-2024, Q4(b) [10 marks]

**📄 Question — Dec-2024 TEE, Q4(b) [10 marks]**
> Solve the following fractional Knapsack problem using Greedy algorithm: Number of objects = 7; Capacity of Knapsack = 5; Weight of objects, Wi = (2, 3, 5, 7, 1, 4, 1); Profit of objects Pi = (10, 5, 15, 7, 6, 18, 3).

**Given:** n = 7, W = 5 kg; w = (2, 3, 5, 7, 1, 4, 1); p = (10, 5, 15, 7, 6, 18, 3).
**Criterion:** decreasing pᵢ/wᵢ.

| Item | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| wᵢ | 2 | 3 | 5 | 7 | 1 | 4 | 1 |
| pᵢ | 10 | 5 | 15 | 7 | 6 | 18 | 3 |
| pᵢ/wᵢ | 5 | 1.67 | 3 | 1 | **6** | 4.5 | 3 |

Order: Item 5 → 1 → 6 → (3, 7) → 2 → 4.

| Step | Item | Capacity left | Action | xᵢ | Weight | Profit |
|---|---|---|---|---|---|---|
| 1 | 5 | 5 | 1 ≤ 5: take fully | 1 | 1 | 6 |
| 2 | 1 | 4 | 2 ≤ 4: take fully | 1 | 2 | 10 |
| 3 | 6 | 2 | 4 > 2: take 2/4 = 1/2 | 1/2 | 2 | 9 |

Bag full after Step 3; items 3, 7, 2, 4 are not taken.

**Result:** x = (1, 0, 0, 0, 1, 1/2, 0)
- Total weight = 1×1 + 1×2 + (1/2)×4 = **5 kg = W**
- Total profit = 1×6 + 1×10 + (1/2)×18 = 6 + 10 + 9 = **25 units**

⚠️ The unit's Example 1 prints **24** for this same instance; the arithmetic gives **25**. Show all steps and trust the arithmetic.

### ✍️ TEE answer — Jun-2025, Q4(a) [10 marks]

**📄 Question — Jun-2025 TEE, Q4(a) [10 marks]**
> Write an algorithm for solving fractional Knapsack problem. Using this algorithm, solve the following fractional Knapsack problem:
> Capacity of Knapsack: 5 kg; Number of items: 5

| Object | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| Weight (kg) | 2 | 3 | 5 | 7 | 1 |
| Profit | 10 | 5 | 15 | 7 | 6 |

**Algorithm** (standalone — same as above):

```
Algorithm FractionalKnapsack(p[1..n], w[1..n], W)
    sort items so that p[i]/w[i] is decreasing
    X[1..n] ← 0; weight ← 0; profit ← 0
    for i ← 1 to n
        if weight + w[i] ≤ W
            X[i] ← 1                        # take item i fully
        else
            X[i] ← (W − weight) / w[i]      # take the fraction that fits
        weight ← weight + w[i] · X[i]
        profit ← profit + p[i] · X[i]
        if weight = W then break            # bag full
    return X, profit
```

**Solve:** ratios pᵢ/wᵢ: I1 5, I2 1.67, I3 3, I4 1, I5 6 → order I5 → I1 → I3 → I2 → I4.

| Step | Item | Capacity left | Action | xᵢ | Weight | Profit |
|---|---|---|---|---|---|---|
| 1 | 5 | 5 | 1 ≤ 5: take fully | 1 | 1 | 6 |
| 2 | 1 | 4 | 2 ≤ 4: take fully | 1 | 2 | 10 |
| 3 | 3 | 2 | 5 > 2: take 2/5 | 2/5 | 2 | 6 |

**Result:** x = (1, 0, 2/5, 0, 1); weight = 5 kg = W; **profit = 6 + 10 + 6 = 22 units.**

### ✍️ TEE answer — Jun-2026, Q3(a) [10 marks]

**📄 Question — Jun-2026 TEE, Q3(a) [10 marks]**
> Find the optimal solution to the following instance of a fractional knapsack problem: Number of objects = 5, Capacity of a knapsack W = 15.
> (P1, P2, P3, P4, P5) = (15, 30, 40, 35, 55); (W1, W2, W3, W4, W5) = (5, 9, 3, 7, 2).

**Criterion:** decreasing pᵢ/wᵢ.

| Item | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| pᵢ/wᵢ | 3 | 3.33 | 13.33 | 5 | **27.5** |

Order: Item 5 → 3 → 4 → 2 → 1.

| Step | Item | Capacity left | Action | xᵢ | Weight | Profit |
|---|---|---|---|---|---|---|
| 1 | 5 | 15 | 2 ≤ 15: take fully | 1 | 2 | 55 |
| 2 | 3 | 13 | 3 ≤ 13: take fully | 1 | 3 | 40 |
| 3 | 4 | 10 | 7 ≤ 10: take fully | 1 | 7 | 35 |
| 4 | 2 | 3 | 9 > 3: take 3/9 = 1/3 | 1/3 | 3 | 10 |

**Result:** x = (0, 1/3, 1, 1, 1); weight = 15 kg = W; **profit = 55 + 40 + 35 + 10 = 140 units.**

## ✅ Verification (Q2(a) block)

| Standard | Check | Result |
|---|---|---|
| Source-grounded | Concepts/formulas from Block 2 U1, pp. 86–96. Exam trail from the 4 archived MCS-211 MDs | ✅ |
| Paraphrased (IGNOU rule) | Own wording; book example used as evidence data | ✅ |
| Structure | L0 → L1–L5 → traps → exam trail → full answer → TEE → verification | ✅ |
| Assignment answer | 497 prose words + 2 tables → ~36–38 min handwritten | ✅ |
| Symbol standard | Every symbol has plain words + read-aloud + purpose + example; code analogies only as labelled asides | ✅ |
| Zero-background | L0/🔰 tables define every assumed term; no code block is the only explanation; primer links present | ✅ |
| Question-first | Assignment + all TEE answers embed the verbatim question text; question figures extracted when present | ✅ |
| Figures | 4 PNGs generated in `MCS-211_Assignment_Workbook.assets/`, referenced from L3/L4 with captions | ✅ |
| TEE layer | Real past questions only; all 4 answered standalone at paper coordinates/marks | ✅ |
| Nil duplication | Registry lists every concept with its single teaching location | ✅ |
| Numerics | Script-checked: order 3→1→5→2→4, x = (1, .8, 1, 0, 1), weight 10, profit 49. Trail answers re-checked (25, 22, 140) | ✅ |

---

# Q2(b) — Huffman codes (4 marks)
*Assignment p. 4 · Book: Block 2 U1 §1.7 “Huffman Codes”, pp. 86–110*

## 🧰 L0. Prerequisite bridge — what this question assumes

| Term | Read it as | What it is & why it exists | Example |
|---|---|---|---|
| fixed-length code | — | every symbol gets the same number of bits (ASCII = 7) | 6 letters × 3 bits = 300 bits for 100 characters |
| variable-length code | — | frequent symbols get short codes, rare ones long codes → smaller total | Huffman |
| prefix code | — | no codeword is the beginning of another; makes decoding unambiguous | {01, 100, 101} is prefix-free; {01, 010, 10} is not |
| code tree | — | leaves = symbols, path from root = code (left edge = 0, right = 1) | Figure 10 |

**Greedy recipe link (taught once, in Q2(a)):** Huffman is a greedy algorithm — it repeatedly makes the locally best merge (two smallest frequencies), and this turns out to be globally optimal for prefix codes.

## 🔁 L1. Huffman's algorithm (book §1.7)

1. Put every symbol in a min-priority queue keyed by frequency — a to-do list that always hands back the smallest item first (like a hospital triage list; *if you code*, a min-heap implements it in O(log n) per operation).
2. Extract the two smallest nodes x, y.
3. Replace them by a new node z = x + y (x left child, y right child).
4. Repeat until one node (the root) remains.
5. Read each code by walking root → leaf, writing 0 for a left edge and 1 for a right edge.

**Read it aloud:** “Merge the two least frequent symbols into one parent; repeat until everything is one tree; read the codes off the tree.”

**Why greedy is optimal here:** in any prefix tree the two least frequent symbols can always be placed as the deepest siblings without making the total worse — this proof style is called an *exchange argument* (if a better tree put them higher, swapping them down never increases the total). In plain words: **rare characters should get the longest codes, and the two rarest can always share the deepest branch**, so merging them first never hurts.

## 🌳 L2. Worked on the assignment data

Frequencies: a:25, b:3, c:2, d:6, e:40, f:14, g:10 (total 100).

| Step | Two smallest merged | New node | Queue afterwards (by frequency) |
|---|---|---|---|
| 1 | c:2, b:3 | 5 | 5, d:6, g:10, f:14, a:25, e:40 |
| 2 | 5, d:6 | 11 | g:10, 11, f:14, a:25, e:40 |
| 3 | g:10, 11 | 21 | f:14, 21, a:25, e:40 |
| 4 | f:14, 21 | 35 | a:25, 35, e:40 |
| 5 | a:25, 35 | 60 | e:40, 60 |
| 6 | e:40, 60 | **100** (root) | — |

![Huffman tree for the assignment data](MCS-211_Assignment_Workbook.assets/fig_huffman.png)
*🖼️ Figure 10 — The Huffman tree; left edges are 0, right edges 1, so each leaf's code is the path from the root.*

| Symbol | e | a | f | g | d | c | b |
|---|---|---|---|---|---|---|---|
| Frequency | 40 | 25 | 14 | 10 | 6 | 2 | 3 |
| Code | 0 | 10 | 110 | 1110 | 11110 | 111110 | 111111 |
| Bits × freq | 40 | 50 | 42 | 40 | 30 | 12 | 18 |

**Total bits = 40 + 50 + 42 + 40 + 30 + 12 + 18 = 232** → average 2.32 bits/character (a fixed 3-bit code would need 300 bits).

**Decoding a coded sequence.** Read bits and walk the tree until a leaf is reached; then restart at the root. For example 110|10|111110|0 → f, a, c, e = “face”. Because no codeword is a prefix of another, this walk is never ambiguous, and no separators are needed.

## ⏱️ L3. Complexity

With a binary min-heap: n − 1 merges, each extract/insert O(log n) → **O(n log n)** time and O(n) space. (Book's simple array version: O(n²) to find the two minima each time.)

## ⚠️ Traps
1. Giving a short code to a high-frequency symbol but placing it deep in the tree — the code and the tree must agree.
2. Adding a merged node back without re-sorting/re-heapifying.
3. Using a code that is a prefix of another (breaks decoding).
4. Forgetting the code tree's edge convention (left = 0, right = 1) when reading codes.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(g) | 5 | Construct Huffman tree for a:65, b:3, c:4, d:10, e:3, f:6 | 🔓 unlocked — queued |
| Dec-2025 | 1(c) | 5 | Build Huffman tree for a:70, b:2, c:5, d:13, e:3, f:7 | 🔓 unlocked — queued (this is the book's own worked example!) |
| Jun-2026 | 5(b) | 10 | Optimal Huffman tree + code, A:20 B:25 C:10 D:8 E:7 F:12 G:10 | ✅ answered below |

**Pattern:** Huffman appears in **3 of 4** sessions (5, 5 and 10 marks) — very high-frequency, and always as *construct the tree/codes*. The Dec-2025 instance is exactly the book's example (Greedy Technique §1.7).

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q2(b) [4 marks]**
> Assuming that data to be transmitted consists of only characters ‘a’ to ‘g’, design the Huffman codes for the following frequencies of character data. Show all the steps of building a Huffman tree. Also, show how a coded sequence using Huffman code can be decoded.
> a:25, b:3, c:2, d:6, e:40, f:14, g:10

*No figure printed in the question; the tree is drawn in Figure 10.*

**Idea.** Assign short binary codewords to frequent characters and long ones to rare characters, with the prefix-free property (no codeword is the start of another) so that decoding is unambiguous. Huffman's greedy algorithm builds the optimal such prefix code.

**Step 1 — Build the tree.** Repeatedly merge the two smallest frequencies; label the left edge 0 and the right edge 1.

| Step | Merge | New node | Queue after the merge |
|---|---|---|---|
| 1 | c:2 + b:3 | 5 | 5, d:6, g:10, f:14, a:25, e:40 |
| 2 | 5 + d:6 | 11 | g:10, 11, f:14, a:25, e:40 |
| 3 | g:10 + 11 | 21 | f:14, 21, a:25, e:40 |
| 4 | f:14 + 21 | 35 | a:25, 35, e:40 |
| 5 | a:25 + 35 | 60 | e:40, 60 |
| 6 | e:40 + 60 | 100 | root reached |

**Step 2 — Read the codes** (root → leaf; left edge 0, right edge 1):

| Character | e | a | f | g | d | c | b |
|---|---|---|---|---|---|---|---|
| Frequency | 40 | 25 | 14 | 10 | 6 | 2 | 3 |
| Huffman code | 0 | 10 | 110 | 1110 | 11110 | 111110 | 111111 |
| Contribution (bits × freq) | 40 | 50 | 42 | 40 | 30 | 12 | 18 |

**Average length** = 232/100 = 2.32 bits per character, against 3 bits for a fixed-length code of 7 symbols.

**Step 3 — Decoding.** Walk the tree bit by bit: follow 0 left and 1 right; when a leaf is reached, output that character and restart from the root. Example: the coded sequence **110|10|111110|0** decodes as f (110), a (10), c (111110), e (0) — “face”. Since the code is prefix-free, the decoder never needs a separator and never has a choice.

**Hence the Huffman codes are e:0, a:10, f:110, g:1110, d:11110, c:111110, b:111111, giving an average of 2.32 bits/character.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2026 | 5(b) | 10 | build tree, assign codes, read frequencies | ✅ answered below |
| Dec-2024 | 1(g) | 5 | build tree | 🔓 unlocked — queued |
| Dec-2025 | 1(c) | 5 | build tree (book example) | 🔓 unlocked — queued |

### ✍️ TEE answer — Jun-2026, Q5(b) [10 marks]

**📄 Question — Jun-2026 TEE, Q5(b) [10 marks]**
> Construct an optimal Huffman tree and Huffman code for the following set of frequencies of characters: A : 20, B : 25, C : 10, D : 8, E : 7, F : 12, G : 10. Show all the intermediate steps.

**Algorithm.** Insert all characters into a min-priority queue by frequency; repeatedly extract the two smallest, merge them into a parent whose frequency is their sum, and insert the parent; stop when one node remains. Label left edges 0, right edges 1.

**Merge sequence.**

| Step | Extract | Merge | Insert | Queue after |
|---|---|---|---|---|
| 1 | E:7, D:8 | E + D = 15 | 15 | C:10, G:10, F:12, 15, A:20, B:25 |
| 2 | C:10, G:10 | C + G = 20 | 20 | F:12, 15, 20, A:20, B:25 |
| 3 | F:12, 15 | F + 15 = 27 | 27 | 20, A:20, B:25, 27 |
| 4 | 20, A:20 | 20 + 20 = 40 | 40 | B:25, 27, 40 |
| 5 | B:25, 27 | B + 27 = 52 | 52 | 40, 52 |
| 6 | 40, 52 | 40 + 52 = 92 | 92 | root |

**Tree and codes** (left = 0, right = 1):

```
                    92
                  /    \
                0        1
             40            52
            /  \          /  \
           0    1        0    1
         20    A:20     B:25   27
        /  \                  /  \
       0    1                0    1
     C:10  G:10            F:12   15
                                 /  \
                                0    1
                              E:7   D:8
```

| Character | A | B | C | D | E | F | G |
|---|---|---|---|---|---|---|---|
| Frequency | 20 | 25 | 10 | 8 | 7 | 12 | 10 |
| Code | 01 | 10 | 000 | 1111 | 1110 | 110 | 001 |
| Bits × freq | 40 | 50 | 30 | 32 | 28 | 36 | 30 |

**Verification:** the weighted path length (sum of *frequency × code length*) = 40 + 50 + 30 + 32 + 28 + 36 + 30 = **246 bits** for 92 characters, i.e. 2.67 bits/character, against 3 bits for a fixed-length 7-symbol code. Every code is prefix-free (e.g. 01 is not a prefix of 001 or 10).

**Hence the optimal Huffman codes are A:01, B:10, C:000, D:1111, E:1110, F:110, G:001, with an average length of 2.67 bits per character.**

---

# Q2(c) — Quicksort PARTITION and its worst case (4 marks)
*Assignment p. 4 · Book: Block 2 U2 §2.5.2 “Quick Sort”, pp. 111–147*

## 🧰 L1. Divide and conquer — the technique in one paragraph

A divide-and-conquer algorithm (i) **divides** the input into smaller sub-problems, (ii) **conquers** them recursively, and (iii) **combines** the results. Its cost obeys a recurrence T(n) = a·T(n/b) + f(n), which is exactly what the Master method solves — so Q1(g) and this question are two views of the same tool.

## 🔁 L2. Quicksort and its PARTITION (last-element pivot)

Quicksort picks a pivot (here the last element A[r]), partitions the array so that everything ≤ pivot is on the left and everything > pivot on the right, then recurses on the two sides.

**What the words mean (this is where most beginners stop).** *Pivot* = the value everything is compared against — here the last element. *Partition* = split the shelf into “≤ pivot” on the left and “> pivot” on the right. *Recurses* = repeats the same procedure on each side; each repetition is a smaller copy of the same job. Sides of size 0 or 1 are already sorted, and that is the **base case** that stops the recursion. *In place* = it rearranges the same shelf (📗.4).

```
Algorithm Partition(A, p, r)          # pivot = A[r]
    x ← A[r];  i ← p − 1
    for j ← p to r − 1:
        if A[j] ≤ x:
            i ← i + 1
            swap A[i] with A[j]
    swap A[i+1] with A[r]             # pivot to its final place
    return i + 1                      # q: pivot's index

Algorithm QuickSort(A, p, r)
    if p < r:
        q ← Partition(A, p, r)
        QuickSort(A, p, q − 1)
        QuickSort(A, q + 1, r)
```

**Read it aloud:** “Carry a boundary i just before the region of small elements. Scan j; whenever A[j] ≤ pivot, grow the small region and swap A[j] into it. Finally drop the pivot between the two regions.”

PARTITION is correct because after the loop A[p..i] ≤ pivot < A[i+1..r−1]; placing the pivot at i+1 puts it in its final sorted position. Each pass is a single left-to-right scan, **Θ(n)** time, and works in place (O(1) extra space).

**Trace one PARTITION call** — A = [3, 1, 4, 2], pivot x = A[4] = 2, p = 1, r = 4. Remember: i marks the end of the “small” region and starts at p − 1 = 0.

| j | A[j] | A[j] ≤ 2? | i after the round | Array after the round |
|---|---|---|---|---|
| 1 | 3 | no | 0 | [3, 1, 4, 2] — nothing moves |
| 2 | 1 | yes → i grows to 1, swap A[1]↔A[2] | 1 | [1, 3, 4, 2] |
| 3 | 4 | no | 1 | [1, 3, 4, 2] |
| — | — | final swap A[i+1]↔A[r] = A[2]↔A[4] | — | **[1, 2, 4, 3]** — pivot 2 is now in box 2 |

The pivot's final box is 2, so the left side is [1] (already sorted) and the right side is [4, 3] — each side is then partitioned the same way. Doing this by hand on small rows like this one is the best way to “feel” the algorithm.

## 🧪 L3. Demonstration on the sorted input [1, 5, 8, 11, 16, 19, 29, 38]

Call 1: pivot = 38. Every A[j] ≤ 38, so i moves with j and no swap changes anything; the final swap puts 38 at index 8. Partition returns q = 8 → right side empty, left side = the other 7 elements.

Call 2: pivot = 29, same story → q = 7.

| Call | Sub-array | Pivot | Pivot's final index | Elements on the left |
|---|---|---|---|---|
| 1 | 1…8 | 38 | 8 | 7 |
| 2 | 1…7 | 29 | 7 | 6 |
| 3 | 1…6 | 19 | 6 | 5 |
| 4 | 1…5 | 16 | 5 | 4 |
| 5 | 1…4 | 11 | 4 | 3 |
| 6 | 1…3 | 8 | 3 | 2 |
| 7 | 1…2 | 5 | 2 | 1 |

![Partition on sorted input](MCS-211_Assignment_Workbook.assets/fig_qsort_partition.png)
*🖼️ Figure 11 — On sorted input every scan finds all elements smaller than the pivot: the split is maximally unbalanced, one element falls into place per pass.*

Total comparisons = 7 + 6 + 5 + 4 + 3 + 2 + 1 = 28, and the array never needs a real swap — the *number of partition passes* is the problem, not the work per pass.

## ⏱️ L4. Complexity — why the sorted input is the worst case

| Case | Split at each level | Recurrence | Complexity |
|---|---|---|---|
| Best | two halves of size ≈ n/2 | T(n) = 2T(n/2) + Θ(n) | **Θ(n log n)** |
| Average | a constant fraction on each side | T(n) ≈ 2T(n/2) + Θ(n) | **Θ(n log n)** |
| Worst | 0 and n−1 elements (sorted / reverse-sorted input, or all equal with last-pivot) | T(n) = T(n−1) + Θ(n) | **Θ(n²)** |

The worst-case recurrence unrolls as n + (n−1) + … + 1 = n(n+1)/2 = Θ(n²). Quicksort is still the practical favourite because the average case is Θ(n log n) with small constants and it sorts in place; randomising the pivot avoids the sorted-input trap.

## ⚠️ Traps
1. Swapping before incrementing i (off-by-one) — the pivot lands in the wrong place.
2. Using `<` instead of `≤` — equal keys are pushed to one side, changing the partition behaviour.
3. Forgetting that the recursion is on (p, q−1) and (q+1, r) — including q again causes infinite recursion.
4. Calling the worst case O(n log n) — for last-element pivot on sorted data it is Θ(n²).

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 2(b) | 10 | Write quicksort; sort 15, 10, 13, 9, 12, 7; best/worst analysis | ✅ answered below |
| Dec-2025 | 3(b) | 10 | Write quicksort; worst case; sort 20, 5, 15, 8, 6, 28 | 🔓 unlocked — queued (same algorithm, different data) |

**Pattern:** quicksort appears in **2 of 4** sessions, both **10 marks** — medium-slot material, always “algorithm + sort this list + complexity”.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q2(c) [4 marks]**
> Explain the PARTITION algorithm of the Quick Sort taking the last element as pivot. Demonstrate the use of Quick sort algorithm for sorting the following data of size 8: [1, 5, 8, 11, 16, 19, 29, 38]. Compute the complexity of the worst case of Quick Sort algorithm.

*No figure printed in the question; the trace is shown in Figure 11.*

**PARTITION algorithm.** The pivot is the last element A[r]. The procedure keeps a boundary i such that A[p..i] contains the elements ≤ pivot, and scans j from p to r−1:

```
Algorithm Partition(A, p, r)
    x ← A[r];  i ← p − 1
    for j ← p to r − 1:
        if A[j] ≤ x:
            i ← i + 1;  swap A[i] with A[j]
    swap A[i + 1] with A[r]
    return i + 1
```

After the loop the pivot is swapped into position i+1, so it is in its final sorted place and the array is split into A[p..q−1] ≤ A[q] and A[q+1..r] > A[q]. Quicksort then recurses on the two sides. Each PARTITION is one pass over the sub-array, Θ(n) time, in place.

**Demonstration on [1, 5, 8, 11, 16, 19, 29, 38].**

- Pass 1: pivot 38. For j = 1…7 every A[j] ≤ 38, so i advances with j and no swap changes the array; finally 38 is swapped with itself. q = 8. Left sub-array: 7 elements, right: empty.
- Pass 2: pivot 29 → q = 7; pass 3: pivot 19 → q = 6; pass 4: pivot 16 → q = 5; pass 5: pivot 11 → q = 4; pass 6: pivot 8 → q = 3; pass 7: pivot 5 → q = 2. The array is sorted.

Comparisons = 7 + 6 + 5 + 4 + 3 + 2 + 1 = 28. The input was already sorted, which gives the **most unbalanced split possible**: every partition isolates exactly one element.

**Worst-case complexity.** The worst case arises when the pivot is always the smallest or largest element (sorted or reverse-sorted input). Then

> T(n) = T(n−1) + Θ(n) = (n + (n−1) + … + 1) = Θ(n²).

With balanced splits the recurrence is T(n) = 2T(n/2) + Θ(n) = Θ(n log n) (Master Case 2), so the **worst case Θ(n²)** is caused only by poor pivots; randomising the pivot or using the median avoids it.

**Hence the sorted input is sorted with 28 comparisons and the worst-case complexity of quicksort is Θ(n²).**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2025 | 2(b) | 10 | quicksort algorithm, trace, best/worst | ✅ answered below |
| Dec-2025 | 3(b) | 10 | quicksort, worst case, trace | 🔓 unlocked — queued |

### ✍️ TEE answer — Jun-2025, Q2(b) [10 marks]

**📄 Question — Jun-2025 TEE, Q2(b) [10 marks]**
> Write an algorithm for quick sort. Sort the following sequence of numbers using quick sort: 15, 10, 13, 9, 12, 7. Analyze the time complexity of quick sort in best and worst case.

**Algorithm** (last element as pivot):

```
Algorithm QuickSort(A, p, r)
    if p < r:
        q ← Partition(A, p, r)
        QuickSort(A, p, q − 1)
        QuickSort(A, q + 1, r)

Algorithm Partition(A, p, r)
    x ← A[r];  i ← p − 1
    for j ← p to r − 1:
        if A[j] ≤ x:  i ← i + 1;  swap A[i] with A[j]
    swap A[i + 1] with A[r]
    return i + 1
```

**Sorting 15, 10, 13, 9, 12, 7.**

- Partition 1: pivot 7. The scan finds no element ≤ 7 except the pivot; 15 is swapped with 7 → **[7, 10, 13, 9, 12, 15]**, q = 1.
- Left side (7) is a single element. Partition 2 on [10, 13, 9, 12, 15]: pivot 15; all others ≤ 15, so q = 6 and the left side is [10, 13, 9, 12].
- Partition 3 on [10, 13, 9, 12]: pivot 12. 10 ≤ 12 (i = 1); 13 > 12; 9 ≤ 12 → swap 13 and 9 → [10, 9, 13, 12]; finally swap 13 and 12 → **[10, 9, 12, 13]**, q = 4.
- Partition 4 on [10, 9]: pivot 9 → swap → **[9, 10]**, q = 2. The element 13 is alone.
- Concatenating the fixed positions: **[7, 9, 10, 12, 13, 15]**.

**Best case.** The pivot splits the array into two nearly equal halves: T(n) = 2T(n/2) + Θ(n) → **Θ(n log n)** (Master Case 2).

**Worst case.** The pivot is always the least or greatest element (sorted/reverse-sorted input): T(n) = T(n−1) + Θ(n) = Θ(n²) → **Θ(n²)**. This is what the first partition above nearly did — 7 was the minimum, so the split was 0 : 5.

**Hence quicksort sorts the sequence to [7, 9, 10, 12, 13, 15]; its best case is Θ(n log n) and its worst case Θ(n²).**

---

# Q2(d) — Divide-and-conquer matrix multiplication (4 marks)
*Assignment p. 4 · Book: Block 2 U2 §2.7 “Matrix Multiplication”, pp. 111–147*

## 🔰 L0. What this question assumes — matrices in plain words

A **matrix** is a rectangular grid of numbers; a 16×16 matrix has 16 rows and 16 columns. Matrix multiplication is “row times column”: each output entry is the sum of pairwise products of one row of the left matrix and one column of the right matrix.

> *Tiny 2×2 example:* [[a, b], [c, d]] × [[e, f], [g, h]] = [[ae+bg, af+bh], [ce+dg, cf+dh]]. The top-left entry uses row 1 of the first matrix and column 1 of the second: a·e + b·g.
>
> *Why multiplying a p×q matrix by a q×r matrix costs p·q·r scalar multiplications:* the result has p×r entries, and each entry needs q multiplications and q−1 additions. The · is ordinary number multiplication.

*If you code:* a matrix is a 2-D array, `A[row][col]`.

## 🧮 L1. Multiplying 16×16 matrices by divide and conquer

For C = A·B, split each n×n matrix into four (n/2)×(n/2) blocks:

> C₁₁ = A₁₁B₁₁ + A₁₂B₂₁, C₁₂ = A₁₁B₁₂ + A₁₂B₂₂, C₂₁ = A₂₁B₁₁ + A₂₂B₂₁, C₂₂ = A₂₁B₁₂ + A₂₂B₂₂.

Each block product is computed recursively; the four results are combined by additions. For n = 16 the recursion goes 16 → 8 → 4 → 2 → 1, so there are **8 recursive multiplications of 8×8** at the top level, 8² = 64 of 4×4, …, and 8⁴ = 4096 scalar multiplications at the leaves — the same count as the naive triple loop, because no multiplications were saved.

![D&C matrix multiplication](MCS-211_Assignment_Workbook.assets/fig_dc_matmul.png)
*🖼️ Figure 12 — Block decomposition of a 16×16 product: 8 recursive (n/2)×(n/2) products plus 4 block additions per quadrant.*

## ⏱️ L2. Time complexity

Each level performs 8 recursive multiplications of half size plus Θ(n²) additions/scalar work for the combining:

> T(n) = 8T(n/2) + Θ(n²).

Master method: a = 8, b = 2, f(n) = n²; leaf work n^(log₂8) = n³. Since f(n) = n² = O(n^(3−ε)), **Case 1** applies:

> **T(n) = Θ(n³)** — no asymptotic gain over the ordinary method.

**Strassen's improvement (book §2.7.2).** Strassen showed the four block products can be obtained from **7** auxiliary products M₁…M₇ instead of 8, at the cost of extra additions. The recurrence becomes T(n) = 7T(n/2) + Θ(n²) → Master Case 1 → T(n) = Θ(n^log₂7) ≈ **Θ(n^2.807)**, which for n = 16 means 7⁴ = 2401 scalar multiplications instead of 4096.

## ⚠️ Traps
1. Counting the additions as free — they are Θ(n²) per level and decide the recurrence's second term.
2. Saying “divide and conquer gives O(n log n)” — matrix multiplication is cubic, not n log n.
3. Mixing up the block index pattern when combining (C₁₁ = A₁₁B₁₁ + A₁₂B₂₁, not A₁₁B₁₁ + A₂₂B₂₂).

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 2(a) | 10 | Strassen's algorithm + multiply A=[[5,6],[−4,3]], B=[[−7,6],[5,9]] | ✅ answered below |

**Pattern:** D&C matrix multiplication appears in **1 of 4** sessions at 10 marks, always asking **Strassen's** variant rather than the plain block method the assignment asks for.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q2(d) [4 marks]**
> Explain the divide and conquer approach of multiplying two large matrices of size 16 × 16. Compute the time complexity of this approach.

*No figure printed in the question; the block split is shown in Figure 12.*

**Divide-and-conquer approach.** Let A and B be 16×16 matrices partitioned into four 8×8 blocks:

> A = [[A₁₁, A₁₂], [A₂₁, A₂₂]],  B = [[B₁₁, B₁₂], [B₂₁, B₂₂]].

The product C = A·B is formed block-wise:

> C₁₁ = A₁₁B₁₁ + A₁₂B₂₁,  C₁₂ = A₁₁B₁₂ + A₁₂B₂₂,
> C₂₁ = A₂₁B₁₁ + A₂₂B₂₁,  C₂₂ = A₂₁B₁₂ + A₂₂B₂₂.

Each of the eight products of 8×8 blocks is computed by the same procedure, recursively, until blocks of size 1×1 are multiplied as ordinary numbers; the four additions per output quadrant combine the results. For 16×16 the recursion depth is log₂16 = 4, and the number of scalar multiplications is 8⁴ = 4096 — identical to the ordinary three-loop method, which is why the plain block scheme changes the organisation but not the order of growth.

**Time complexity.** At every level there are 8 recursive multiplications of half size plus Θ(n²) work for the block additions and the divisions:

> T(n) = 8T(n/2) + Θ(n²),  T(1) = 1.

Here a = 8, b = 2, f(n) = Θ(n²), and n^(log₂ 8) = n³. Since f(n) = n² = O(n^(3−ε)), the Master theorem's **Case 1** gives:

> **T(n) = Θ(n³).**

With Strassen's seven-product variant the recurrence becomes T(n) = 7T(n/2) + Θ(n²) and the complexity drops to Θ(n^log₂7) ≈ Θ(n^2.807).

**Hence the divide-and-conquer multiplication of two 16×16 matrices runs in Θ(n³) time (4096 scalar multiplications at n = 16), improved to Θ(n^2.807) by Strassen's method.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2025 | 2(a) | 10 | Strassen's seven products, 2×2 application | ✅ answered below |

### ✍️ TEE answer — Jun-2025, Q2(a) [10 marks]

**📄 Question — Jun-2025 TEE, Q2(a) [10 marks]**
> Explain Strassen's Matrix Multiplication Algorithm and apply the same to multiply the following two matrices:
> A = [[5, 6], [−4, 3]],  B = [[−7, 6], [5, 9]]

**Algorithm.** For 2×2 matrices A = [[a₁₁, a₁₂], [a₂₁, a₂₂]] and B = [[b₁₁, b₁₂], [b₂₁, b₂₂]], Strassen computes seven products and combines them:

```
M₁ = (a₁₁ + a₂₂)(b₁₁ + b₂₂)      M₂ = (a₂₁ + a₂₂)b₁₁       M₃ = a₁₁(b₁₂ − b₂₂)
M₄ = a₂₂(b₂₁ − b₁₁)              M₅ = (a₁₁ + a₁₂)b₂₂       M₆ = (a₂₁ − a₁₁)(b₁₁ + b₁₂)
M₇ = (a₁₂ − a₂₂)(b₂₁ + b₂₂)

c₁₁ = M₁ + M₄ − M₅ + M₇          c₁₂ = M₃ + M₅
c₂₁ = M₂ + M₄                    c₂₂ = M₁ − M₂ + M₃ + M₆
```

It replaces **8** multiplications with **7** (10 extra additions trade for one multiplication). Applied recursively to n×n matrices, T(n) = 7T(n/2) + Θ(n²) → Θ(n^log₂7) ≈ Θ(n^2.807), beating the naive Θ(n³).

**Application.** a₁₁ = 5, a₁₂ = 6, a₂₁ = −4, a₂₂ = 3; b₁₁ = −7, b₁₂ = 6, b₂₁ = 5, b₂₂ = 9.

| Product | Computation | Value |
|---|---|---|
| M₁ | (5 + 3)(−7 + 9) = 8 × 2 | 16 |
| M₂ | (−4 + 3)(−7) = (−1)(−7) | 7 |
| M₃ | 5(6 − 9) = 5 × (−3) | −15 |
| M₄ | 3(5 − (−7)) = 3 × 12 | 36 |
| M₅ | (5 + 6)(9) = 11 × 9 | 99 |
| M₆ | (−4 − 5)(−7 + 6) = (−9)(−1) | 9 |
| M₇ | (6 − 3)(5 + 9) = 3 × 14 | 42 |

| Result | Computation | Value |
|---|---|---|
| c₁₁ | M₁ + M₄ − M₅ + M₇ = 16 + 36 − 99 + 42 | **−5** |
| c₁₂ | M₃ + M₅ = −15 + 99 | **84** |
| c₂₁ | M₂ + M₄ = 7 + 36 | **43** |
| c₂₂ | M₁ − M₂ + M₃ + M₆ = 16 − 7 − 15 + 9 | **3** |

**Check (ordinary multiplication):** c₁₁ = 5(−7) + 6(5) = −35 + 30 = −5; c₁₂ = 5(6) + 6(9) = 30 + 54 = 84; c₂₁ = −4(−7) + 3(5) = 28 + 15 = 43; c₂₂ = −4(6) + 3(9) = −24 + 27 = 3. ✔

**Hence A·B = [[−5, 84], [43, 3]], computed with 7 multiplications instead of 8.**

---

# Q2(e) — Topological sorting and strongly connected components (4 marks)
*Assignment p. 4 · Book: Block 2 U3 §3.5–3.6, pp. 148–162*

## 🧰 L1. Directed acyclic graphs and topological order

A **directed acyclic graph (DAG)** is a directed graph with no directed cycle. It models precedence: an edge u → v means “u must come before v”. A **topological ordering** is a linear order of the vertices such that for every edge u → v, u appears before v. If a graph has a cycle, no topological order exists — the ordering is possible exactly for DAGs.

**Read it aloud:** “Line up the tasks so that every arrow points forward.”

**Graph words this question uses:** a *vertex* (plural vertices) is a dot; an *edge* is a line joining two dots — in a **directed** graph each edge is an arrow (A → B is not B → A); the **in-degree** of a vertex is how many arrows point *into* it; a *cycle* is a route that returns to where it started; a **DAG** is a directed graph with **no** cycle. 📗.5 sketches a graph and a tree if these words are new. The in-degree is useful because a vertex with in-degree 0 has **no prerequisites** — it can be placed next.

## 🔁 L2. Kahn's algorithm (in-degree method)

```
Algorithm TopologicalSort(G)
    compute in-degree(v) for every vertex
    Q ← all vertices with in-degree 0        # can start immediately
    order ← empty
    while Q is not empty:
        u ← remove a vertex from Q
        append u to order
        for each edge (u → v):
            in-degree(v) ← in-degree(v) − 1
            if in-degree(v) = 0: add v to Q
    if |order| < |V|: report “cycle — no topological order”
    return order
```

**Read it aloud:** “Repeatedly take out a task with nothing left to wait for, append it, and cross it off its successors' to-do lists.” Here `Q` is just a **waiting line**: a vertex joins it the moment its last prerequisite is done, and the algorithm always takes the next one from the front. The book's recursive version does the same: find a zero in-degree vertex, output it, delete it, recurse on the rest. **Adjacency lists** = a list, for each vertex, of the edges leaving it (a grid of 0s and 1s stores the same information as an adjacency matrix).

**Complexity:** with adjacency lists every vertex and every edge is processed once → **O(V + E)**; the book's simple matrix-based version is O(n²).

## 🧩 L3. Strongly connected components (for the second part of the question)

In a directed graph, two vertices are **strongly connected** when there is a path from each to the other. A **strongly connected component (SCC)** is a maximal set of vertices that are all mutually reachable. In a DAG every SCC is a single vertex; the SCCs of a graph, collapsed, always form a DAG.

**Example:** in the directed graph with edges A→B, B→C, C→A and D→A, the set {A, B, C} is one SCC (you can go from any of them to any other), while D alone is another.

## ⚠️ Traps
1. Assuming every directed graph has a topological order — cycles make it impossible.
2. Forgetting to decrement the in-degree only for **outgoing** edges of the removed vertex.
3. Confusing “connected” (undirected) with “strongly connected” (directed, both ways).
4. Reporting a topological order without checking that every edge points forward.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 1(f) | 5 | Find the topological ordering of a graph (figure) | 🔓 unlocked — queued (same algorithm, different graph) |
| Jun-2026 | 4(b) | 10 | Define topological sorting; perform it on a graph (figure) | ✅ answered below |

**Pattern:** topological sorting appears in **2 of 4** sessions at 5 and 10 marks, always as “apply it to the given graph”.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q2(e) [4 marks]**
> Write and explain the algorithm of Topological sorting with the help of an example. Also, define the concept of strongly connected components in a directed Graph.

*No figure printed in the question; the example DAG is drawn in Figure 13.*

**Algorithm (Kahn's in-degree method).**

```
Algorithm TopologicalSort(G)
    compute in-degree(v) for every vertex
    Q ← all vertices with in-degree 0
    order ← empty
    while Q is not empty:
        u ← remove any vertex from Q
        append u to order
        for each edge (u → v):
            in-degree(v) ← in-degree(v) − 1
            if in-degree(v) = 0: add v to Q
    if |order| < |V|: the graph has a cycle (no topological order)
    return order
```

**Explanation.** A vertex with in-degree 0 has no prerequisite, so it can be placed first. After placing it, it is removed from the graph; this decreases the in-degree of each successor, and any successor that reaches in-degree 0 becomes free. Repeating this gives a valid order. With adjacency lists the algorithm is O(V + E).

![Example DAG with a topological order](MCS-211_Assignment_Workbook.assets/fig_dag_topo.png)
*🖼️ Figure 13 — A small DAG; V1 → V2 → V3 → V4 → V5 is one valid topological order (V2 and V3 can be interchanged).*

**Worked example.** For the DAG V1→V2, V1→V3, V2→V4, V3→V4, V3→V5, V4→V5: in-degrees are V1:0, V2:1, V3:1, V4:2, V5:2. Start with V1; removing it frees V2 and V3; remove V2 (V4 becomes 1); remove V3 (V4 becomes 0, V5 becomes 1); remove V4 (V5 becomes 0); remove V5. Order: **V1, V2, V3, V4, V5**. Check: every edge points forward in this order. ✔

**Strongly connected components.** Two vertices of a directed graph are strongly connected if a directed path exists from each to the other; a strongly connected component (SCC) is a maximal set of vertices that are pairwise strongly connected. SCCs are computed by two DFS passes (Kosaraju/Sharir) in O(V + E). Inside an SCC every task depends on every other, so an SCC can be contracted to a single node to obtain the DAG of the graph. *Example:* with edges A→B, B→C, C→A and D→A, the component {A, B, C} is strongly connected; D alone forms a second SCC.

**Hence topological sorting orders a DAG in O(V + E) and is impossible when a cycle exists; SCCs are the maximal mutually-reachable vertex sets of a directed graph.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2026 | 4(b) | 10 | define topological sort, apply to a graph | ✅ answered below |
| Dec-2024 | 1(f) | 5 | find a topological ordering | ✅ answered below |

### ✍️ TEE answer — Jun-2026, Q4(b) [10 marks]

**📄 Question — Jun-2026 TEE, Q4(b) [10 marks]**
> Define topological sorting of a graph and perform topological sorting of the following graph:

![Question figure — Jun-2026 TEE, Q4(b)](MCS-211_Assignment_Workbook.assets/fig_tee_jun26_topo.png)
*🖼️ Figure 14 — The question's graph (a → b, a → c, a → d, b → e, c → f, d → c, d → f, e → d, e → f, g → d, g → e, g → f).*

**Definition.** A topological sort of a DAG G = (V, E) is a linear ordering of its vertices such that for every directed edge (u, v), u comes before v. Equivalently, all arrows point forward in the ordering. A graph has a topological sort if and only if it is acyclic.

**Algorithm (Kahn).** Compute in-degrees; repeatedly output a vertex with in-degree 0, delete it, and decrement its successors' in-degrees.

**Step-by-step application.**

| Step | In-degree-zero set | Output | Effect |
|---|---|---|---|
| 0 | a, g | — | initial in-degrees: a0, b1, c2, d3, e2, f4, g0 |
| 1 | pick a | **a** | b→0, c→1, d→2 |
| 2 | b, g | **b** | e→1 |
| 3 | g | **g** | d→1, e→0, f→3 |
| 4 | e | **e** | d→0, f→2 |
| 5 | d | **d** | c→0, f→1 |
| 6 | c | **c** | f→0 |
| 7 | f | **f** | done |

**Order: a, b, g, e, d, c, f.** Verification: every edge of the graph is respected — a before b, c, d; b before e; g before d, e, f; e before d, f; d before c, f; c before f. ✔ (Other valid orders exist, e.g. g, a, b, e, d, c, f, because Kahn's queue allows any zero in-degree choice.)

**Hence a valid topological order is a → b → g → e → d → c → f.**

### ✍️ TEE answer — Dec-2024, Q1(f) [5 marks]

**📄 Question — Dec-2024 TEE, Q1(f) [5 marks]**
> Find the topological ordering of the following graph:

![Question figure — Dec-2024 TEE, Q1(f)](MCS-211_Assignment_Workbook.assets/fig_tee_dec24_topo.png)
*🖼️ Figure 15 — The question's graph: A → B, A → E, B → C, E → F, F → C, D → C, D → F.*

**In-degrees:** A 0, B 1 (from A), C 3 (from B, D, F), D 0, E 1 (from A), F 2 (from D, E).

| Step | Pick (in-degree 0) | Output | Effect |
|---|---|---|---|
| 1 | A or D — pick A | **A** | B→0, E→0 |
| 2 | B or D — pick B | **B** | C→2 |
| 3 | D | **D** | C→1, F→1 |
| 4 | E | **E** | F→0 |
| 5 | F | **F** | C→0 |
| 6 | C | **C** | done |

**Order: A, B, D, E, F, C.** Verification: A before B and E; B before C; D before C and F; E before F; F before C. ✔ (Other valid orders exist, e.g. A, D, B, E, F, C, because Kahn's queue allows any zero in-degree choice.)

**Hence a topological ordering of the given graph is A → B → D → E → F → C.**

---

# Q3 — Graph Algorithms, Dynamic Programming and String Matching (20 marks)
*Assignment pp. 4–5 · Book: Block 3 U1–U3, pp. 163–228*

**📄 Question context — MCS-211 assignment, p. 4, Q3**
> Consider the following Graph:

![Question figure — assignment Q3 (Figure 1 of the paper)](MCS-211_Assignment_Workbook.assets/fig_q3_graph.png)
*🖼️ Figure 16 — Question figure (the paper's “Figure 1: A sample weighted Graph”). Edges: A–B 20, A–E 8, B–C 20, B–E 10, C–D 12, C–G 16, D–F 17, E–F 25, F–G 17. All parts of Q3 that say “the graph given in Figure 1” refer to this figure.*

---

# Q3(a) — Kruskal and Prim; MST of Figure 1 (4 marks)
*Assignment p. 4 · Book: Block 3 U1 §1.2 “Minimum Spanning Tree”, pp. 163–194*

## 🧰 L1. Spanning tree, minimum spanning tree, safe edge

A **spanning tree** of a connected weighted graph G = (V, E) is a subgraph that contains every vertex, is connected, and has exactly |V| − 1 edges (no cycles). A **minimum spanning tree (MST)** is a spanning tree of least total edge weight. The greedy **cut property** justifies both algorithms: if (u, v) is a minimum-weight edge crossing any cut of the graph, then some MST contains it — such an edge is called a **safe edge**.

**Read it aloud:** “Connect all the nodes with the cheapest possible set of wires and no loops.”

**Two words worth pausing on.** A *cut* is any way of splitting the vertices into two groups; an edge *crosses* the cut when its two ends fall in different groups. The cut property says the cheapest crossing edge is always safe — choosing it can never destroy the possibility of an optimal tree. A *forest* is simply a collection of separate trees (the chosen edges form a forest until the MST is complete).

## 🧱 L2. Kruskal's algorithm

```
Algorithm MCST_Kruskal(V, E, w)
    K ← { }
    for each vertex v in V:  MAKE-SET(v)          # each vertex starts alone
    sort the edges of E by non-decreasing weight
    for each edge (u, v) in sorted order:
        if FIND-SET(u) ≠ FIND-SET(v):             # different trees → no cycle
            K ← K ∪ {(u, v)}                      # safe edge
            UNION(u, v)
    return K                                      # |K| = |V| − 1 edges
```

**Read it aloud:** “Walk the edges from cheapest to dearest; keep an edge only if its ends belong to different trees (i.e. it does not close a cycle).”

**MAKE-SET, FIND-SET, UNION in plain words.** Imagine every vertex wears a **badge** naming the tree it belongs to. MAKE-SET(v) hands vertex v a new badge of its own. FIND-SET(u) reads u's badge. UNION(u, v) repaints both groups with one common badge. Kruskal keeps edge (u, v) exactly when the two endpoints wear **different** badges — then the edge cannot close a cycle. *If you code:* this structure is a disjoint-set forest (union–find), which makes each check almost O(1).

**Complexity:** sorting E edges costs O(E log E); MAKE-SET is O(V); the FIND/UNION loop with a disjoint-set forest is O(E log V) in the book's analysis. Overall **O(E log E) = O(E log V)** time, plus O(V) space. For a dense graph E = V², giving O(V² log V).

## 🌱 L3. Prim's algorithm

```
Algorithm MCST_Prim(V, E, w, r)                  # r = starting vertex
    start the tree with vertex r
    while the tree has fewer than |V| vertices:
        choose the minimum-weight edge (u, v) with u in the tree
        and v outside it                       # safe edge
        add v (and the edge) to the tree
    return the tree
```

Prim grows one tree from a seed; Kruskal grows a forest and merges it. With an adjacency matrix Prim is O(V²); with a binary heap and adjacency lists it is O(E log V).

## 🧪 L4. Demonstration on Figure 1

Edges sorted by weight: A–E 8, B–E 10, C–D 12, C–G 16, D–F 17, F–G 17, A–B 20, B–C 20, E–F 25.

**Kruskal:**

| Step | Edge | Weight | Action | Components after |
|---|---|---|---|---|
| 1 | A–E | 8 | accept | {A,E} |
| 2 | B–E | 10 | accept | {A,B,E} |
| 3 | C–D | 12 | accept | {C,D} |
| 4 | C–G | 16 | accept | {C,D,G} |
| 5 | D–F | 17 | accept | {C,D,F,G} |
| 6 | F–G | 17 | **reject** (cycle F–G–C–D–F) | — |
| 7 | A–B | 20 | **reject** (cycle A–E–B–A) | — |
| 8 | B–C | 20 | accept (joins the two components) | {A,B,C,D,E,F,G} |
| 9 | E–F | 25 | not needed (already \|V\|−1 = 6 edges) | — |

**MST = {A–E 8, B–E 10, C–D 12, C–G 16, D–F 17, B–C 20}; total weight = 8 + 10 + 12 + 16 + 17 + 20 = 83.**

**Prim starting from A:**

| Step | Tree vertices | Cheapest edge leaving the tree | Add |
|---|---|---|---|
| 1 | {A} | A–E 8 (vs A–B 20) | E, weight 8 |
| 2 | {A,E} | B–E 10 (vs A–B 20, E–F 25) | B, weight 10 |
| 3 | {A,B,E} | B–C 20 (A–B rejected: cycle) | C, weight 20 |
| 4 | {A,B,C,E} | C–D 12 (vs C–G 16) | D, weight 12 |
| 5 | {A,B,C,D,E} | C–G 16 (vs D–F 17) | G, weight 16 |
| 6 | {A,B,C,D,E,G} | D–F 17 (F–G 17 would create a cycle) | F, weight 17 |

**Total = 8 + 10 + 20 + 12 + 16 + 17 = 83** — the same tree as Kruskal. (F–G 17 is an equally cheap alternative to D–F 17, so the MST is not unique; both choices total 83.)

![MST of the assignment graph](MCS-211_Assignment_Workbook.assets/fig_mst.png)
*🖼️ Figure 17 — The MST found by both algorithms: A–E 8, B–E 10, C–D 12, C–G 16, D–F 17, B–C 20 (green); grey edges are the rejected ones.*

## ⚠️ Traps
1. Accepting an edge that closes a cycle (Kruskal) — the FIND-SET test must fail.
2. Stopping Kruskal after fewer than |V|−1 edges — the tree is incomplete.
3. In Prim, choosing the cheapest edge **inside** the tree instead of an edge leaving it.
4. Adding all |V| edges — a spanning tree has exactly |V| − 1.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2025 | 1(f) | 5 | Explain Kruskal's algorithm for MST construction | 🔓 unlocked — queued |
| Jun-2026 | 1(h) | 4 | Use Kruskal on a given 4-vertex graph | ✅ answered below |
| Jun-2025 | 3(b) | 10 | Prim's algorithm + MST of a figure | 🔓 unlocked — queued (Prim taught; needs the paper's figure) |
| Dec-2025 | 4(a) | 10 | Prim's algorithm + MST of a figure | 🔓 unlocked — queued (Prim taught; needs the paper's figure) |

**Pattern:** MST appears in **4 of 4** sessions (4, 5, 10, 10 marks) — one of the surest topics in the paper. Kruskal and Prim are asked alternately.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q3(a) [4 marks]**
> Write the Kruskal's algorithm to find the minimum cost spanning tree of a graph. Also, find the time complexity of Kruskal's algorithm. Demonstrate the use of Kruskal's algorithm and Prim's algorithm to find the minimum cost spanning tree for the Graph given in Figure 1. Show all the steps.

*The question figure is reproduced as Figure 16; the resulting MST is Figure 17.*

**Kruskal's algorithm.**

```
Algorithm MCST_Kruskal(V, E, w)
    K ← { } ;  MAKE-SET(v) for every vertex v
    sort E by non-decreasing weight
    for each edge (u, v) in sorted order:
        if FIND-SET(u) ≠ FIND-SET(v):
            K ← K ∪ {(u, v)} ;  UNION(u, v)
    return K
```

It selects edges in increasing weight order and keeps an edge exactly when it joins two different components (i.e. does not form a cycle); after |V| − 1 edges the MST is complete.

**Complexity.** Sorting the E edges: O(E log E). Initialising the disjoint sets: O(V). The loop performs O(E) FIND/UNION operations, O(E log V). Dominated by the sort, the total is **O(E log E) = O(E log V)**.

**Kruskal on Figure 1.** Sorted edges: A–E 8, B–E 10, C–D 12, C–G 16, D–F 17, F–G 17, A–B 20, B–C 20, E–F 25.

| Step | Edge | Weight | Decision | Components |
|---|---|---|---|---|
| 1 | A–E | 8 | include | {A,E} |
| 2 | B–E | 10 | include | {A,B,E} |
| 3 | C–D | 12 | include | {C,D} |
| 4 | C–G | 16 | include | {C,D,G} |
| 5 | D–F | 17 | include | {C,D,F,G} |
| 6 | F–G | 17 | reject — cycle F–G–C–D–F | — |
| 7 | A–B | 20 | reject — cycle A–E–B–A | — |
| 8 | B–C | 20 | include — joins the two components | all 7 vertices |

MST edges: A–E, B–E, C–D, C–G, D–F, B–C. **Total weight = 8 + 10 + 12 + 16 + 17 + 20 = 83 units.**

**Prim on Figure 1 (starting from A).**

| Step | Tree | Minimum edge leaving the tree | New vertex | Weight |
|---|---|---|---|---|
| 1 | {A} | A–E 8 | E | 8 |
| 2 | {A,E} | B–E 10 | B | 10 |
| 3 | {A,B,E} | B–C 20 | C | 20 |
| 4 | {A,B,C,E} | C–D 12 | D | 12 |
| 5 | {A,B,C,D,E} | C–G 16 | G | 16 |
| 6 | {A,B,C,D,E,G} | D–F 17 | F | 17 |

**Total = 8 + 10 + 20 + 12 + 16 + 17 = 83 units** — identical to Kruskal's tree (the tie D–F 17 / F–G 17 means an equally good alternative exists).

**Hence the minimum spanning tree of Figure 1 costs 83 and consists of the edges A–E, B–E, B–C, C–D, C–G, D–F; both greedy algorithms find it.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2026 | 1(h) | 4 | Kruskal on a given graph | ✅ answered below |
| Dec-2025 | 1(f) | 5 | explain Kruskal | 🔓 unlocked — queued |
| Jun-2025 | 3(b) | 10 | Prim + graph figure | 🔓 unlocked — queued |
| Dec-2025 | 4(a) | 10 | Prim + graph figure | 🔓 unlocked — queued |

### ✍️ TEE answer — Jun-2026, Q1(h) [4 marks]

**📄 Question — Jun-2026 TEE, Q1(h) [4 marks]**
> Use the Kruskal's algorithm to find the minimum cost spanning tree for the following graph:

![Question figure — Jun-2026 TEE, Q1(h)](MCS-211_Assignment_Workbook.assets/fig_tee_jun26_kruskal.png)
*🖼️ Figure 18 — The question's graph: edges A–B 5, B–C 7, B–D 2, A–D 4, C–D 4.*

**Algorithm.** Sort the edges by weight; add an edge when it does not form a cycle with the edges already chosen; stop at |V| − 1 = 3 edges.

**Sorted edges:** B–D 2, A–D 4, C–D 4, A–B 5, B–C 7.

| Step | Edge | Weight | Decision | Components |
|---|---|---|---|---|
| 1 | B–D | 2 | include | {B,D} |
| 2 | A–D | 4 | include | {A,B,D} |
| 3 | C–D | 4 | include | {A,B,C,D} |
| — | A–B | 5 | not needed (already 3 = \|V\|−1 edges) | — |
| — | B–C | 7 | not needed | — |

**MST = {B–D 2, A–D 4, C–D 4}; total cost = 2 + 4 + 4 = 10.**

**Hence the minimum spanning tree has cost 10 units.**

---

# Q3(b) — Bellman-Ford shortest paths from A (4 marks)
*Assignment p. 4 · Book: Block 3 U1 §1.3.2 “Bellman-Ford Algorithm”, pp. 163–194*

## 🧰 L1. Relaxation — the one operation of shortest-path algorithms

Every shortest-path algorithm maintains an estimate dist[v] (initially 0 for the source and ∞ everywhere else) and repeatedly **relaxes** each edge (u, v):

> if dist[u] + w(u, v) < dist[v], then dist[v] ← dist[u] + w(u, v).

**Read it aloud:** “If I can reach v more cheaply through u, update v's estimate.” Bellman-Ford relaxes **all** edges |V| − 1 times; after that every shortest path (which has at most |V| − 1 edges) has been discovered. A |V|-th pass that still changes a distance proves a negative cycle.

**Two terms in plain words.** *∞ (infinity)* is the starting estimate for “no route found yet”: it is larger than every real total, so the very first route discovered always improves it. A **negative cycle** is a loop whose total weight is negative — walking round it would keep reducing the cost forever, so a “shortest path” would be −∞, which is meaningless; the extra pass exists to detect exactly that and report it. In an all-positive graph like Figure 1 the check can never fire, but the algorithm is defined to run it.

## 🔁 L2. The algorithm

```
Algorithm BellmanFord(G, V, E, w, s)
    dist[s] ← 0 ;  dist[v] ← ∞ for every v ≠ s
    for i ← 1 to |V| − 1:
        for each edge (u, v) in E:
            if dist[u] + w(u, v) < dist[v]:
                dist[v] ← dist[u] + w(u, v)
    for each edge (u, v):
        if dist[u] + w(u, v) < dist[v]:  return FALSE   # negative cycle
    return TRUE
```

Unlike Dijkstra, Bellman-Ford handles **negative edge weights** (and detects negative cycles); the price is O(V) passes over all edges → **O(V·E)** time. For the undirected graph of Figure 1, each edge is relaxed in both directions.

## 🧪 L3. Worked on Figure 1 from source A

Edge order used: (A,E), (A,B), (B,E), (B,C), (C,D), (C,G), (D,F), (E,F), (F,G); each undirected edge is examined both ways.

**Initialisation:** dist(A) = 0, all others ∞.

**Pass 1:**

| Edge examined | Relaxation | dist after |
|---|---|---|
| A–E (8) | E = 0 + 8 = 8 | E=8 |
| A–B (20) | B = 0 + 20 = 20 | B=20 |
| B–E (10) | E = min(8, 20+10)=8; B = min(20, 8+10)=18 | B=18 |
| B–C (20) | C = 18 + 20 = 38 | C=38 |
| C–D (12) | D = 38 + 12 = 50 | D=50 |
| C–G (16) | G = 38 + 16 = 54 | G=54 |
| D–F (17) | F = 50 + 17 = 67 | F=67 |
| E–F (25) | F = min(67, 8+25)=33 | F=33 |
| F–G (17) | G = min(54, 33+17)=50 | G=50 |

After pass 1: A=0, B=18, C=38, D=50, E=8, F=33, G=50. **Pass 2** relaxes every edge again and changes nothing (e.g. G = min(50, 33+17) = 50; C = min(38, 18+20) = 38), so the distances have converged; passes 3–6 are also no-ops. (The algorithm is allowed to stop early when a full pass makes no change.)

**Shortest paths from A:**

| Vertex | Distance | Path |
|---|---|---|
| A | 0 | — |
| B | 18 | A → E → B (8 + 10) |
| C | 38 | A → E → B → C (8 + 10 + 20) |
| D | 50 | A → E → B → C → D (8+10+20+12) or A → E → F → D (8+25+17) |
| E | 8 | A → E |
| F | 33 | A → E → F (8 + 25) |
| G | 50 | A → E → F → G (8 + 25 + 17) |

![Shortest paths from A](MCS-211_Assignment_Workbook.assets/fig_sssp.png)
*🖼️ Figure 19 — The shortest-path tree from A (green); vertex labels under each node are the final distances.*

## ⚠️ Traps
1. Running only one pass — some distances need more than one relaxation (B needed A–E then B–E in the same pass because of edge order; other orders need more).
2. Forgetting the negative-cycle check pass.
3. Applying Dijkstra with negative weights — Bellman-Ford is the algorithm that tolerates them.
4. Updating dist[u] while scanning the same edge backwards in an undirected graph is fine, but each edge must be relaxed in **both** directions.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| — | — | — | No archived Bellman-Ford question in the 4 sessions | — |
| Dec-2024 | 1(h), 4(a) | 5, 10 | Dijkstra's algorithm (disadvantages / SSSP) | ⏳ blocked — needs Dijkstra lesson |
| Jun-2025 | 4(b) | 10 | Dijkstra from a given source | ⏳ blocked — needs Dijkstra lesson |
| Dec-2025 | 3(a) | 10 | Dijkstra from vertex 'a' | ⏳ blocked — needs Dijkstra lesson |

**Pattern:** the paper asks **Dijkstra** for SSSP (3 of 4 sessions); Bellman-Ford itself has not appeared. Both solve the same problem, but Dijkstra is a different, greedy algorithm and stays blocked until taught.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q3(b) [4 marks]**
> Write the Bellman-Ford shortest path algorithm. What is the time complexity of this shortest path algorithm? Find the shortest paths from the vertex ‘A’ using Bellman-Ford's shortest path algorithm for the graph given in Figure 1. Show all the steps of computation.

*The question figure is Figure 16.*

**Algorithm.** Bellman-Ford keeps distance estimates and relaxes every edge |V| − 1 times; a final pass detects negative-weight cycles.

```
Algorithm BellmanFord(G, V, E, w, s)
    dist[s] ← 0 ;  dist[v] ← ∞ for all v ≠ s
    for i ← 1 to |V| − 1:
        for each edge (u, v) in E:
            if dist[u] + w(u, v) < dist[v]:
                dist[v] ← dist[u] + w(u, v)
    for each edge (u, v):                       # negative-cycle check
        if dist[u] + w(u, v) < dist[v]:  return FALSE
    return TRUE
```

**Complexity.** The outer loop runs |V| − 1 times and each pass examines all |E| edges once, so the time is **O(V·E)**; the space is O(V) for the distance array.

**Computation for Figure 1 (source A, |V| = 7, so up to 6 passes).** Edge order: A–E, A–B, B–E, B–C, C–D, C–G, D–F, E–F, F–G; each undirected edge is used in both directions.

*Initialisation:* dist(A) = 0, dist(B) = dist(C) = dist(D) = dist(E) = dist(F) = dist(G) = ∞.

*Pass 1:*

| Relaxation | New value |
|---|---|
| dist(E) = 0 + 8 | 8 |
| dist(B) = 0 + 20 | 20 |
| dist(E) = min(8, 20 + 10); dist(B) = min(20, 8 + 10) | 8; 18 |
| dist(C) = 18 + 20 | 38 |
| dist(D) = 38 + 12 | 50 |
| dist(G) = 38 + 16 | 54 |
| dist(F) = 50 + 17 | 67 |
| dist(F) = min(67, 8 + 25) | 33 |
| dist(G) = min(54, 33 + 17) | 50 |

After pass 1: (A, B, C, D, E, F, G) = (0, 18, 38, 50, 8, 33, 50). Pass 2 checks every edge and changes no value — the estimates are final.

**Shortest paths from A:** A→E = 8 (direct); A→E→B = 18; A→E→B→C = 38; A→E→B→C→D = 50 (equally A→E→F→D = 8 + 25 + 17 = 50); A→E→F = 33; A→E→F→G = 8 + 25 + 17 = 50.

**Hence the shortest distances from A are: A 0, B 18, C 38, D 50, E 8, F 33, G 50 units, found in O(V·E) time.**

## 📝 TEE layer

No past question on Bellman-Ford exists in the archive; the related Dijkstra questions are ⏳ blocked (see the trail). Nothing to answer here without inventing a “TEE version”.

---

# Q3(c) — Optimal Binary Search Tree (6 marks)
*Assignment pp. 4–5 · Book: Block 3 U2 §2.5, pp. 195–218*

## 🔰 L0. What this question assumes — a binary search tree in one minute

A **tree** is a set of dots (nodes) joined so that there is exactly one route between any two, with one dot at the top (the **root**) and **leaves** at the bottom (📗.5). In a **binary search tree (BST)** each node holds a key and has at most two children, arranged so that **smaller keys go left and larger keys go right**. A search starts at the root and moves down one level per comparison, so its cost is the node's **depth + 1** comparisons (root = depth 0 = 1 comparison).

This question asks: among all BSTs that hold the given keys, which one has the **smallest average search cost**, where each key is searched with its own probability? A shallow, well-balanced tree is usually good — but if one key is searched very often, it may be worth putting *that* key near the root even if other keys become deeper. That trade-off is what the table below optimises.

## 🧰 L1. What makes a BST “optimal”

A binary search tree stores keys so that a search costs the number of nodes examined = depth + 1. If key kᵢ is searched with probability pᵢ and a missing key in gap dᵢ with probability qᵢ, the **expected search cost** of a tree T is

> E[search cost] = Σᵢ (depth(kᵢ)+1)·pᵢ + Σᵢ (depth(dᵢ)+1)·qᵢ, with Σpᵢ + Σqᵢ = 1.

An **optimal BST (OBST)** is a BST of minimum expected cost. A low average-depth tree is what we want — not necessarily the shallowest tree.

**Symbol card — pᵢ and qᵢ:** read “p sub i” and “q sub i”. pᵢ = probability that the search asks for stored key kᵢ; qᵢ = probability that it asks for a value falling in the gap dᵢ between kᵢ and kᵢ₊₁ (d₀ = before k₁, dₙ = after kₙ). Why both: searches can succeed (hit a key) or fail (hit a gap), and both consume comparisons. Example: q₀ = 0.10 means 10% of searches fall below the smallest key.

**Worked shape:** if key kᵣ is the root, its subtree contains keys kᵢ…kⱼ; choosing r optimally splits the problem into the left range kᵢ…kᵣ₋₁ and the right range kᵣ₊₁…kⱼ. Trying every r gives the recurrence, and each sub-range is reused — the classic DP situation (Q3(d) teaches the DP machinery in full).

## 🧮 L2. The DP tables

Let e[i, j] = expected cost of an optimal BST on keys kᵢ…kⱼ, and w[i, j] = total probability weight of that range:

> w[i, j] = Σ_{k=i..j} pₖ + Σ_{k=i−1..j} qₖ,  e[i, j] = min_{i ≤ r ≤ j} { e[i, r−1] + e[r+1, j] + w[i, j] }.

Base case: e[i, i−1] = qᵢ₋₁ (only the dummy key dᵢ₋₁). The table is filled by increasing length; root[i, j] records the best r.

```
Algorithm OptimalBST(p[1..n], q[0..n], n)
    for i ← 1 to n+1:  e[i, i−1] ← q_{i−1};  w[i, i−1] ← q_{i−1}
    for l ← 1 to n:                       # sub-range length
        for i ← 1 to n − l + 1:
            j ← i + l − 1
            w[i, j] ← w[i, j−1] + p[j] + q[j]
            e[i, j] ← ∞
            for r ← i to j:
                t ← e[i, r−1] + e[r+1, j] + w[i, j]
                if t < e[i, j]:  e[i, j] ← t;  root[i, j] ← r
    return e, root
```

**Complexity:** three nested loops over the n lengths and n ranges and n roots → **Θ(n³)** time, **Θ(n²)** space for the tables.

## 🧪 L3. Worked on the assignment probabilities

Keys k₁…k₄ with p = (0.15, 0.05, 0.15, 0.25) and q = (0.10, 0.05, 0.05, 0.10, 0.10); Σp + Σq = 0.60 + 0.40 = 1.00. ✔

**w-table** (base w[i,i−1] = qᵢ₋₁, then w[i,j] = w[i,j−1] + p_j + q_j):

| w[i,j] | j=0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|---|
| i=1 | 0.10 | 0.30 | 0.40 | 0.65 | 1.00 |
| 2 | 0.05 | 0.15 | 0.40 | 0.75 | — |
| 3 | 0.05 | 0.30 | 0.65 | — | — |
| 4 | 0.10 | 0.45 | — | — | — |
| 5 | 0.10 | — | — | — | — |

**e-table** (diagonal order; value = min over roots + w[i,j], root in parentheses):

| e[i,j] | j=1 | j=2 | j=3 | j=4 |
|---|---|---|---|---|
| i=1 | 0.45 (r1) | 0.75 (r1) | 1.50 (r1) | **2.40 (r3)** |
| i=2 | — | 0.25 (r2) | 0.75 (r3) | 1.60 (r4) |
| i=3 | — | — | 0.45 (r3) | 1.20 (r4) |
| i=4 | — | — | — | 0.65 (r4) |

Key rows: e[1,2] = min{0.10+0.25, 0.45+0.05} + 0.40 = 0.35 + 0.40 = 0.75 (root 1). e[1,4] = min{0.10+1.60, 0.45+1.20, 0.75+0.65, 1.50+0.10} + 1.00 = 1.40 + 1.00 = **2.40**, root 3.

**Tree reconstruction.** root[1,4] = 3 → k₃ at the root. Left range 1–2: root[1,2] = 1 → k₁, with k₂ as its right child (root[2,2] = 2). Right range 4–4: k₄.

```
      k₃
     /  \
   k₁    k₄
     \
     k₂
```

![Optimal BST for the assignment data](MCS-211_Assignment_Workbook.assets/fig_obst.png)
*🖼️ Figure 20 — The optimal tree: k₃ root, k₁ left, k₂ as k₁'s right child, k₄ right; expected cost 2.40.*

**Verification by direct cost:** levels: k₃=1, k₁=2, k₄=2, k₂=3; d₀=3, d₁=4, d₂=4, d₃=3, d₄=3. Cost = 1(0.15) + 2(0.15) + 2(0.25) + 3(0.05) + 3(0.10) + 4(0.05) + 4(0.05) + 3(0.10) + 3(0.10) = 0.15 + 0.30 + 0.50 + 0.15 + 0.30 + 0.20 + 0.20 + 0.30 + 0.30 = **2.40**. ✔

## ⚠️ Traps
1. Using only pᵢ in w[i,j] and forgetting the dummy probabilities qᵢ — the answer will be too small.
2. Trying all trees by hand instead of using the tables — the DP exists to avoid that.
3. Reading the root table with the wrong convention (root[i,j] is the index r, not a key value).
4. Filling e by rows instead of by increasing length — sub-problem values would not exist yet.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| — | — | — | No archived OBST question | — |
| Dec-2024 | 5(b) | 4+6 | Binomial coefficients by recursion vs DP | ⏳ blocked — needs DP/binomial lesson |
| Dec-2025 | 1(d) | 5 | All BSTs on 3 keys | ⏳ blocked — needs Catalan/BST enumeration lesson |
| Jun-2026 | 1(f) | 6 | All BSTs on 3 keys | ⏳ blocked — needs Catalan/BST enumeration lesson |

**Pattern:** OBST itself is not in the archive; DP appears through **matrix-chain multiplication** and binomial coefficients instead. The neighbouring “how many BSTs” question needs a separate counting lesson.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 4, Q3(c) [6 marks]**
> Write the algorithm to find the Optimal Binary Search Tree. Demonstrate this algorithm to find the Optimal Binary Search Tree for the following probabilities of search (where pᵢ represents the probability that the search will be for the key node kᵢ, whereas qᵢ represents that the search is for dummy node dᵢ. Make suitable assumptions, if any)
> i: 0 1 2 3 4 · pᵢ: — 0.15 0.05 0.15 0.25 · qᵢ: 0.10 0.05 0.05 0.10 0.10

*No figure printed in the question; the optimal tree is Figure 20.*

**Assumption:** the four keys are k₁ < k₂ < k₃ < k₄ and the dummy keys d₀ < k₁ < d₁ < k₂ < d₂ < k₃ < d₃ < k₄ < d₄ represent unsuccessful searches. Check: Σpᵢ = 0.60, Σqᵢ = 0.40, total 1.00. ✔

**Algorithm.** Let e[i,j] be the minimum expected cost of a BST containing keys kᵢ…kⱼ and w[i,j] the total probability of that range. Choosing key kᵣ as root gives e[i,j] = min_r { e[i,r−1] + e[r+1,j] } + w[i,j], with base e[i,i−1] = qᵢ₋₁.

```
Algorithm OptimalBST(p[1..n], q[0..n], n)
    for i ← 1 to n+1:  e[i,i−1] ← q_{i−1};  w[i,i−1] ← q_{i−1}
    for l ← 1 to n:
        for i ← 1 to n−l+1:
            j ← i+l−1
            w[i,j] ← w[i,j−1] + p[j] + q[j]
            e[i,j] ← ∞
            for r ← i to j:
                t ← e[i,r−1] + e[r+1,j] + w[i,j]
                if t < e[i,j]:  e[i,j] ← t ;  root[i,j] ← r
    return e, root
```

**Working.**

w-table (only the needed entries):

| | j=0 | j=1 | j=2 | j=3 | j=4 |
|---|---|---|---|---|---|
| w[1,j] | 0.10 | 0.30 | 0.40 | 0.65 | 1.00 |
| w[2,j] | 0.05 | 0.15 | 0.40 | 0.75 | — |
| w[3,j] | 0.05 | 0.30 | 0.65 | — | — |
| w[4,j] | 0.10 | 0.45 | — | — | — |

Examples: w[1,1] = 0.10 + 0.15 + 0.05 = 0.30; w[1,2] = 0.30 + 0.05 + 0.05 = 0.40; w[1,4] = 0.65 + 0.25 + 0.10 = 1.00.

e-table (cost = min over split + w, root in brackets):

| e[i,j] | j=1 | j=2 | j=3 | j=4 |
|---|---|---|---|---|
| i=1 | 0.45 (1) | 0.75 (1) | 1.50 (1) | **2.40 (3)** |
| i=2 | — | 0.25 (2) | 0.75 (3) | 1.60 (4) |
| i=3 | — | — | 0.45 (3) | 1.20 (4) |
| i=4 | — | — | — | 0.65 (4) |

Sample computations: e[1,1] = e[1,0] + e[2,1] + w[1,1] = 0.10 + 0.05 + 0.30 = 0.45 (root k₁). e[1,3]: r=1 → 0.10 + 0.75 + 0.65 = 1.50; r=2 → 0.45 + 0.45 + 0.65 = 1.55; r=3 → 0.75 + 0.10 + 0.65 = 1.50 → minimum 1.50, take root 1. e[1,4]: r=1 → 0.10 + 1.60 + 1.00 = 2.70; r=2 → 0.45 + 1.20 + 1.00 = 2.65; r=3 → 0.75 + 0.65 + 1.00 = **2.40**; r=4 → 1.50 + 0.10 + 1.00 = 2.60 → minimum 2.40 with root k₃.

**Tree.** root[1,4] = 3 → k₃ is the root. Left range (1,2): root[1,2] = 1 → k₁, with k₂ as k₁'s right child. Right range (4,4): k₄. The tree is shown in Figure 20.

**Cost check.** Expected cost = Σ(depth+1)·pᵢ + Σ(depth+1)·qᵢ = 1(0.15) + 2(0.15) + 3(0.05) + 2(0.25) + 3(0.10) + 4(0.05) + 4(0.05) + 3(0.10) + 3(0.10) = **2.40**. ✔

**Hence the optimal binary search tree has root k₃, left subtree k₁ (with k₂ as its right child) and right child k₄, with minimum expected search cost 2.40.**

## 📝 TEE layer

No past OBST question exists in the archive. The related DP questions (binomial coefficients, all-BSTs counting) remain ⏳ blocked until their lessons are added; nothing is answered by inventing a TEE version here.

---

# Q3(d) — Optimal matrix-chain multiplication (2 marks)
*Assignment p. 5 · Book: Block 3 U2 §2.4, pp. 195–218*

## 🧰 L1. Why order matters — and the DP response

The product A₁A₂…Aₙ is associative, but different parenthesizations cost very different numbers of scalar multiplications. Multiplying a p×q by a q×r matrix costs p·q·r. For four matrices there are Catalan C₃ = 5 orders; for n matrices, Catalan Cₙ₋₁ — so brute force is exponential.

**Principle of optimality (the DP foundation):** an optimal solution to a problem contains optimal solutions to its sub-problems. If the best parenthesization of Aᵢ…Aⱼ splits at r, then the parenthesizations of Aᵢ…Aᵣ and Aᵣ₊₁…Aⱼ must themselves be optimal — otherwise replacing them would improve the whole. Sub-problems overlap (the same range appears inside many larger ranges), so their answers are stored in a table — that is dynamic programming.

## 🧮 L2. The tables

With dimensions p₀×p₁, p₁×p₂, …, pₙ₋₁×pₙ (Aᵢ has size pᵢ₋₁×pᵢ):

> m[i, j] = min_{i ≤ k < j} { m[i, k] + m[k+1, j] + pᵢ₋₁·pₖ·pⱼ },  m[i, i] = 0;
> s[i, j] = the k that achieves the minimum.

```
Algorithm MatrixChainOrder(p[0..n])
    for i ← 1 to n:  m[i, i] ← 0
    for l ← 2 to n:                      # chain length
        for i ← 1 to n − l + 1:
            j ← i + l − 1;  m[i, j] ← ∞
            for k ← i to j − 1:
                q ← m[i,k] + m[k+1,j] + p[i−1]·p[k]·p[j]
                if q < m[i, j]:  m[i, j] ← q;  s[i, j] ← k
    return m, s
```

**Complexity:** three nested loops over n ranges and n splits → **Θ(n³)** time, **Θ(n²)** space.

## 🧪 L3. Worked on A₁ 25×10, A₂ 10×35, A₃ 35×10, A₄ 10×30

Dimensions: p₀ = 25, p₁ = 10, p₂ = 35, p₃ = 10, p₄ = 30.

| m[i,j] | j=1 | j=2 | j=3 | j=4 |
|---|---|---|---|---|
| i=1 | 0 | 25·10·35 = 8750 | **6000** | **13500** |
| i=2 | — | 0 | 10·35·10 = 3500 | 6500 |
| i=3 | — | — | 0 | 35·10·30 = 10500 |
| i=4 | — | — | — | 0 |

Example computations: m[1,3] = min(k=1: 0 + 3500 + 25·10·10 = 6000; k=2: 8750 + 0 + 25·35·10 = 17500) = 6000, s = 1. m[2,4] = min(k=2: 0 + 10500 + 10·35·30 = 21000; k=3: 3500 + 0 + 10·10·30 = 6500) = 6500, s = 3. m[1,4] = min(k=1: 0 + 6500 + 25·10·30 = 14000; k=2: 8750 + 10500 + 25·35·30 = 45500; k=3: 6000 + 0 + 25·10·30 = 13500) = **13500**, s = 3.

**Parenthesization from the s-table:** s[1,4] = 3 → split after A₃: (A₁A₂A₃)(A₄); s[1,3] = 1 → (A₁)(A₂A₃). Final: **((A₁(A₂A₃))A₄)**.

**Cost verification:** A₂A₃ = 10·35·10 = 3500; A₁(A₂A₃) = 25·10·10 = 2500; then ×A₄ = 25·10·30 = 7500. Total = 3500 + 2500 + 7500 = **13,500** scalar multiplications.

![Optimal parenthesization tree](MCS-211_Assignment_Workbook.assets/fig_mcm.png)
*🖼️ Figure 21 — The optimal bracketing ((A₁(A₂A₃))A₄) as a binary tree.*

## ⚠️ Traps
1. Multiplying dimensions in the wrong order when costing a split (the inner dimensions pₖ must match).
2. Filling the table by rows instead of by chain length — sub-results must exist first.
3. Confusing “matrix dimension” with “number of matrices” when indexing p.
4. Forgetting that the first and last dimensions are the output size (25×30 here), needed for the final multiplication cost.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2024 | 3(b) | 10 | Explain DP for MCM; apply to (15×6, 6×50, 50×9, 9×12) | 🔓 unlocked — queued |
| Jun-2025 | 1(g) | 5 | Optimal parenthesization of A(2,4) B(4,5) C(5,3) D(3,5) | ✅ answered below |
| Dec-2025 | 2(a) | 10 | Principle of optimality + MCM | 🔓 unlocked — queued |
| Jun-2026 | 1(e) | 6 | Optimal parenthesization of 10×15, 15×25, 25×8, 8×13 | ✅ answered below |

**Pattern:** MCM appears in **4 of 4** sessions (5, 6, 10, 10 marks) — the single most reliable DP topic. The paper always asks for the **optimal parenthesization of a small chain**, exactly as the assignment does.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q3(d) [2 marks]**
> Given the following sequence of chain multiplication of the matrices. Find the optimal way of multiplying these matrices: A₁ 25×10, A₂ 10×35, A₃ 35×10, A₄ 10×30

*No figure printed in the question; the bracketing tree is Figure 21.*

**Method.** Let m[i,j] be the minimum number of scalar multiplications needed to compute Aᵢ…Aⱼ. The last multiplication splits the chain at some k:

> m[i,j] = min_{i≤k<j} { m[i,k] + m[k+1,j] + pᵢ₋₁·pₖ·pⱼ },  m[i,i] = 0,

with dimension sequence p = (25, 10, 35, 10, 30). The table is filled by increasing chain length.

**m-table:**

| m[i,j] | j=1 | 2 | 3 | 4 |
|---|---|---|---|---|
| i=1 | 0 | 8750 | 6000 | 13500 |
| i=2 | — | 0 | 3500 | 6500 |
| i=3 | — | — | 0 | 10500 |
| i=4 | — | — | — | 0 |

**Key computations.**
- m[1,2] = 25·10·35 = 8750; m[2,3] = 10·35·10 = 3500; m[3,4] = 35·10·30 = 10,500.
- m[1,3] = min(k=1: 0 + 3500 + 25·10·10 = 6000; k=2: 8750 + 0 + 25·35·10 = 17,500) = **6000** (s = 1).
- m[2,4] = min(k=2: 0 + 10,500 + 10·35·30 = 21,000; k=3: 3500 + 0 + 10·10·30 = 6500) = **6500** (s = 3).
- m[1,4] = min(k=1: 0 + 6500 + 25·10·30 = 14,000; k=2: 8750 + 10,500 + 25·35·30 = 45,500; k=3: 6000 + 0 + 25·10·30 = **13,500**) = **13,500** (s = 3).

**Optimal order.** s[1,4] = 3 means the last multiplication joins A₁A₂A₃ with A₄; s[1,3] = 1 means A₁ is multiplied by A₂A₃. Therefore the optimal order is:

> **((A₁(A₂A₃))A₄)** — multiply A₂A₃ first (3500), then A₁ by that result (2500), then multiply by A₄ (7500).

**Total cost = 3500 + 2500 + 7500 = 13,500 scalar multiplications** (the naive orders cost 45,500 or more).

**Hence the optimal multiplication order is ((A₁(A₂A₃))A₄) with 13,500 scalar multiplications.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2025 | 1(g) | 5 | m-table, parenthesization | ✅ answered below |
| Jun-2026 | 1(e) | 6 | m-table, parenthesization | ✅ answered below |
| Dec-2024 | 3(b) | 10 | DP explanation + m-table | 🔓 unlocked — queued |
| Dec-2025 | 2(a) | 10 | principle of optimality + MCM | 🔓 unlocked — queued |

### ✍️ TEE answer — Jun-2026, Q1(e) [6 marks]

**📄 Question — Jun-2026 TEE, Q1(e) [6 marks]**
> Find an optimal parenthesization of a matrix-chain product whose sequence of dimensions is as follows:
> A₁ 10×15, A₂ 15×25, A₃ 25×8, A₄ 8×13

**Dimension sequence:** p = (10, 15, 25, 8, 13); m[i,j] = min_k { m[i,k] + m[k+1,j] + pᵢ₋₁pₖpⱼ }.

| m[i,j] | j=1 | 2 | 3 | 4 |
|---|---|---|---|---|
| i=1 | 0 | 10·15·25 = 3750 | 4200 | 5240 |
| i=2 | — | 0 | 15·25·8 = 3000 | 4560 |
| i=3 | — | — | 0 | 25·8·13 = 2600 |
| i=4 | — | — | — | 0 |

- m[1,3] = min(k=1: 3000 + 10·15·8 = 4200; k=2: 3750 + 10·25·8 = 5750) = **4200** (s=1).
- m[2,4] = min(k=2: 2600 + 15·25·13 = 7475; k=3: 3000 + 15·8·13 = 4560) = **4560** (s=3).
- m[1,4] = min(k=1: 4560 + 10·15·13 = 6510; k=2: 3750 + 2600 + 10·25·13 = 9600; k=3: 4200 + 10·8·13 = **5240**) = **5240** (s=3).

Following the split points: ((A₁(A₂A₃))A₄). Verification: A₂A₃ = 15·25·8 = 3000; A₁(A₂A₃) = 10·15·8 = 1200; ×A₄ = 10·8·13 = 1040. Total = 3000 + 1200 + 1040 = **5240**. ✔

**Hence the optimal parenthesization is ((A₁(A₂A₃))A₄), with 5240 scalar multiplications.**

### ✍️ TEE answer — Jun-2025, Q1(g) [5 marks]

**📄 Question — Jun-2025 TEE, Q1(g) [5 marks]**
> Consider the following four matrices and their dimensions: A(2,4), B(4,5), C(5,3), D(3,5). Find the optimal parenthesization of matrix-chain multiplication A×B×C×D.

**Dimension sequence:** p = (2, 4, 5, 3, 5).

| m[i,j] | j=1 | 2 | 3 | 4 |
|---|---|---|---|---|
| i=1 | 0 | 2·4·5 = 40 | 70 | 100 |
| i=2 | — | 0 | 4·5·3 = 60 | 120 |
| i=3 | — | — | 0 | 5·3·5 = 75 |
| i=4 | — | — | — | 0 |

- m[1,3] = min(k=1: 60 + 2·4·3 = 84; k=2: 40 + 2·5·3 = 70) = **70** (s=2).
- m[2,4] = min(k=2: 75 + 4·5·5 = 175; k=3: 60 + 4·3·5 = 120) = **120** (s=3).
- m[1,4] = min(k=1: 120 + 2·4·5 = 160; k=2: 40 + 75 + 2·5·5 = 165; k=3: 70 + 2·3·5 = **100**) = **100** (s=3).

s[1,4] = 3 → (ABC)(D); s[1,3] = 2 → (AB)(C). Verification: AB = 2·4·5 = 40; (AB)C = 2·5·3 = 30; ((AB)C)D = 2·3·5 = 30. Total = **100**. ✔

**Hence the optimal parenthesization is ((AB)C)D, with 100 scalar multiplications.**

---

# Q3(e) — Knuth–Morris–Pratt string matching (4 marks)
*Assignment p. 5 · Book: Block 3 U3 §3.4, pp. 219–228*

## 🧰 L1. The problem and the naive baseline

**String matching:** find every occurrence of a pattern P[1..m] in a text T[1..n]. The naive algorithm tries every alignment and compares characters left to right; on a mismatch it shifts the pattern by one and **re-reads characters of the text** it has already seen. Its worst case is Θ(n·m) (e.g. T = aaaa…a, P = aaab).

**Read it aloud:** “Slide the pattern under the text and compare; the naive method forgets what a mismatch taught it.”

**Prefix/suffix words, which the LPS array is built from:**

| Word | Plain meaning | Example with P = ababc |
|---|---|---|
| prefix | a block read from the start | “ab”, “aba” |
| proper prefix | a prefix **shorter** than the whole string | “ab” is one; “ababc” is not |
| suffix | a block ending at the last character | “bc”, “abc” |
| proper suffix | a suffix **shorter** than the whole string | “bc” is one; “ababc” is not |
| lps[i] | length of the longest block that is both a proper prefix and a proper suffix of P[1..i] | lps[4] = 2, from “ab” |
| alignment | where the pattern currently sits under the text | “pattern aligned at T[2]” = its first character sits under T[2] |

The point of lps: when a mismatch happens after the first two characters of P matched, the characters already read are not wasted — the pattern knows its own “ab” prefix already matches there, so the next alignment tries that instead of re-reading the text (Q3(e) L2 below shows the jump).

## 🧠 L2. The LPS array and KMP

The **LPS array** (book: “largest prefix as suffix”; standard name *longest proper prefix which is also a suffix*, π) stores, for each position i of the pattern, the length of the longest prefix of P[1..i] that is also a *proper* suffix of P[1..i]. It answers the question: *after a mismatch at P[i], how much of the pattern do we already know?*

```
Algorithm BuildLPS(P[1..m])
    lps[1] ← 0;  i ← 1;  j ← 2
    while j ≤ m:
        if P[i] = P[j]:  lps[j] ← i;  i ← i+1;  j ← j+1
        elif i > 1:      i ← lps[i−1] + 1
        else:            lps[j] ← 0;  j ← j+1
    return lps

Algorithm KMP(T[1..n], P[1..m])
    lps ← BuildLPS(P);  i ← 1;  j ← 1
    while i ≤ n:
        if T[i] = P[j]:  i ← i+1;  j ← j+1
        if j = m+1:      report match at i − m;  j ← lps[m] + 1
        elif i ≤ n and T[i] ≠ P[j]:
            if j > 1:  j ← lps[j−1] + 1
            else:      i ← i+1
```

**The invariant:** the text pointer i **never moves backwards**; only j jumps back to lps[j−1]+1. Every text character is compared at most once more after a shift, which is what makes KMP linear.

## 🧪 L3. Worked example — T = “aababc”, P = “ababc”

| i | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| P | a | b | a | b | c |
| lps | 0 | 0 | 1 | 2 | 0 |

Construction: “a” → 0; “ab” → 0 (no prefix = suffix); “aba” → 1 (“a”); “abab” → 2 (“ab”); “ababc” → 0.

**Search:**
1. Align P at T[1]: T = a **a** b a b c, P = a **b** a b c → mismatch at P₂: T₂ = a, P₂ = b.
2. j = 2, so jump j to lps[1] + 1 = 1 without moving i. Compare P₁ = a with T₂ = a → match; then P₂=b with T₃=b, P₃=a with T₄=a, P₄=b with T₅=b, P₅=c with T₆=c — all match.
3. Report a match at position 2 (T[2..6] = ababc).

The naive algorithm would have re-compared T₂ at alignment 1 and T₃,T₄ again at alignment 2.

![KMP shift after a mismatch](MCS-211_Assignment_Workbook.assets/fig_kmp.png)
*🖼️ Figure 22 — After the mismatch at P₂, LPS[1] = 0 tells KMP to shift the pattern by one while the text pointer stays put.*

**Complexity:** building LPS is O(m); the search advances i at most n times with O(1) amortised work → O(n). Total **O(n + m)** time, O(m) extra space. This is optimal — any algorithm must read the text once.

## ⚠️ Traps
1. Building lps over the pattern **including** the current character — it must be a *proper* prefix (strictly shorter).
2. Moving the text pointer backwards on mismatch (that is the naive method).
3. Off-by-one in the 0-based vs 1-based lps conventions — the book uses 1-based indices.
4. Claiming KMP is O(n·m) — the whole point is the linear bound.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| — | — | — | No archived KMP question | — |
| Jun-2026 | 5(a) | 10 | Rabin-Karp vs naive string matching | ⏳ blocked — needs Rabin-Karp lesson (assignment asks KMP; the paper asked a different matcher) |

**Pattern:** string matching appears in **1 of 4** sessions, and the paper's algorithm (Rabin-Karp) differs from the assignment's (KMP). The KMP lessons here stand on their own.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q3(e) [4 marks]**
> Explain the Knuth Morris Pratt (KMP) algorithm for finding a string in a text/paragraph with the help of an example. Find the time complexity of this algorithm.

*No figure printed in the question; the shift is illustrated in Figure 22.*

**Idea.** The naive matcher shifts the pattern by one and re-compares characters after every mismatch, giving O(nm) worst-case. KMP pre-processes the pattern into an **LPS array** (longest proper prefix that is also a suffix) which records, for each pattern position, how much of the pattern can be reused after a mismatch. The text pointer then never moves backwards.

**LPS construction.** For P = ababc:

| i | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| P[i] | a | b | a | b | c |
| lps[i] | 0 | 0 | 1 | 2 | 0 |

(“a” has no proper prefix; “aba” begins and ends with “a” → 1; “abab” begins and ends with “ab” → 2.)

**Search algorithm.** Keep pointers i (text) and j (pattern). While characters match, advance both. On a mismatch, if j > 1 set j ← lps[j−1] + 1 and keep i fixed; otherwise advance i. When j passes m, a match ends at i − m and the search resumes at j ← lps[m] + 1.

**Example.** T = a a b a b c, P = a b a b c.

| Step | Alignment | Result |
|---|---|---|
| 1 | T: a a b a b c / P: a b a b c | T₂ = a vs P₂ = b → mismatch; lps[1] = 0 → j ← 1, i stays at 2 |
| 2 | compare from T₂: a b a b c vs a b a b c | five matches → pattern found at position 2 |

Unlike the naive method, KMP does not re-compare T₂–T₄; the “ab” prefix of the pattern is known to be already matched, so it is skipped rather than re-read.

**Complexity.** Building the LPS array takes O(m); the search loop advances i at most n times and each comparison either advances i or decreases j, so it is O(n). Total time **O(n + m)** (linear), with O(m) extra space for the LPS array.

**Hence KMP finds all occurrences of a pattern of length m in a text of length n in O(n + m) time by never moving the text pointer backwards.**

---

# Q4(a) — Intractable problems; TSP and Clique (4 marks)
*Assignment p. 5 · Book: Block 4 U1–U2, pp. 229–264*

## 🧰 L1. Tractable vs intractable

A problem is **tractable** if it can be solved by an algorithm whose running time is bounded by a polynomial in the input size — O(nᵏ) for some constant k. A problem is **intractable** if no polynomial-time algorithm is known (and, usually, none is believed to exist): every known algorithm needs super-polynomial time such as 2ⁿ or n!. Intractability is the practical face of the P vs NP question: all NP-complete problems are the standard examples.

**Read it aloud:** “Tractable — solvable in polynomial time; intractable — all known methods blow up exponentially as the input grows.”

**One concrete example of intractability:** the travelling salesman problem. With n cities, a brute-force search examines (n−1)!/2 tours; at n = 20 that is already about 6 × 10¹⁶ tours — centuries of computation — so the problem is intractable by exhaustive search, and no polynomial-time algorithm is known.

## 🚚 L2. Travelling Salesman Problem (TSP)

**Definition (optimisation form).** Given n cities and the distance w(i,j) between every pair, find a **minimum-weight Hamiltonian cycle** — a tour that visits every city exactly once and returns to the start city.

**Definition (decision form).** Given the distances and a bound d, is there a tour of total length ≤ d? This yes/no version is NP-complete.

**Reading the words.** A **Hamiltonian cycle** is a tour that visits every vertex exactly once and returns to the start. “(n−1)!/2 tours” in plain words: fix the starting city (otherwise every tour would be counted n times, once from each starting point), then the remaining n−1 cities can be visited in (n−1)! orders; finally a route and its reverse are the same physical tour, so divide by 2. At n = 20 that is 19!/2 ≈ 6 × 10¹⁶ tours — centuries of computing, which is why brute force is hopeless.

**Example.** Cities A, B, C, D with distances A–B = 2, B–C = 6, C–D = 5, D–A = 3, A–C = 5, B–D = 7. Candidate tours: A→B→C→D→A = 2+6+5+3 = 16; A→B→D→C→A = 2+7+5+5 = 19; A→C→B→D→A = 5+6+7+3 = 21. Optimal tour = A→B→C→D→A with **length 16**. Brute force for general n tries (n−1)!/2 tours.

## 🔵 L3. Clique problem

**Definition.** A **clique** in an undirected graph G = (V, E) is a subset of vertices that are all pairwise adjacent — a complete subgraph Kₖ. The **clique decision problem** asks: does G contain a clique of size at least k? The optimisation version asks for the largest clique (**maximum clique**).

**Example.** In the graph 1–2, 2–3, 1–3, 1–4, 2–4 (Figure 23a), the vertices {1, 2, 3} are all mutually connected, so they form a K₃ clique of size 3; {1,2,3,4} is not a clique because 3 and 4 are not adjacent. Brute force checks all C(n,k) subsets, which is exponential in n.

![Clique, vertex cover and colouring examples](MCS-211_Assignment_Workbook.assets/fig_np_examples.png)
*🖼️ Figure 23 — Running examples for Q4(d): (a) a K₃ clique {1,2,3}; (b) vertex cover {b,c}; (c) a proper 3-colouring.*

## ⚠️ Traps
1. Calling a slow-looking polynomial algorithm intractable — 1000n³ is tractable; 2^(n/1000) is not.
2. Confusing the decision form (yes/no, NP-complete) with the optimisation form (find the best tour/clique) of the same problem.
3. Forgetting that intractability is claimed for **worst-case, all inputs**: a special case can still be easy.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 5(a) | 10 | NP-complete vs NP-hard; state CLIQUE and vertex-cover | ✅ answered in Q4(c) TEE layer |

**Pattern:** intractability itself is asked through the complexity classes (Q4(b)/(c)); TSP and clique appear as the illustrative problems.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q4(a) [4 marks]**
> Explain the term intractable problems with the help of an example. Define the following problems with the help of an example. (i) Travelling Salesman Problem (ii) Clique Problem

*No figure printed in the question; illustration examples are Figure 23.*

**Intractable problems.** A problem is called **intractable** if it cannot be solved by any polynomial-time algorithm; every known method requires time that grows exponentially (or worse) with the input size, so even moderately larger inputs become unsolvable in practice. Intractable problems are exactly the NP-hard problems (assuming P ≠ NP). *Example:* the **travelling salesman problem** — the only known exact method examines all (n−1)!/2 tours, so n = 20 already needs about 6 × 10¹⁶ tours. Polynomial-time algorithms exist only for special cases or as approximations.

**(i) Travelling Salesman Problem (TSP).** Given a set of n cities and the distance between each pair, find a tour that starts at a city, visits every other city exactly once, and returns to the start, with minimum total distance. *Example:* for cities A, B, C, D with A–B = 2, B–C = 6, C–D = 5, D–A = 3, A–C = 5, B–D = 7, the tours have lengths 16, 19 and 21, so the optimal tour is A→B→C→D→A with length 16. Its decision version (“is there a tour of length ≤ d?”) is NP-complete.

**(ii) Clique Problem.** A clique is a set of vertices in an undirected graph that are all pairwise adjacent (a complete subgraph Kₖ). The clique problem asks whether a graph contains a clique of a given size k (decision), or for the largest clique (optimisation). *Example:* in the graph with edges 1–2, 2–3, 1–3, 1–4, 2–4, the vertices {1, 2, 3} form a clique of size 3, while {1, 2, 3, 4} is not a clique because 3 and 4 are not adjacent. The maximum clique problem is NP-hard; checking all C(n,k) subsets is exponential.

**Hence an intractable problem has no known polynomial-time solution; TSP (minimum Hamiltonian tour) and the clique problem (largest complete subgraph) are two standard illustrations, both NP-hard.**

---

# Q4(b) — NP and NP-complete classes (4 marks)
*Assignment p. 5 · Book: Block 4 U1 §1.3, pp. 229–264*

## 🧰 L1. Decision problems, certificates and verification

Complexity classes are defined for **decision problems** (answers “yes” or “no”). A **certificate** is a proposed solution whose correctness can be checked quickly: for TSP the certificate is a tour, and verifying “tour length ≤ d” takes one pass over the edges. A problem is in NP if *yes* instances have a certificate that a **deterministic** verifier can check in polynomial time.

**Symbol/term card — certificate:** read “certificate”; it is the *evidence* that a yes-answer is correct (why it exists: guessing a solution may be hard, but checking one is easy); example: for graph 3-colouring, the certificate is the actual colour assignment, checked edge by edge — any edge whose two ends share a colour fails the check. *If you code:* `verify(input, certificate)`.

## 🧮 L2. The two classes

| Class | Informal meaning | Formal definition |
|---|---|---|
| **P** | problems solvable efficiently | decision problems solvable by a **deterministic** algorithm in polynomial time |
| **NP** | problems whose yes-answers can be checked efficiently | decision problems solvable by a **non-deterministic** algorithm in polynomial time, equivalently: yes-instances have a polynomial-time verifiable certificate |

Every problem in P is in NP (solve it, then verify by comparing), so **P ⊆ NP**; whether P = NP is the most famous open question in computer science.

**Deterministic vs non-deterministic, one line each.** *Deterministic* = follow one instruction at a time, no guessing — the normal kind of algorithm. *Non-deterministic* = a thought experiment in which the algorithm may **guess** the right certificate first and then **check** it step by step; guessing is free, checking must be polynomial. That is the sense in which NP means “easy to check, hard to solve”.

## 🔗 L3. NP-complete and NP-hard

A problem L is **NP-hard** if every problem in NP can be reduced to L in polynomial time (a polynomial-time reduction maps instances of A to instances of B so that solving B solves A). L is **NP-complete** if it is NP-hard **and** in NP. Thus NP-complete = NP ∩ NP-hard: these are the hardest problems *inside* NP. If any one NP-complete problem gets a polynomial-time algorithm, then P = NP and every problem in NP becomes tractable.

**Reduction in plain words (the idea beginners miss).** A reduction is a *translator*: a fast procedure that turns any instance of problem A into an instance of problem B so that both have the **same yes/no answer**. If such a translator exists, then “an algorithm for B” also answers A — translate the question, then run B — so **B is at least as hard as A**. The same trick in daily life: “is this temperature above 100 °C?” can be answered by translating to Fahrenheit and asking “is it above 212 °F?”. Saying B is NP-hard means such a translator exists from **every** problem in NP to B.

**Examples (at least two each, as the question asks):**

| Class | Examples |
|---|---|
| NP | Boolean satisfiability (SAT); Hamiltonian cycle; subset-sum; the decision version of TSP; m-colourability of a graph; 0/1 knapsack (decision) |
| NP-complete | SAT (Cook–Levin theorem); 3-SAT; clique; vertex cover; directed Hamiltonian cycle; TSP (decision); 0/1 knapsack (decision) |

SAT was the first problem proved NP-complete (Cook, 1971); thousands of others are now known. The classic chains are SAT → 3-SAT → clique, 3-SAT → vertex cover, 3-SAT → subset-sum → 0/1 knapsack.

## ⚠️ Traps
1. Saying “NP means non-polynomial” — NP stands for **non-deterministic polynomial**, and P ⊆ NP.
2. Claiming NP-complete problems are definitely unsolvable — they are solvable, just not in known polynomial time.
3. Mixing up NP-hard (need not be in NP) with NP-complete (must be in NP).
4. Forgetting that the classes are defined on **decision** problems; optimisation versions are NP-hard rather than NP-complete.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 1(d) | 5 | What is the NP class? Explain with an example | 🔓 unlocked — queued |
| Jun-2026 | 1(d) | 5 | What is the NP class? Explain with an example | 🔓 unlocked — queued |
| Dec-2025 | 5(a) | 8 | Explain classes P, NP and NP-complete with one example each | ✅ answered in Q4(c) TEE layer |

**Pattern:** the P/NP family appears in **3 of 4** sessions (5, 5 and 8 marks) — a short/medium-slot certainty.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q4(b) [4 marks]**
> What are NP and NP-Complete classes of problems? Explain with the help of at least two examples each.

*No figure printed in the question.*

**NP class.** NP (non-deterministic polynomial) is the class of **decision problems** for which a yes-answer can be *verified* in polynomial time by a deterministic algorithm, given a suitable certificate (the guessed solution). Equivalently, they can be solved by a non-deterministic algorithm in polynomial time, in two stages: a guessing stage that proposes a candidate solution, and a deterministic verification stage that checks it in polynomial time. Every problem in P also lies in NP, so P ⊆ NP.

*Examples of NP problems:* (1) **Boolean satisfiability (SAT)** — given a Boolean formula, is there an assignment of truth values that makes it true? A candidate assignment is verified by evaluating the formula once. (2) **Travelling salesman (decision)** — given the distances and a bound d, is there a tour of length ≤ d? A candidate tour is verified by adding its edge weights. (Also: Hamiltonian cycle, 0/1 knapsack decision, graph m-colourability.)

**NP-complete class.** A problem is NP-complete if it belongs to NP **and** is NP-hard — every problem in NP reduces to it in polynomial time. These are the hardest problems in NP: if any single NP-complete problem is solved in polynomial time, then every problem in NP is (P = NP), and no polynomial-time algorithm is known for any of them.

*Examples of NP-complete problems:* (1) **SAT** (proved by the Cook–Levin theorem) and its restriction **3-SAT**; (2) the **clique problem** — does the graph contain a clique of size k?; (3) the **vertex cover problem** — is there a set of ≤ k vertices covering every edge?; (4) **TSP (decision)** and **0/1 knapsack (decision)**.

**Hence NP contains the decision problems with polynomial-time-checkable certificates, and NP-complete problems are the NP problems to which all of NP reduces — SAT, 3-SAT, clique and vertex cover being the standard examples.**

## 📝 TEE layer

The direct NP-class questions (Jun-2025 1(d), Jun-2026 1(d)) are 🔓 queued; the P/NP/NP-complete question (Dec-2025 5(a)) is answered in the Q4(c) TEE layer below to avoid duplicating the same material twice in this workbook.

---

# Q4(c) — P, NP, NP-complete and NP-hard relationships (4 marks)
*Assignment p. 5 · Book: Block 4 U1–U2, pp. 229–264*

## 🗺️ L1. The four classes at a glance

| Class | Definition | Contains |
|---|---|---|
| **P** | decision problems solvable by a deterministic algorithm in polynomial time | sorting, searching, shortest paths, MST, primality |
| **NP** | decision problems with a polynomial-time verifiable certificate (solvable by a non-deterministic algorithm in polynomial time) | all of P, plus SAT, TSP-decision, clique, … |
| **NP-hard** | problems to which **every** problem in NP reduces in polynomial time | NP-complete problems, halting problem, TSP optimisation |
| **NP-complete** | problems that are both in NP and NP-hard | SAT, 3-SAT, clique, vertex cover, subset-sum |

**Relationships:**
- **P ⊆ NP** (a solved instance is its own certificate).
- **NP-complete = NP ∩ NP-hard** — the intersection region.
- **NP-hard ⊇ NP-complete**, but NP-hard problems need not be in NP (their yes-answers may not be verifiable in polynomial time; indeed the halting problem is undecidable).
- If **P = NP**, then NP-complete = P; if **P ≠ NP**, P and NP-complete are disjoint. Nobody has proved either way.

![Relationships between P, NP, NP-complete and NP-hard](MCS-211_Assignment_Workbook.assets/fig_pnp.png)
*🖼️ Figure 24 — The standard picture (assumed P ≠ NP): P inside NP, NP-complete = NP ∩ NP-hard, and NP-hard extending beyond NP.*

## ⚖️ L2. How they differ

| Basis | P | NP | NP-complete | NP-hard |
|---|---|---|---|---|
| Solvable fast? | yes (deterministic) | verification fast | no polynomial algorithm known | no polynomial algorithm known |
| Verification of yes | polynomial | polynomial | polynomial | not required |
| Reduction direction | — | reduces to NP-hard | every NP problem reduces to it | every NP problem reduces to it |
| Example | shortest path | SAT (yes-check) | 3-SAT, clique | TSP optimisation, halting problem |

## ⚠️ Traps
1. Writing “NP = non-polynomial” — the N stands for non-deterministic.
2. Putting NP-hard inside NP — it may lie outside.
3. Saying an NP-complete problem is “unsolvable” — it is solvable, just not in known polynomial time.
4. Forgetting that reductions run in polynomial time (otherwise the definition is meaningless).
5. Drawing NP-complete outside NP — by definition it is inside.

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Jun-2025 | 5(a) | 10 | NPC vs NP-hard; clique; vertex cover | ✅ answered below |
| Dec-2025 | 5(a) | 8 | Classes P, NP, NP-complete with one example each | ✅ answered below |

**Pattern:** 2 of 4 sessions, 8–10 marks — always definitions + examples + comparison table. The diagrams used by the paper are exactly Figure 24's picture.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q4(c) [4 marks]**
> Define the relationship between P, NP, NP-Complete and NP-Hard classes of problems. How are they different from each other.

*The relationships are drawn in Figure 24.*

**Definitions and relationships.**
- **P:** decision problems solvable by a deterministic algorithm in polynomial time. *Example:* finding a shortest path.
- **NP:** decision problems whose yes-instances can be verified in polynomial time with a certificate. Every P problem is in NP, so **P ⊆ NP**. *Example:* SAT, clique.
- **NP-hard:** problems to which every NP problem reduces in polynomial time. They are at least as hard as every problem in NP, but need not be in NP themselves. *Example:* the optimisation version of TSP, the halting problem.
- **NP-complete:** the intersection — problems that are in NP **and** NP-hard. They are the hardest problems inside NP. *Example:* SAT, 3-SAT, vertex cover.

Relations: **P ⊆ NP**; **NP-complete = NP ∩ NP-hard**; **NP-hard ⊇ NP-complete**. If P = NP then P = NP-complete; if P ≠ NP (widely believed), P and NP-complete are disjoint. Solving any one NP-complete problem in polynomial time would prove P = NP.

**Differences:** P problems are efficiently solvable; NP problems are efficiently checkable; NP-hard problems are not known to be solvable or checkable in polynomial time and may lie outside NP; NP-complete problems are the NP-hard problems that also lie inside NP. In short: P = easy to solve, NP = easy to check, NP-complete = hardest to solve but still easy to check, NP-hard = at least as hard as NP-complete, possibly harder.

**Hence P ⊆ NP; NP-complete = NP ∩ NP-hard; NP-hard can be larger than NP-complete.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Jun-2025 | 5(a) | 10 | NPC vs NP-hard, clique, vertex cover | ✅ answered below |
| Dec-2025 | 5(a) | 8 | P, NP, NP-complete + examples | ✅ answered below |

### ✍️ TEE answer — Jun-2025, Q5(a) [10 marks]

**📄 Question — Jun-2025 TEE, Q5(a) [10 marks]**
> Differentiate between NP-complete and NP-hard problem. State CLIQUE problem and vertex-cover problem.

**NP-complete vs NP-hard.**

| Basis | NP-complete | NP-hard |
|---|---|---|
| Belongs to NP? | yes | not necessarily |
| Every NP problem reduces to it? | yes | yes |
| Verifiable in polynomial time? | yes (it is in NP) | not required |
| Solvable in polynomial time? | no algorithm known (unless P = NP) | no algorithm known |
| Example | 3-SAT, clique, vertex cover | TSP optimisation, halting problem |

So every NP-complete problem is NP-hard, but not every NP-hard problem is NP-complete: NP-complete = NP ∩ NP-hard.

**Clique problem.** A clique is a subset of vertices of an undirected graph that are all pairwise adjacent (a complete subgraph). The decision problem asks: given G = (V, E) and an integer k, does G contain a clique of size k? It is in NP (a certificate is the k vertices; checking all C(k,2) pairs takes polynomial time), and it is NP-complete (3-SAT reduces to it). *Example:* in a graph on {1,2,3,4} with edges 1–2, 2–3, 1–3, 1–4, 2–4, the set {1,2,3} is a clique of size 3; no clique of size 4 exists.

**Vertex-cover problem.** A vertex cover of G = (V, E) is a set S ⊆ V such that every edge of G has at least one endpoint in S. The decision problem asks: given G and an integer k, is there a vertex cover of size ≤ k? It is in NP (a certificate is the set S; checking that every edge touches S is polynomial) and it is NP-complete (3-SAT reduces to it). *Example:* for the path a–b–c–d, the set {b, c} covers edges a–b, b–c and c–d, so it is a vertex cover of size 2; {a, d} is not a cover because edge b–c is untouched.

**Hence NP-complete is the intersection of NP with NP-hard; the clique problem (largest complete subgraph) and the vertex-cover problem (smallest vertex set touching every edge) are both NP-complete.**

### ✍️ TEE answer — Dec-2025, Q5(a) [8 marks]

**📄 Question — Dec-2025 TEE, Q5(a) [8 marks]**
> Explain the class P, NP and NP-complete problem. Give one example for each class.

**Class P.** P is the set of decision problems that can be solved by a **deterministic** algorithm in polynomial time, i.e. in O(nᵏ) steps for some constant k, where n is the input size. These are the problems considered efficiently solvable. *Example:* the sorting problem — sorting n numbers takes O(n log n) — or finding the shortest path in a graph.

**Class NP.** NP (non-deterministic polynomial) is the set of decision problems for which a yes-answer can be **verified** in polynomial time given a certificate. Equivalently, a non-deterministic algorithm can guess a candidate solution and check it in polynomial time. Every P problem is in NP (P ⊆ NP), so NP contains at least all efficiently solvable problems. *Example:* Boolean satisfiability (SAT) — a candidate truth assignment is verified by evaluating the formula; graph 3-colourability — a candidate colouring is checked edge by edge.

**Class NP-complete.** A problem is NP-complete if it is in NP and **NP-hard** — every problem in NP reduces to it in polynomial time. NP-complete problems are the hardest problems of NP: no polynomial-time algorithm is known for any of them, and finding one for a single NP-complete problem would imply P = NP. *Example:* the vertex-cover decision problem, or 3-SAT.

**Hence P ⊆ NP, NP-complete ⊆ NP, and P = NP-complete only if P = NP; shortest path exemplifies P, SAT exemplifies NP, and vertex cover exemplifies NP-complete.**

---

# Q4(d) — 3-CNF SAT, 0/1 Knapsack, Vertex Cover, Graph Colouring (8 marks)
*Assignment p. 5 · Book: Block 4 U1–U3, pp. 229–290*

## 🧰 L1. Four standard NP-complete problems

Each problem below is presented in its **decision form** (the form used for NP-completeness) with a small example. Figure 23 contains the graph examples.

**Boolean words and symbols, read aloud.** A Boolean value is simply **true or false**. **∧** reads “AND” — both sides must be true. **∨** reads “OR” — at least one side is true. **¬** reads “NOT” — it flips the value. A **literal** is a variable (x) or its negation (¬x). A **clause** is literals joined by OR; a formula in **CNF (conjunctive normal form)** is clauses joined by AND. *Tiny example:* (x ∨ ¬y) is true when x is true **or** y is false.

**1. 3-CNF SAT.** A **literal** is a Boolean variable or its negation (x or ¬x); a **clause** is an OR of literals; a formula is in **CNF (conjunctive normal form)** when it is an AND of clauses; it is in **3-CNF** when every clause has exactly three literals. The problem asks: is there a truth assignment that makes the whole formula true? *Example:* (x₁ ∨ ¬x₂ ∨ x₃) ∧ (¬x₁ ∨ x₂ ∨ x₄) ∧ (x₂ ∨ ¬x₃ ∨ ¬x₄). The assignment x₁ = T, x₂ = T, x₃ = F, x₄ = T satisfies all three clauses. 3-SAT is the standard starting point for NP-completeness reductions; SAT was the first NP-complete problem (Cook–Levin theorem).

**2. 0/1 Knapsack.** Given n items with weights wᵢ and profits pᵢ, and a capacity W, choose a subset of items — each item either fully included or not at all — so that the total profit is maximum and the total weight is at most W. The decision form: is there a subset with profit ≥ P and weight ≤ W? *Example (from the earlier MCM data):* W = 10, items (w,p) = (6,30), (5,20), (5,20). Taking item 1 alone gives 30; taking items 2 and 3 gives 20 + 20 = **40** with weight 10 — so the optimum is 40. Note that the greedy “best profit-per-kg first” rule takes item 1 (density 5) and cannot improve, proving greedy fails for 0/1 knapsack; DP (or exhaustive subsets) is needed. It is NP-complete.

**3. Vertex Cover.** A vertex cover of G = (V, E) is a set S of vertices such that every edge has at least one endpoint in S. Decision form: does G have a vertex cover of size ≤ k? *Example (Figure 23b):* for the graph a–b, b–c, a–c, c–d, the set {b, c} covers every edge, so it is a cover of size 2. The optimisation version is the **minimum vertex cover** (NP-hard); the decision version is NP-complete. Application: placing guards/observers so that every road (edge) is watched.

**4. Graph Colouring.** Assign colours to the vertices of a graph so that no two adjacent vertices share a colour. Decision form: can G be coloured with at most m colours? The minimum number of colours needed is the **chromatic number** χ(G). *Example (Figure 23c):* a triangle needs 3 colours; any bipartite graph needs 2; the example graph in the figure can be coloured with 3. Deciding 3-colourability is NP-complete; applications include timetabling (exams ↔ vertices, shared students ↔ edges) and register allocation in compilers.

## ⚠️ Traps
1. Writing “3-CNF” as a formula with clauses of any length — exactly three literals per clause.
2. Applying the fractional-knapsack greedy ratio to 0/1 knapsack (it fails; see the example).
3. Confusing vertex cover (cover edges with vertices) with independent set (no two chosen vertices adjacent) — they are complements.
4. Confusing colouring with edge colouring; here it is **vertices**.
5. Describing the optimisation version as NP-complete rather than NP-hard (the exact decision version is the NP-complete one).

## 🧪 Exam trail

| Session | Q | Marks | What was asked | Status |
|---|---|---|---|---|
| Dec-2025 | 1(g) | 5 | What is the Boolean satisfiability (SAT) problem? | ✅ answered below |
| Jun-2025 | 5(a) | 10 | State clique and vertex-cover problems | ✅ answered in Q4(c) TEE layer |
| Jun-2026 | 1(g) | 4 | Explain the vertex-cover problem | 🔓 unlocked — queued |

**Pattern:** the four named problems appear in **3 of 4** sessions; vertex cover is the most repeated (twice), SAT once. All are short-slot (4–5 mark) definitions.

## ✍️ Assignment answer (full version)

**📄 Question — MCS-211 assignment, p. 5, Q4(d) [8 marks]**
> Describe the following Problems: (i) 3-CNF SAT Problem (ii) 0/1 Knapsack Problem (iii) Vertex Cover Problem (iv) Graph colouring problem

*Illustrations for (iii) and (iv) are in Figure 23.*

**(i) 3-CNF SAT.** A literal is a Boolean variable or its negation; a clause is an OR of three literals; a 3-CNF formula is an AND of such clauses. The satisfiability problem asks whether some assignment of true/false to the variables makes the formula true. *Example:* F = (x₁ ∨ ¬x₂ ∨ x₃) ∧ (¬x₁ ∨ x₂ ∨ x₄) ∧ (x₂ ∨ ¬x₃ ∨ ¬x₄); the assignment x₁ = T, x₂ = T, x₃ = F, x₄ = T makes each clause true, so F is satisfiable. 3-SAT is NP-complete (SAT was the first problem proved so, by Cook and Levin) and is the standard reduction source for other NP-completeness proofs.

**(ii) 0/1 Knapsack.** Given n items, each with weight wᵢ and profit pᵢ, and a knapsack of capacity W, select a subset so that the total profit is maximum and the total weight does not exceed W; each item is either taken whole (1) or left (0) — no fractions. *Example:* W = 10, items (6 kg, 30), (5 kg, 20), (5 kg, 20). Taking both 5-kg items gives 20 + 20 = 40 with weight 10, which beats item 1 alone (30); the optimum is 40. Because the choice is all-or-nothing, the greedy profit/weight method can fail and dynamic programming over capacity is used. The decision version is NP-complete.

**(iii) Vertex Cover.** A vertex cover of an undirected graph G = (V, E) is a subset S of vertices such that every edge of G has at least one endpoint in S. *Example (Figure 23b):* in the graph with edges a–b, b–c, a–c, c–d, the set {b, c} touches every edge, so it is a vertex cover of size 2 (the minimum here); {a, d} fails because b–c is untouched. The decision version (“is there a cover of size ≤ k?”) is NP-complete; the optimisation version is NP-hard. Applications include placing the fewest guards to watch all roads.

**(iv) Graph Colouring.** A proper colouring of a graph assigns a colour to every vertex so that adjacent vertices get different colours. The problem asks for the minimum number of colours (the chromatic number χ(G)), or, in decision form, whether m colours suffice. *Example (Figure 23c):* a triangle (K₃) needs 3 colours; a bipartite graph needs only 2; the graph in the figure is coloured with 3 colours so that no edge joins equal colours. Deciding 3-colourability is NP-complete. Applications include exam timetabling and compiler register allocation.

**Hence the four problems — 3-CNF SAT, 0/1 knapsack, vertex cover and graph colouring — are all NP-complete, and each reduces to the others in the standard NP-completeness chain.**

## 📝 TEE layer — past-paper bank & coverage sweep

| Paper | Q | Marks | Concepts needed | Status |
|---|---|---|---|---|
| Dec-2025 | 1(g) | 5 | SAT definition, CNF/3-CNF, example | ✅ answered below |
| Jun-2026 | 1(g) | 4 | vertex cover definition + example | 🔓 unlocked — queued |

### ✍️ TEE answer — Dec-2025, Q1(g) [5 marks]

**📄 Question — Dec-2025 TEE, Q1(g) [5 marks]**
> What is Boolean Satisfiability (SAT) problem? Explain in detail.

**Definition.** Boolean satisfiability is the decision problem that asks: given a Boolean formula built from variables x₁…xₙ using AND (∧), OR (∨) and NOT (¬), does there exist an assignment of true/false values to the variables that makes the formula **true**? Such an assignment is called a satisfying assignment; the formula is then satisfiable.

**CNF and 3-CNF.** A literal is a variable or its negation. A formula is in **conjunctive normal form (CNF)** if it is an AND of clauses, where each clause is an OR of literals. If every clause has exactly three literals the formula is in **3-CNF**, and deciding its satisfiability is the 3-SAT problem — a special case of SAT that is itself NP-complete.

**Example.** F = (x₁ ∨ ¬x₂ ∨ x₃) ∧ (¬x₁ ∨ x₂ ∨ x₄). Choosing x₁ = T, x₂ = T, x₃ = F, x₄ = T makes the first clause true through x₁ and the second through x₂, so F is satisfiable. If instead all four variables were F, the first clause would fail (F ∨ T ∨ F = T? — with x₂ = F, ¬x₂ = T, so the clause is actually true) — a full truth table over 2ⁿ assignments is needed in the worst case, which is exactly the 2ⁿ search.

**Why it matters.** SAT was the first problem proved NP-complete (Cook–Levin theorem, 1971). Every problem in NP reduces to SAT, so a polynomial-time SAT algorithm would imply P = NP. Its restricted form 3-SAT is the standard starting point for NP-completeness proofs of clique, vertex cover, knapsack and colouring; in practice SAT solvers are used in hardware verification, planning and scheduling.

**Hence SAT asks whether a Boolean formula has a satisfying assignment, is NP-complete, and is the root of the NP-completeness family.**

---

# ✅ Final verification (whole workbook)

| Standard | Check | Result |
|---|---|---|
| Source-grounded | Q1 → Block 1 U1–U4; Q2 → Block 2 U1–U3; Q3 → Block 3 U1–U3; Q4 → Block 4 U1–U3 | ✅ |
| Question-first | All 17 assignment parts and 18 TEE answers embed verbatim question text; every question figure extracted (assignment Fig. 1, Jun-2026/Dec-2024 graph figures) | ✅ |
| Paraphrased | Study blocks are rewritten from the unit, not copied; only short definitions of record are quoted | ✅ |
| Symbol standard | Every new symbol has read-aloud + purpose + example; abbreviations expanded on first use | ✅ |
| Zero-background | 📗 primer teaches pseudo-code, binary, arrays, graphs, logs/Σ once; every symbol used later appears in 📗.7; every algorithm has a read-aloud + tiny trace; code asides optional | ✅ |
| Assignment coverage | Q1(a)–(g), Q2(a)–(e), Q3(a)–(e), Q4(a)–(d) all have full standalone answers with **bold results** | ✅ |
| Numbers verified | 25 primes ≤ 100; 5²³ = 11,920,928,955,078,125; Q2(a) profit 49; Huffman 232 bits/2.32; quicksort 28 comparisons; MST 83; Bellman-Ford (0,18,38,50,8,33,50); OBST 2.40; MCM 13,500; Strassen [[−5,84],[43,3]]; Kruskal TEE 10; MCM TEE 5240 and 100 | ✅ |
| Figures | 24 figures (1–24), all referenced with numbered captions; assets in `MCS-211_Assignment_Workbook.assets/` | ✅ |
| TEE layer | Real past questions only; 23 answered standalone at paper coordinates/marks; remaining direct matches marked 🔓 queued; topics not taught marked ⏳ blocked | ✅ |
| Registry | Every concept listed once with its first-teaching location | ✅ |

**Remaining queue (next pass):** Dec-2024 1(e) binary search · Dec-2024 1(g) Huffman · Dec-2025 1(c) Huffman · Dec-2025 3(b) quicksort · Jun-2025 3(b) Prim · Dec-2025 4(a) Prim · Dec-2025 1(f) Kruskal · Dec-2024 3(b) MCM · Dec-2025 2(a) MCM · Jun-2025 1(d) NP · Jun-2026 1(d) NP · Jun-2026 1(g) vertex cover. **Blocked (needs new lessons):** all merge/bubble sort questions, all Dijkstra questions, Rabin-Karp, all-BST counting, binomial-coefficient DP, Euclid GCD, Horner's method, Floyd–Warshall, BFS/DFS/adjacency questions.





