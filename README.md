<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=34&duration=4000&pause=1000&color=3B82F6&center=true&vCenter=true&width=900&lines=NeetCode+150+Solutions;Java+DSA+with+Detailed+Explanations;Arrays+%B7+Strings+%B7+Linked+List+%B7+Trees+%B7+Graphs" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/Aman-746/Neetcode-150-Solutions/stargazers">
    <img src="https://img.shields.io/github/stars/Aman-746/Neetcode-150-Solutions?style=for-the-badge&logo=github&color=FFD700&labelColor=111827" alt="Stars"/>
  </a>
  <a href="https://github.com/Aman-746/Neetcode-150-Solutions/network/members">
    <img src="https://img.shields.io/github/forks/Aman-746/Neetcode-150-Solutions?style=for-the-badge&logo=github&color=0E75B6&labelColor=111827" alt="Forks"/>
  </a>
  <a href="https://github.com/Aman-746/Neetcode-150-Solutions/issues">
    <img src="https://img.shields.io/github/issues/Aman-746/Neetcode-150-Solutions?style=for-the-badge&logo=github&color=EF4444&labelColor=111827" alt="Issues"/>
  </a>
  <a href="https://github.com/Aman-746/Neetcode-150-Solutions/commits/main">
    <img src="https://img.shields.io/github/last-commit/Aman-746/Neetcode-150-Solutions?style=for-the-badge&logo=github&color=10B981&labelColor=111827" alt="Last Commit"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aman-kumar-41090a200/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-aman--kumar--41090a200-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:aman04012000@gmail.com">
    <img src="https://img.shields.io/badge/Email-aman04012000@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 📖 Overview

**NeetCode 150 Solutions** is a curated collection of Java solutions for the [NeetCode 150](https://neetcode.io/roadmap) — the essential list of 150 LeetCode problems you need to master to crack coding interviews at top tech companies.

Each solution includes clean, well-commented Java code with time and space complexity analysis.

> 🎯 **Target:** Product-based companies (Google, Amazon, Microsoft, Meta, Netflix, etc.)

---

## 📊 Problem Categories

| Category | Problems | Status |
|----------|----------|--------|
| 🔢 Arrays | Two Sum, Best Time to Buy Stock, etc. | ✅ Solved |
| 🔤 Strings | Valid Anagram, Group Anagrams, etc. | ✅ Solved |
| 🔗 Linked List | Reverse Linked List, Merge Two Sorted Lists, etc. | ✅ Solved |
| 🌳 Trees & Tries | Maximum Depth, Invert Binary Tree, etc. | ✅ Solved |
| 🔄 Graphs | Clone Graph, Course Schedule, etc. | ✅ Solved |
| 🔢 Dynamic Programming | Climbing Stairs, Coin Change, etc. | ✅ Solved |
| 🔢 Intervals | Merge Intervals, Insert Interval, etc. | ✅ Solved |
| 🧮 Stacks & Queues | Valid Parentheses, Min Stack, etc. | ✅ Solved |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | <a href="https://www.java.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="24" height="24"/></a> Java (JDK 17+) |
| **IDE** | IntelliJ IDEA / Eclipse / VS Code |
| **Platform** | LeetCode · NeetCode |

---

## 📁 Project Structure

```
Neetcode-150-Solutions/
├── Arrays/
│   ├── twoSum.java
│   └── ...
├── Strings/
├── LinkedList/
├── Trees/
├── Graphs/
├── DynamicProgramming/
├── StacksQueues/
├── Intervals/
├── Heap/
└── README.md
```

---

## 💡 Sample Solution

```java
// Problem: Two Sum
// Time Complexity: O(n)
// Space Complexity: O(n)

class Solution {
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> map = new HashMap<>();
        for (int i = 0; i < nums.length; i++) {
            int complement = target - nums[i];
            if (map.containsKey(complement)) {
                return new int[] { map.get(complement), i };
            }
            map.put(nums[i], i);
        }
        throw new IllegalArgumentException("No two sum solution");
    }
}
```

Every solution in this repo follows this pattern:
- ✅ Clean, readable Java code
- ✅ Time & Space complexity annotated
- ✅ Edge cases handled
- ✅ Optimized approach

---

## 🚀 How to Use

```bash
# Clone the repository
git clone https://github.com/Aman-746/Neetcode-150-Solutions.git
cd Neetcode-150-Solutions

# Open any .java file in your IDE and run it
# Or compile and run from terminal:
javac Arrays/twoSum.java
java Arrays/twoSum
```

---

## 📈 Progress

- **Total Problems:** 150+
- **Language:** Java
- **Platform:** NeetCode 150 Roadmap
- **Status:** Actively solving

---

## 🔗 Resources

- [NeetCode 150 Roadmap](https://neetcode.io/roadmap)
- [LeetCode](https://leetcode.com)
- [Java Documentation](https://docs.oracle.com/en/java/)

---

## 🤝 Contributing

Feel free to fork this repo and add your own solutions or improvements!

---

## 📞 Contact

**Aman Kumar** — Full Stack Developer | AI Engineer

📧 aman04012000@gmail.com &nbsp;•&nbsp; 📱 +91-7462933412 &nbsp;•&nbsp; 🇮🇳 India  
🔗 [LinkedIn](https://www.linkedin.com/in/aman-kumar-41090a200/) &nbsp;•&nbsp; [GitHub](https://github.com/Aman-746) &nbsp;•&nbsp; [LeetCode](https://leetcode.com/u/amandn/)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Aman-746&repo=Neetcode-150-Solutions&label=Repo%20views&color=0e75b6&style=flat-square&start=2000" alt="Repo views"/>
</p>
