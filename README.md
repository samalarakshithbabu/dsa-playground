# DSA Playground

A comprehensive collection of Data Structures and Algorithms implemented in C, Java, and Python with an interactive web-based visualization interface.

---

## What It Does

Educational platform for learning and practicing Data Structures and Algorithms with:
- 12 Data Structures implementations
- 11 Algorithm implementations
- Multi-language support (C, Java, Python)
- Interactive web visualizer
- Unit tests and benchmarks

## Data Structures Implemented

| Data Structure | C | Java | Python |
|---------------|---|------|--------|
| Array / Dynamic Array | ✅ | ✅ | ✅ |
| Singly Linked List | ✅ | ✅ | ✅ |
| Doubly Linked List | ✅ | ✅ | ✅ |
| Stack | ✅ | ✅ | ✅ |
| Queue / Circular Queue | ✅ | ✅ | ✅ |
| Binary Search Tree | ✅ | ✅ | ✅ |
| AVL Tree | ✅ | ✅ | ✅ |
| Red-Black Tree | ✅ | ✅ | ✅ |
| Heap (Min/Max) | ✅ | ✅ | ✅ |
| Hash Table | ✅ | ✅ | ✅ |
| Graph (Adjacency List/Matrix) | ✅ | ✅ | ✅ |
| Trie | ✅ | ✅ | ✅ |

## Algorithms Implemented

| Algorithm | C | Java | Python |
|-----------|---|------|--------|
| Bubble Sort | ✅ | ✅ | ✅ |
| Merge Sort | ✅ | ✅ | ✅ |
| Quick Sort | ✅ | ✅ | ✅ |
| Heap Sort | ✅ | ✅ | ✅ |
| Binary Search | ✅ | ✅ | ✅ |
| DFS (Graph) | ✅ | ✅ | ✅ |
| BFS (Graph) | ✅ | ✅ | ✅ |
| Dijkstra's Shortest Path | ✅ | ✅ | ✅ |
| A* Search | ✅ | ✅ | ✅ |
| Kruskal's MST | ✅ | ✅ | ✅ |
| Prim's MST | ✅ | ✅ | ✅ |

## Project Structure

```
dsa-playground/
├── c/                          # C implementations
│   ├── include/               # Header files
│   ├── src/                   # Source files
│   ├── tests/                 # Unit tests
│   └── Makefile
├── java/                       # Java implementations
│   ├── src/
│   │   ├── datastructures/
│   │   ├── algorithms/
│   │   └── utils/
│   ├── test/
│   └── pom.xml
├── python/                     # Python implementations
│   ├── datastructures/
│   ├── algorithms/
│   ├── tests/
│   └── requirements.txt
├── web/                        # Interactive web visualizer
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── utils/
│   ├── package.json
│   └── vite.config.ts
├── benchmarks/                 # Performance benchmarks
├── docs/                       # Documentation
├── README.md
└── LICENSE
```

## Quick Start

### C Implementation
```bash
cd c
make
./bin/dsa_demo
# Run tests
make test
```

### Java Implementation
```bash
cd java
mvn compile
mvn exec:java -Dexec.mainClass="com.dsa.Main"
# Run tests
mvn test
```

### Python Implementation
```bash
cd python
pip install -r requirements.txt
python -m datastructures.demo
# Run tests
pytest tests/
```

### Web Visualizer
```bash
cd web
npm install
npm run dev
# Opens at http://localhost:5173
```

## Web Visualizer Features

- Interactive step-by-step algorithm execution
- Visual representation of data structure operations
- Complexity analysis display
- Code highlighting for all three languages
- Dark/Light theme support

## Educational Use

Each implementation includes:
- Time and space complexity annotations
- Inline comments explaining key steps
- Unit tests verifying correctness
- Example usage in `demo` or `main` files

## Benchmarks

Run performance comparisons:
```bash
cd benchmarks
python run_benchmarks.py
```
Results show relative performance across languages for each algorithm.

---

## Author

**SAMALA RAKSHITH BABU**  

**Contact:**  
- Email: samalarakshithbabu7@gmail.com  
- LinkedIn: https://www.linkedin.com/in/samala-rakshith-babu/  
- GitHub: https://github.com/samalarakshithbabu  

---

## License

MIT License