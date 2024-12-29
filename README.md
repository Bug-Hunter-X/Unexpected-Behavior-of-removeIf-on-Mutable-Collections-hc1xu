# Unexpected Behavior of removeIf on Mutable Collections in Kotlin

This repository demonstrates a potential source of confusion when using the `removeIf` function with mutable collections (Lists, Maps, Sets) in Kotlin.  The example code highlights how the behavior may differ from what a beginner might intuitively expect.

The key issue is that modifying the collection while iterating over it using `removeIf` can lead to unexpected results or even exceptions in some cases. The code provided illustrates this behavior and offers a solution to avoid these pitfalls.

## How to Run

1. Clone this repository.
2. Open the project in your favorite Kotlin IDE (IntelliJ IDEA is recommended).
3. Run the `main` function in `bug.kt` to observe the unexpected behavior.
4. Then, run the `main` function in `bugSolution.kt` to see the recommended approach.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests if you find any problems or have suggestions for improvement.