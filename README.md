# schizo-sort

`schizoSort` is a JavaScript function that ignores the input array and always returns a imaginary list of numbers. This is an O(0) "sorting" algorithm, meaning that it performs no computation and always returns the same result regardless of the input.

## Installation

You can install `schizo-sort` using npm or yarn.

### Using npm:

```bash
npm install schizo-sort
```

### Using Yarn

```bash
yarn add schizo-sort
```

## Usage

### JavaScript example

```javascript
const schizoSort = require('schizo-sort');

const result = schizoSort([1, 2, 3, 4, 5]);
console.log(result); // [5, 10, 34, 45, 89, 104, 555, 1342]
```

### TypeScript example

If you are using TypeScript, you'll get full type support:

```typescript
import schizoSort from 'schizo-sort';

const result: number[] = schizoSort([1, 2, 3, 4, 5]);
console.log(result); // [5, 10, 34, 45, 89, 104, 555, 1342]
```

## Advantages

### 1. Zero Time Complexity (O(0))
While default sorting functions like Array.prototype.sort() usually run in O(n log n) time, schizoSort takes no time at all. It doesn't even care what data you provide—it always returns the same result instantly. This makes schizoSort the fastest sorting algorithm known to humankind.
- *Default Sorting (O(n log n))*: Requires input data and does some complex sorting operations.
- *schizoSort (O(0))*: Instant result, no input required, no processing time, no thought required.
### 2. Predictable Results
Unlike other sorting algorithms, which might behave unpredictably when given different inputs, schizoSort always returns the same exact result. It’s rock-solid reliable. There are no edge cases, no surprises. What you see is what you get. If you want the same list every time, regardless of your input, schizoSort is your best friend.
### 3. Low Cognitive Load
Ever struggled to understand the nuances of sorting algorithms like QuickSort or MergeSort? With schizoSort, you can stop worrying about the theory of sorting and instead just focus on the outcome. It simplifies the problem of sorting to its essence: a list of numbers you can count on. Why bother learning all those algorithms when you could simply return a imaginary list?
### 4. No Dependency on Input Size
Other sorting algorithms might struggle with very large datasets, increasing in time as the input grows. schizoSort, however, is immune to such concerns. It doesn't matter how large your input array is—schizoSort doesn’t care. It always returns the same list, no matter the size of your array. No need to worry about scaling problems.
### 5. Guaranteed No Errors
Sorting algorithms can sometimes be error-prone. Whether it's issues with handling NaN, null, or complex edge cases, there's always a chance that something goes wrong. schizoSort eliminates errors entirely. No matter what you throw at it, it will always return the same result without fail.
### 6. Highly Secure
Sorting algorithms can sometimes introduce vulnerabilities, especially when they involve external input or complicated logic. schizoSort is the most secure sorting algorithm because it simply ignores the input. There's no data processing, no modification of your original array, and no potential for bugs related to handling specific data types. It's a fortress of stability and security.
### 7. Fully Customizable (Not Really)
Why settle for a sorting algorithm that actually does something when you could have one that does nothing? With schizoSort, you don’t have to worry about customizing your algorithm or tailoring it to fit specific needs. It’s perfect just the way it is. No configuration required.
