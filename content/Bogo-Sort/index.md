---
title: "Bogo Sort"
description: "For my data structures and algorithms class, our last assignment is to understand the differences of sorting algorithms. There are 6 main types that we need to be able to distinguish which are ‘quick…"
date: "2016-12-04T05:28:19.564Z"
categories: 
  - Programming
  - JavaScript

published: true
canonicalLink: https://medium.com/@5tigerjelly/bogo-sort-b7d3656d6cd8
---

For my data structures and algorithms class, our last assignment is to understand the differences of sorting algorithms. There are 6 main types that we need to be able to distinguish which are ‘quick sort’, ‘merge sort’, ‘insertion sort’, ‘shell sort’, ‘heap sort’, and ‘selection sort’.

The main take away from this is, how good the sorting algorithm is, will can never get better than O(Nlog(N)) runtime. While learning about interesting sorts like bucket sort and regex sort, there was one really interesting sorting method called ‘bogo sort’. The key feature is, the program randomizes the order of elements until the ordered set is found. The runtime of this method is O(N!). I was reading about this sorting algorithm, and thought to myself, ‘who would create this most stupid way of sorting?’ This is obviously very time consuming way to order. But something amazing I learned a bit later is that, in current computers, it is O(N!) runtime, however, in quantum computers the runtime is actually O(1). The crazy reason behind this is because, in quantum computers, the sort is run in every variation simultaneously. The fact that the most slowest method turns out to be the fastest way to compute in future machines is pretty amazing.

Hiep Can is a friend which I am hoping to start a [small project](https://medium.com/@5tigerjelly/photo-merging-algorithm-6cc98ae64f55#.z4j9xjcps) starting this Winter break. While I was in talks about the project, I was a bit hesitant that he might not like the idea, or think that the idea is stupid. What he told me changed how I think, that ‘there are no bad ideas’.