![image](https://github.com/user-attachments/assets/e2a3215d-c5b7-48bb-a383-7e9b158cacd6)


# Алгоритмы и Структуры Данных на Go

## 1. Arrays & Hashing (Массивы и хеширование)
Массивы и хеш-таблицы — основа для работы с данными. В Go хеш-таблицы реализуются через встроенный тип `map`.

**Задачи для практики:**
- [Two Sum](https://leetcode.com/problems/two-sum/)
- [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
- [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
- [Group Anagrams](https://leetcode.com/problems/group-anagrams/)
- [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
- [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)
- [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
- [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Majority Element](https://leetcode.com/problems/majority-element/)
- [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)

### 1.1. Two Pointers (Два указателя)
Техника двух указателей помогает эффективно решать задачи с массивами и строками.

**Задачи для практики:**
- [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
- [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [3Sum](https://leetcode.com/problems/3sum/)
- [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)
- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)
- [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
- [Move Zeroes](https://leetcode.com/problems/move-zeroes/)
- [Reverse String](https://leetcode.com/problems/reverse-string/)
- [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)
- [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

### 1.2. Stack (Стек)
Стек полезен для задач, связанных с вложенными структурами, например, скобками. В Go можно использовать слайс как стек.

**Задачи для практики:**
- [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
- [Min Stack](https://leetcode.com/problems/min-stack/)
- [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
- [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)
- [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [Simplify Path](https://leetcode.com/problems/simplify-path/)
- [Basic Calculator](https://leetcode.com/problems/basic-calculator/)
- [Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/)
- [Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/)
- [Car Fleet](https://leetcode.com/problems/car-fleet/)

### 1.3. Binary Search (Бинарный поиск)
Бинарный поиск эффективен для отсортированных данных.

**Задачи для практики:**
- [Binary Search](https://leetcode.com/problems/binary-search/)
- [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)
- [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/)
- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)
- [Find Peak Element](https://leetcode.com/problems/find-peak-element/)
- [Search Insert Position](https://leetcode.com/problems/search-insert-position/)
- [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/)

### 1.4. Sliding Window (Скользящее окно)
Скользящее окно — мощная техника для работы с подмассивами и подстроками.

**Задачи для практики:**
- [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
- [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)
- [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [Permutation in String](https://leetcode.com/problems/permutation-in-string/)
- [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
- [Maximum Number of Vowels in a Substring of Given Length](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/)
- [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
- [Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/)
- [Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/)

### 1.5. Linked List (Связный список)
Связные списки — важная структура данных. В Go их нужно реализовывать вручную.

**Задачи для практики:**
- [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
- [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)
- [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
- [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)
- [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)
- [Rotate List](https://leetcode.com/problems/rotate-list/)
- [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
- [Sort List](https://leetcode.com/problems/sort-list/)
- [Reorder List](https://leetcode.com/problems/reorder-list/)

### 1.6. Trees (Деревья)
Деревья — основа для многих алгоритмов. В Go деревья реализуются через структуры.

**Задачи для практики:**
- [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)
- [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- [Same Tree](https://leetcode.com/problems/same-tree/)
- [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/)
- [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
- [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)
- [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)

### 1.6.1. Tries (Префиксные деревья)
Префиксные деревья полезны для задач с поиском слов и префиксов.

**Задачи для практики:**
- [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)
- [Word Search II](https://leetcode.com/problems/word-search-ii/)
- [Longest Word in Dictionary](https://leetcode.com/problems/longest-word-in-dictionary/)
- [Replace Words](https://leetcode.com/problems/replace-words/)
- [Design Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/)
- [Word Break II](https://leetcode.com/problems/word-break-ii/)
- [Concatenated Words](https://leetcode.com/problems/concatenated-words/)
- [Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/)
- [Shortest Unique Prefix](https://leetcode.com/problems/shortest-unique-prefix/)

### 1.6.2. Heap / Priority Queue (Куча / Очередь с приоритетом)
Кучи полезны для задач с приоритетами. В Go можно использовать `container/heap`.

**Задачи для практики:**
- [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
- [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)
- [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)
- [Task Scheduler](https://leetcode.com/problems/task-scheduler/)
- [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)
- [Reorganize String](https://leetcode.com/problems/reorganize-string/)
- [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/)
- [Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/)
- [Design Twitter](https://leetcode.com/problems/design-twitter/)

### 1.6.2.1. Intervals (Интервалы)
Задачи с интервалами часто связаны с сортировкой и жадными алгоритмами.

**Задачи для практики:**
- [Merge Intervals](https://leetcode.com/problems/merge-intervals/)
- [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
- [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/)
- [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/)
- [Insert Interval](https://leetcode.com/problems/insert-interval/)
- [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)
- [Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/)
- [Employee Free Time](https://leetcode.com/problems/employee-free-time/)
- [Partition Labels](https://leetcode.com/problems/partition-labels/)
- [Teemo Attacking](https://leetcode.com/problems/teemo-attacking/)

### 1.6.2.2. Greedy (Жадные алгоритмы)
Жадные алгоритмы выбирают локально оптимальное решение на каждом шаге.

**Задачи для практики:**
- [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
- [Jump Game](https://leetcode.com/problems/jump-game/)
- [Jump Game II](https://leetcode.com/problems/jump-game-ii/)
- [Gas Station](https://leetcode.com/problems/gas-station/)
- [Hand of Straights](https://leetcode.com/problems/hand-of-straights/)
- [Merge Triplets to Form Target Triplet](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/)
- [Partition Labels](https://leetcode.com/problems/partition-labels/)
- [Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/)
- [Minimum Deletions to Make Character Frequencies Unique](https://leetcode.com/problems/minimum-deletions-to-make-character-frequencies-unique/)
- [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/)

### 1.7. Backtracking (Поиск с возвратом)
Поиск с возвратом полезен для задач, где нужно перебирать все возможные комбинации.

**Задачи для практики:**
- [Subsets](https://leetcode.com/problems/subsets/)
- [Combination Sum](https://leetcode.com/problems/combination-sum/)
- [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)
- [N-Queens](https://leetcode.com/problems/n-queens/)
- [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)
- [Permutations](https://leetcode.com/problems/permutations/)
- [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
- [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/)
- [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/)
- [Word Search](https://leetcode.com/problems/word-search/)

### 1.8. Dynamic Programming (Динамическое программирование)
Динамическое программирование позволяет эффективно решать задачи, которые можно разбить на более простые подзадачи.

**Задачи для практики:**
- [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
- [House Robber](https://leetcode.com/problems/house-robber/)
- [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
- [Coin Change](https://leetcode.com/problems/coin-change/)
- [Word Break](https://leetcode.com/problems/word-break/)
- [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
- [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)
- [Edit Distance](https://leetcode.com/problems/edit-distance/)
- [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/)
- [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/)

### 1.9. Graphs (Графы)
Графы — важная структура данных, особенно для задач, связанных с маршрутизацией и связностью.

**Задачи для практики:**
- [Number of Islands](https://leetcode.com/problems/number-of-islands/)
- [Clone Graph](https://leetcode.com/problems/clone-graph/)
- [Course Schedule](https://leetcode.com/problems/course-schedule/)
- [Word Ladder](https://leetcode.com/problems/word-ladder/)
- [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)
- [Max Area of Island](https://leetcode.com/problems/max-area-of-island/)
- [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/)
- [Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/)
- [Network Delay Time](https://leetcode.com/problems/network-delay-time/)
- [Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)

### 1.10. Bit Manipulation (Битовые операции)
Битовые операции часто используются для задач с числами, где требуется манипуляция битами.

**Задачи для практики:**
- [Single Number](https://leetcode.com/problems/single-number/)
- [Power of Two](https://leetcode.com/problems/power-of-two/)
- [Counting Bits](https://leetcode.com/problems/counting-bits/)
- [Hamming Distance](https://leetcode.com/problems/hamming-distance/)
- [Reverse Bits](https://leetcode.com/problems/reverse-bits/)
- [Missing Number](https://leetcode.com/problems/missing-number/)
- [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
- [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)
- [Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/)
- [Total Hamming Distance](https://leetcode.com/problems/total-hamming-distance/)

### 1.11. Mathematics (Математика)
Математические задачи включают в себя не только простые вычисления, но и более сложные алгоритмы.

**Задачи для практики:**
- [Count Primes](https://leetcode.com/problems/count-primes/)
- [Sqrt(x)](https://leetcode.com/problems/sqrtx/)
- [Multiply Strings](https://leetcode.com/problems/multiply-strings/)
- [Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/)
- [Pow(x, n)](https://leetcode.com/problems/powx-n/)
- [Integer to Roman](https://leetcode.com/problems/integer-to-roman/)
- [Roman to Integer](https://leetcode.com/problems/roman-to-integer/)
- [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Happy Number](https://leetcode.com/problems/happy-number/)
- [Plus One](https://leetcode.com/problems/plus-one/)

### 1.12. String Manipulation (Манипуляции со строками)
Строки играют важную роль в решении множества задач.

**Задачи для практики:**
- [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
- [Anagram](https://leetcode.com/problems/anagram/)
- [String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/)
- [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
- [Ransom Note](https://leetcode.com/problems/ransom-note/)
- [Count and Say](https://leetcode.com/problems/count-and-say/)
- [Length of Last Word](https://leetcode.com/problems/length-of-last-word/)
- [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/)
- [Group Anagrams](https://leetcode.com/problems/group-anagrams/)
- [Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/)

### 1.13. Design (Проектирование)
Проектирование систем и структур данных помогает в решении более сложных задач, связанных с производительностью и масштабируемостью.

**Задачи для практики:**
- [Design HashSet](https://leetcode.com/problems/design-hashset/)
- [Design Linked List](https://leetcode.com/problems/design-linked-list/)
- [Design Queue Using Stacks](https://leetcode.com/problems/design-queue-using-stacks/)
- [LRU Cache](https://leetcode.com/problems/lru-cache/)
- [Design Snake Game](https://leetcode.com/problems/design-snake-game/)
- [Design a Stack With Increment Operation](https://leetcode.com/problems/design-a-stack-with-increment-operation/)
- [Design Hit Counter](https://leetcode.com/problems/design-hit-counter/)
- [Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/)
- [Design Browser History](https://leetcode.com/problems/design-browser-history/)
- [Design Underground System](https://leetcode.com/problems/design-underground-system/)
