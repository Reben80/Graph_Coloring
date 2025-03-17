# Activity: Exploring Graph Coloring through Play and Challenges

**Objective:** To deepen understanding of graph coloring by interactive play and progressively challenging problems.

---

## Introduction

Begin by having the students **play with the online graph coloring game** at:

[Graph Coloring Game](https://reben80.github.io/chromatic-number-new-/)

- **Instructions:**
  - Explore the game by attempting to color various graphs with the smallest number of colors.
  - Try to solve all the challenges provided in the game.
  - Pay attention to how the number of colors relates to the structure of the graph.

This interactive experience will provide a hands-on understanding of graph coloring concepts and prepare them for the subsequent challenges.

---

## After the Game: Deeper Exploration

### Step 1: Recall Graph Coloring Basics

- **Definition:** In a graph, a proper vertex coloring assigns colors to each vertex such that no two adjacent (connected) vertices share the same color.
- **Chromatic Number (χ):** The smallest number of colors needed to properly color a graph.

---

### Step 2: Investigate Small Graphs

Ask the students to observe chromatic numbers in small graphs:

1. **Graph with 1 Vertex (V = 1):**
   - **Edges (E):** 0
   - **Chromatic Number (χ):** 1

2. **Graph with 2 Vertices (V = 2):**
   - **If connected (edge between them):**
     - **Chromatic Number (χ):** 2

3. **Graph with 3 Vertices (V = 3):**
   - **Triangle (each vertex connected to the other two):**
     - **Chromatic Number (χ):** 3

---

### Step 3: Identify the Pattern

- **Observation:** In a complete graph, the chromatic number equals the number of vertices.
- **Complete Graph (Kₙ):** A graph where every pair of distinct vertices is connected by a unique edge.

---

### Step 4: Generalize the Concept

- **Conclusion:** A graph where the chromatic number equals the number of vertices is a **complete graph**.
- **Reasoning:** Each vertex is adjacent to every other vertex, so each must have a unique color.

---

### Step 5: Draw and Analyze

Have the students:

1. **Draw Complete Graphs for V = 4, 5, 6:**
   - Label vertices and connect every pair of vertices.

2. **Attempt to Color with Fewer Colors:**
   - Try to color the graph with fewer colors than vertices and observe conflicts.

3. **Discuss Why It's Impossible:**
   - Emphasize adjacency requiring different colors.

---

### Step 6: Extend the Exploration

- **Non-Complete Graphs:** Find graphs where the chromatic number is less than the number of vertices.
  - **Example:** A bipartite graph or a cycle graph with an even number of vertices.

- **Real-World Applications:** Discuss applications like scheduling, map coloring, and frequency assignment.

---

# 10 Challenge Questions on Graph Coloring

After playing the game and exploring basic concepts, challenge the students with the following problems:

---

## Challenge 1: Basic Coloring

**Question:** Draw a simple graph with 4 vertices that can be properly colored using only 2 colors. What kind of graph is this?

**Hint:** Think of a square or a cycle graph with 4 vertices.

---

## Challenge 2: Coloring a Cycle Graph

**Question:** Consider a cycle graph with 5 vertices. What is the minimum number of colors needed to color this graph properly?

**Hint:** Observe the parity of the cycle (odd number of vertices).

---

## Challenge 3: Understanding Bipartite Graphs

**Question:** Explain why any bipartite graph can be colored using only 2 colors, regardless of the number of vertices.

**Hint:** Bipartite graphs have vertices divided into two sets with edges only between sets.

---

## Challenge 4: Complete Graph Coloring

**Question:** How many colors are needed to properly color a complete graph with 4 vertices (\( K_4 \))? Draw the graph and show your coloring.

**Answer:** 4 colors, because each vertex is connected to every other vertex.

---

## Challenge 5: Chromatic Number Exploration

**Question:** Find a graph with 6 vertices that requires exactly 3 colors to be properly colored. Describe or draw your graph.

**Hint:** Think of two interconnected triangles.

---

## Challenge 6: Coloring Planar Graphs

**Question:** According to the Four Color Theorem, any planar graph (a graph that can be drawn on a plane without edges crossing) can be colored using at most 4 colors. Can you draw a planar graph with 5 vertices that requires exactly 4 colors?

**Hint:** Consider the complete graph \( K_5 \) minus one edge, making it planar.

---

## Challenge 7: Graph with Chromatic Number Less Than Clique Number

**Question:** Can you find a graph where the chromatic number is less than the size of its largest complete subgraph (clique)? Draw the graph and explain.

**Hint:** Construct a graph with a large clique embedded in a structure that reduces the overall chromatic number.

---

## Challenge 8: Trees and Coloring

**Question:** Prove that any tree can be properly colored using only 2 colors, regardless of its size.

**Hint:** Use induction or consider the properties of acyclic graphs.

---

## Challenge 9: Graph Coloring and Map Coloring

**Question:** Is it possible to draw a map such that the corresponding graph requires 5 colors to be properly colored? Explain your reasoning.

**Answer:** No, due to the Four Color Theorem, any planar graph (and thus any map) can be colored with at most 4 colors.

---

## Challenge 10: Chromatic Number and Graph Properties

**Question:** Create a graph with 7 vertices that has a chromatic number of 4. Explain the properties that necessitate the use of 4 colors.

**Hint:** Incorporate an odd cycle or a complete subgraph of 4 vertices (\( K_4 \)).

---

# Additional Tips for Students

- **Engage with the Game:** Reflect on strategies used in the online game and how they apply to these challenges.
- **Draw and Experiment:** Visualizing the graphs will aid in understanding.
- **Collaborate:** Discuss your approaches with peers.
- **Explore Variations:** Modify graphs to see how changes affect the chromatic number.

---

By integrating interactive play with these challenges, students will build a solid foundation in graph coloring concepts and develop problem-solving skills in graph theory.
