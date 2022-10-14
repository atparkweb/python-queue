# Review

## Queue
- [ ] Should be able to be initialized with a list
- [ ] Should be able to get length of the queue
- [ ] Should have an enqueue method
  - [ ] Should add item to the right
- [ ] Should have a dequeue method
  - [ ] Should remove and return item from left
- [ ] Should have an iterator that dequeues items until empty

## Stack
- [ ] Should inherit queue methods
  - [ ] Should be able to be initialized with a list
  - [ ] Should be able to get length of the queue
  - [ ] Should have an enqueue method
  - [ ] Should have a dequeue method
  - [ ] Should have an iterator that dequeues items until empty
- [ ] Should dequeue items from the right

## PriorityQueue
- [ ] Should be initialized with an empty list and counter
- [ ] Should be able to get length of the queue
- [ ] Should have an iterator that dequeues items until empty
- [ ] Should have enqueue_with_priority method
  - [ ] Should be able to enqueue an item with priority and value
  - [ ] Should increment the counter
  - HINT: Use heapq.heappush
- [ ] Should have a dequeue method
  - [ ] Should dequeue highest priority item first
  - HINT: Use heapq.heappop
