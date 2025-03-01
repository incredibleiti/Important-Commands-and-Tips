
Most algorithm problems fall into common categories. If you can recognize which category a problem belongs to, you can immediately recall similar solutions.


<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Key Clues in the Problem Statement</th>
      <th>Best Approach</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Two Pointers</strong></td>
      <td>
        - Sorted input <br>
        - Remove/modify elements in-place <br>
        - Find a pair or triplet with a condition
      </td>
      <td>Use two-pointer approach (slow & fast pointer)</td>
    </tr>
    <tr>
      <td><strong>Sliding Window</strong></td>
      <td>
        - Subarray / substring problems <br>
        - "Maximum/minimum X in a subarray" <br>
        - Fixed or variable-sized window
      </td>
      <td>Sliding window technique</td>
    </tr>
    <tr>
      <td><strong>Binary Search</strong></td>
      <td>
        - Sorted input <br>
        - "Find the position" / "Find X in log time" <br>
        - Min/max optimizations
      </td>
      <td>Binary Search (O(log n))</td>
    </tr>
    <tr>
      <td><strong>Hashing (HashMap/Set)</strong></td>
      <td>
        - "Find duplicates" / "Find first occurrence" <br>
        - Frequency counting <br>
        - Searching for values quickly
      </td>
      <td>Use <code>unordered_map</code> or <code>unordered_set</code></td>
    </tr>
    <tr>
      <td><strong>Sorting + Greedy</strong></td>
      <td>
        - "Find minimum/maximum X" <br>
        - "Optimize result while processing elements"
      </td>
      <td>Sort first, then use a greedy approach</td>
    </tr>
    <tr>
      <td><strong>Dynamic Programming</strong></td>
      <td>
        - "Find the number of ways to X" <br>
        - "Find the optimal way to X" <br>
        - Overlapping subproblems (previous results help next results)
      </td>
      <td>Use DP with memoization or tabulation</td>
    </tr>
  </tbody>
</table>
