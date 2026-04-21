# 🧩Arrays & Hashing

## 📦Prerequisites ✅

- **Big‑O basics:** array index access `O(1)`, search in array `O(n)`, `dict/set` average lookup/insert `O(1)`.
- **Arrays (Python `list`):** indexing, iteration (`for`, `enumerate`), two pointers, sliding window, prefix/suffix basics.
- **Hashing (`dict` / `set`):**
  - `set` for **existence** checks (duplicates, seen elements).
  - `dict` for **mapping/counting** (value→index, frequency).
  - Know `d.get(key, default)` (common for counting).
- **Common patterns:** frequency counting (anagram), seen set/map (two-sum), grouping by key (group anagrams).
- **Tip:** if keys are limited (like lowercase `a-z`), a fixed array of size `26` can replace a hash map.

## Basic Arrays & Stack

- **Static Array — fixed size, contiguous memory:**

> [!TIP]
> **Interactive visual (Static Array / Dynamic Array / Stack)**  
> Most Markdown viewers block embedded HTML/JS widgets.  
> Use the live preview link below instead:

<p align="center">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/HaRsh-init/DataStructures-and-Algorithms/fixes-arrays-notes/dump/arrays_static_dynamic_stack.html">
    👉 <strong>Open Interactive UI Card</strong>
  </a>
</p>

<sub>If the page doesn’t load, copy the URL and open it directly in your browser.</sub>

## Hashing

- **Hashing — concept, implementation:**

A hash map maps keys to values using a hash function. The function converts a key into an array index (a bucket). When two keys hash to the same index, that is a collision, handled by chaining linked list per bucket or open addressing probe for the next empty slot.

The core power: O(1) average-case insert, delete, and lookup.  
![Dark themed instructional diagram of hash table behavior. Left column labeled Keys shows apple, banana, cherry, and date. Arrows point to a center box labeled hash key percent bucket count. From there, arrows go to a right column labeled Buckets array with bucket 0 mapping to apple, bucket 1 mapping to banana, bucket 2 containing cherry followed by an arrow to date with label collision, and bucket 3 shown as empty with a dash. Bottom text reads Average O1 insert lookup delete - Worst case all collisions On. Overall tone is technical and explanatory, set in a clean interface style.](../dump/image.png)

> [!TIP]
> **Interactive visual (Hashing Pattern)**  
> Most Markdown viewers block embedded HTML/JS widgets.  
> Use the live preview link below instead:

<p align="center">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/HaRsh-init/DataStructures-and-Algorithms/fixes-arrays-notes/dump/hash_pattern.html">
    👉 <strong>Open Hashing Interactive UI Card</strong>
  </a>
</p>

<sub>If the page doesn’t load, copy the URL and open it directly in your browser.</sub>
