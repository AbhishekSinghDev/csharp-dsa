# DSA with C\#

This repository tracks my Data Structures and Algorithms journey using C#.

I already have software engineering experience and mainly come from a TypeScript and Node.js background, so this repository focuses on:

- Learning C# concepts relevant to DSA
- Understanding the .NET collections ecosystem
- Implementing core data structures manually
- Practicing common operations and algorithms
- Building a strong understanding of time and space complexity

## Environment

- OS: Linux Mint
- Language: C#
- Runtime: .NET 10
- Editor: Any C# compatible editor
- Version Control: Git and GitHub

## Repository Structure

```text
dsa-csharp/
│
├── README.md
├── .gitignore
├── Dsa.sln
│
├── 01-csharp-basics/
│
├── 02-arrays/
│
├── 03-strings/
│
├── 04-singly-linked-list/
│
├── 05-stack/
│
├── 06-queue/
│
├── 07-hashing/
│
├── 08-trees/
│
├── 09-heaps/
│
├── 10-graphs/
│
└── 11-algorithms/
```

Each exercise will generally have its own small console project.

Example:

```text
02-arrays/
└── 01-traverse-array/
    ├── TraverseArray.csproj
    └── Program.cs
```

## Running a Project

From the repository root:

```bash
dotnet run --project 02-arrays/01-traverse-array
```

Build the entire solution:

```bash
dotnet build
```

## C# Foundation

- [ ] Types and variables
- [ ] Value types vs reference types
- [ ] Arrays vs `List<T>`
- [ ] Methods and parameter passing
- [ ] `ref` and `out`
- [ ] Classes and objects
- [ ] Generics
- [ ] Collections
- [ ] Equality and hashing
- [ ] Common collection complexities

## Arrays

- [ ] Traverse array
- [ ] Insert element at index
- [ ] Delete element at index
- [ ] Update element
- [ ] Linear search
- [ ] Find minimum and maximum
- [ ] Reverse array
- [ ] Find second largest
- [ ] Count frequency of elements
- [ ] Remove duplicates from sorted array

## Strings

- [ ] Traverse characters
- [ ] Reverse string
- [ ] Check palindrome
- [ ] Count character frequency
- [ ] Check anagram
- [ ] Find first non repeating character
- [ ] Remove duplicate characters

## Singly Linked List

- [ ] Insert at beginning
- [ ] Insert at end
- [ ] Insert at position
- [ ] Delete first node
- [ ] Delete last node
- [ ] Delete by value
- [ ] Search value

More topics will be added as I progress.

## Approach

For each topic, the goal is to understand:

1. How the data structure works
2. How to implement it manually
3. How C# provides similar functionality through built in collections
4. Time complexity
5. Space complexity
6. Common edge cases

For example, when learning dynamic arrays, I will compare a manual implementation with:

```csharp
List<int>
```

When learning hash tables, I will compare the implementation with:

```csharp
Dictionary<TKey, TValue>
HashSet<T>
```

## Notes

LINQ may be used occasionally for comparison, but core DSA exercises will generally be implemented without relying on LINQ so the underlying algorithm remains clear.

The goal of this repository is understanding, not writing the shortest possible solution.
