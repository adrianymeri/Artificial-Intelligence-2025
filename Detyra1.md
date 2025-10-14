# Detyra 1 - AI - 22/11/2024

## Teknikat e Painformuara të Kërkimit (Uninformed Search Techniques)

### 1. Social Golfers Problem

**Përshkrimi**  
32 lojtarë golfi luajnë golf një herë në javë dhe gjithmonë në grupe me nga 4. Për sa javë mund të luajnë në mënyrë që dy lojtarë të mos luajnë së bashku më shumë se një herë në të njëjtin grup?

A është e mundur të planifikohen n = g × p lojtarë golfi në g grupe p lojtarësh për w javë në mënyrë që të mos luajnë dy lojtarë golfi në të njëjtin grup më shumë se një herë?

**Shembull**  
| Group 1 | Group 2 | Group 3 | Group 4 | Group 5 | Group 6 | Group 7 | Group 8 |
| ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| Week 1  | 0,1,2,3 | 4,5,22,23 | 6,7,20,21 | 8,25,26,27 | 9,10,11,24 | 12,13,15,30 | 14,28,29,31 | 16,17,18,19 |

**Kërkesa e detyrës:** Implemento Depth First Search (DFS), Depth Limited Search dhe Backtracking për zgjidhjen e problemit

### 2. Sudoku Solver

**Përshkrimi**  
Të shkruhet programi i cili e zgjidh një Sudoku. Programi duhet t’i parasheh tri nivele të Sudoku: Easy, Medium, Hard.  
Për më shumë rreth Sudoku: [Kliko këtu](http://www.sudoku-space.com/sudoku.php)

**Kërkesa e detyrës:** Implemento Breadth First Search (BFS) dhe Backtracking për zgjidhjen e problemit

### 3. Latin Square

**Përshkrimi**  
Një katror latin është një grid n x n dimensional, i mbushur me n numra të ndryshëm, secili që shfaqet saktësisht një herë në çdo rresht dhe kolonë. 
Duke pasur parasysh një hyrje n, ne duhet të printojmë një matricë n x n të përbërë nga numra nga 1 në n që secili shfaqet saktësisht një herë në çdo rresht dhe çdo kolonë.

**Shembull:**

**Hyrja:** 5 

**Dalja:**
```1 2 3 4 5 
5 1 2 3 4 
4 5 1 2 3 
3 4 5 1 2 
2 3 4 5 1
```

**Kërkesa e detyrës:** Implemento Iterative Deepeing Depth First Search (IDDFS) dhe Backtracking  
