# CS106B Programming Assignments

## 1 Welcome

Prove we can setup a dev environment and then leverage functions to write some simple programs, culminating in an interesting implementation of the Flesch-Kincaid grade-level readability metric that follows this formula:

   Grade = C0 + C1(num words / num sentences) + C2(num syllables / num words)

Computing syllables is tricky, but some heuristics come to the rescue.

[[code]](2013_spring/01-welcome)

![alt tag](2013_spring/01-welcome/4_flesch_kincaid/grade-level-text.png)

## 2 Collections

Play with vectors, queues, maps, and lexicons to build a word-ladder and a Markov random-writer.

[[code]](2013_spring/02-collections/word_ladder)

![alt tag](2013_spring/02-collections/word-ladder.png)

[[code]](2013_spring/02-collections/random_writer)

![alt tag](2013_spring/02-collections/markov-writer.png)

## 3 Recursion

Several opportunities to apply recursive problem solving.  One involves graphical recursion:

[[code]](2013_spring/03-recursion)

![alt tag](../08-recursion-strategies/readerEx.08.18/screen_shots/sierpinski-triangle.png)

## 4 Boggle

Use recursion with backtracking -and- the lexicon to create a virtually unbeatable Boggle opponent:

[[code]](2013_spring/04-boggle)

![alt tag](2013_spring/04-boggle/boggle-des-1.jpg)

![alt tag](2013_spring/04-boggle/boggle.png)

## 5 Priority Queues

Variations on a theme in implementing some priority queues.  These have wide application and they'll surface in the last two assignments.  One of the flavors we implement is based upon a binary heap:

[[code]](2013_spring/05-priority-queues)

![alt tag](2013_spring/05-priority-queues/pqueue.png)

## 6 Huffman Encoding

![alt tag](2013_spring/06-huffman-encoding/markus-spiske-FXFz-sW0uwo-unsplash.jpg)
Photo by Markus Spiske on Unsplash

Implement a program to compress / decompress any kind of file using Huffman's variable-length, prefix-unique algorithm which ascribes the shortest bit encodings to the most frequently occurring symbols and longer encodings to less frequent symbols.  At the heart of the algorithm are encoding trees that look like this:

[[code]](2013_spring/06-huffman-encoding)

![alt tag](2013_spring/06-huffman-encoding/huffman-encoding.png)

## 7 Graph Algorithms

Finally, wrap up with a really cool least-cost route finding assignment.  We implement Dijkstra's algorithm and an optimized variant called A* Search which applies a heuristic function to guide the exploration of potential paths from A to B:

[[code]](2013_spring/07-graph-algorithms)

![alt tag](2013_spring/07-graph-algorithms/screen_shots/dijkstra-v-astar-hires.png)

Then we apply these two algorithms to finding our way through a maze, after using Kruskal's minimum spanning tree algorithm to build a random maze in the first place.

![alt tag](2013_spring/07-graph-algorithms/screen_shots/kruskal.png)

![alt tag](2013_spring/07-graph-algorithms/screen_shots/maze-runner-hires.png)
