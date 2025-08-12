# Sorting Visualizer

A simple and interactive **Sorting Algorithm Visualizer** built with React.  
This app visually demonstrates how different sorting algorithms work, step-by-step, using animated bars whose heights represent numbers in an array.

## How It Works
- The array is represented as vertical bars of different heights.
- Each algorithm is implemented to generate a sequence of "animation steps".
- These steps are played back on the screen, changing:
  - **Bar colors** — to indicate which elements are being compared.
  - **Bar heights** — to show the updated values after swaps or merges.
- The animation timing is controlled by `ANIMATION_SPEED_MS`, making the process easier to follow.

The visual effect is powered by **DOM manipulation** and **JavaScript’s setTimeout** to schedule each animation frame sequentially.

## Sorting Algorithms Implemented
Currently, the app supports **Merge Sort** visualization, but more will be added soon.

### Merge Sort
- **Type**: Divide and Conquer
- Splits the array into halves recursively, sorts each half, and merges them.
- Time Complexity: `O(n log n)`

### Other Common Sorting Algorithms (Planned)
- **Quick Sort** — Uses a pivot element to partition the array into smaller and larger parts, then sorts recursively.
- **Heap Sort** — Builds a heap data structure and repeatedly extracts the maximum/minimum to sort the array.
- **Bubble Sort** — Repeatedly swaps adjacent elements if they are in the wrong order.
- **Insertion Sort** — Builds the sorted array one element at a time by inserting elements into their correct position.
- **Selection Sort** — Repeatedly finds the smallest element and moves it to the beginning.

## Contributing
I welcome contributions from other developers! 🚀  
If you’d like to implement new sorting algorithms or improve existing visualizations:
1. Fork the repository
2. Add your algorithm in the animations generator
3. Submit a pull request

Together, we can make this the go-to tool for understanding sorting algorithms visually.
