# CMPS 2200 Recitation 6
## Answers

**Name: Shira Rozenthal and Zachary Wiel**


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

|        File | Fixed-Length Coding |       Huffman Coding |  Huffman vs. Fixed-Length |
|-------------|---------------------|----------------------|---------------------------|
|       f1.txt|                1340 |                  826 |                  0.616418 |
|  alice29.txt|             1039367 |               676374 |                  0.650756 |
| asyoulik.txt|              876253 |               606448 |                  0.692092 |
| grammar.lsp |               26047 |                17356 |                  0.666334 |
|    fields.c |               78050 |                56206 |                  0.720128 |





- **e.**

In this situation, all frequencies are equal to one another. The Huffman coding cost would therefore be the product of this frequency and the encodings’ lengths, resulting in a balanced tree. For a tree of n leaves, the cost would be n log n — and this hold true across documents.  
