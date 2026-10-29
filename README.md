# search-insert-position
Uses Binary Search. Pointers l and r narrow down the search range. If target matches nums[mid], return its index. If target is greater, move l right; otherwise, move r left. If not found, l points directly to the correct insertion index. Time: $O(\log n)$.
