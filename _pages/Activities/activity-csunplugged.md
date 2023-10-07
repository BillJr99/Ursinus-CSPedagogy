---
layout: activity
permalink: /Activities/CSUnplugged
title: "CS471: Computer Science Pedagogy - CS Unplugged"
excerpt: "CS471: Computer Science Pedagogy - CS Unplugged"

info:
  goals: 
    - To design lessons that explore computing concepts without requiring the use of computing technology
  additional_reading:
    - title: "CS Unplugged Book"
      link: "https://classic.csunplugged.org/documents/books/english/CSUnplugged_OS_2015_v3.1.pdf"
    - title: "CS Unplugged Activities from NCWIT"
      link: "https://ncwit.org/resource/unplugged/"
  guidingquestions:
    - "Brainstorm a series of unplugged activities for your lightning talk topic.  Share with your small group, and choose one activity to design and share with the class."
    
tags:
  - csunplugged
  
---

## Using Kinesthetics: Computer Science Unplugged
Computer Science Unplugged is an educational approach that aims to teach computer science concepts using offline activities. One method of delivering Computer Science Unplugged activities is through the use of kinesthetic learning, which involves incorporating physical movement and actions into the learning process. We will review the concept of kinesthetics and how it can be applied to teaching computer science concepts in an engaging and interactive manner.

### Benefits of Kinesthetics in Computer Science Education
1. **Engagement:** Kinesthetic learning actively involves students in the learning process, enhancing their engagement and motivation. By incorporating movement and physical actions, students are more likely to stay focused and interested in the topic at hand.
2. **Hands-on Experience:** Kinesthetic learning provides students with a hands-on experience that helps them understand abstract computer science concepts more effectively. By physically manipulating objects or acting out algorithms, students can visualize and internalize the underlying principles.
3. **Enhanced Retention:** Studies have shown that kinesthetic learning enhances information retention and retrieval. By engaging multiple senses, such as touch and movement, students create neural connections that improve their memory and understanding of the material.
4. **Active Problem Solving:** Kinesthetic learning encourages active problem-solving and critical thinking. Students are required to analyze, plan, and execute physical movements that mirror the steps involved in solving computational problems. This process improves their computational thinking skills.

### Strategies for Incorporating Kinesthetics in Computer Science Education
1. **Role-playing:** Assigning roles to students allows them to act out algorithms or processes. For example, students can simulate the execution of a sorting algorithm by physically arranging themselves in a specific order.
2. **Physical Manipulation:** Incorporate physical objects, such as cards or tokens, to represent data or variables. Students can then manipulate these objects to understand concepts like binary numbers or sorting algorithms.
3. **Dance and Movement:** Create choreographies or movements that represent computer science concepts. For example, representing the traversal of a graph by physically moving between points in a designated space.
4. **Interactive Games:** Design interactive games that involve physical movement to teach coding concepts. For instance, coding a human robot by giving them instructions for moving around a room.

## Examples of Unplugged Activities

Binary Numbers: Students learn how information can be represented using only 1s and 0s by playing games using cards with bits printed on them.  An example is the [code.org Flippy Do](https://studio.code.org/s/csp1-2022/lessons/4).

Sorting Networks: Students act as shuffle sorters and learn how algorithms can sort data efficiently by physically swapping cards representing numbers into order.  
Students stand in a line with cards that each have a number. They represent the items to be sorted. One student is designated the comparator.
On each round, the comparator looks at the numbers of the first two students in line and swaps their positions if required to put them in sorted order.
The comparator then proceeds down the line, comparing and swapping each pair of adjacent students as needed to incrementally sort the line.
When the comparator passes through the line and no swaps need to be made, the algorithm is complete. The students have enacted an insertion sort algorithm using their own bodies!

Graph Coloring: Using colored pencils and paper graphs, students learn about graph theory, trying to color vertices so no adjacent nodes have the same color.

Minimal Spanning Trees: Students act as computers and pass messages to find the most efficient connections between nodes in a graph. They learn about algorithms for optimization.

Routing and Deadlock: With string and wooden blocks, students model computer networks and learn how routing and deadlock occurs.

Error Detection: Students transmit messages across a room and learn how errors can occur. They add parity bits to detect errors.

Image Representation: Using grids of squares, students learn how images can be represented digitally using various color depths and compression techniques.

Encryption: Using the [CS Unplugged Book](https://classic.csunplugged.org/documents/books/english/CSUnplugged_OS_2015_v3.1.pdf) activity ["Kid Crypto"](https://classic.csunplugged.org/activities/public-key-encryption/), students use a "map" which is a graph with a known vertex cover to encrypt values to one another.

Finite Automata: Using the [CS Unplugged Book](https://classic.csunplugged.org/documents/books/english/CSUnplugged_OS_2015_v3.1.pdf) activity ["Treasure Hunt"](https://classic.csunplugged.org/documents/activities/finite-state-automata/unplugged-11-finite_state_automata-original.pdf), Students draw a representation of a path to hidden treasure, learning about states and transitions on a finite automata.

## Example Activity: Reliable Transport Protocols and TCP

Students are divided into groups representing different computer nodes on a network. One student acts as the router. To start, students just pass notes (packets) to each other via the router. The router sometimes intentionally loses or alters packets.

Students realize they need to add sequence numbers to packets to handle lost ones. The receiver nodes need to acknowledge receipt. Error detecting codes like parity bits are added to handle mutation.

As nodes retransmit lost packets and check for errors, they are simulating core concepts of TCP like sequence numbers, acknowledgements, error detection, and retransmission. 

After running different scenarios with varying rates of packet loss and mutation, the students gain an intuitive understanding of why TCP needs these mechanisms to reliably send data on the unreliable Internet. The activity builds the concepts from the ground up, giving students insight into how TCP/IP protocols work.
