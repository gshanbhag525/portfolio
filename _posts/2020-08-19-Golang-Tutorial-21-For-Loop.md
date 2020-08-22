---
toc: true
layout: post
description: Golang Tutorial for Beginners Tutorial 21.
categories: [golang, beginners]
title: "Golang Tutorial for Beginners Tutorial 21- For Loop"
---

# Golang Tutorial for Beginners Tutorial 21 - For Loop

## Introduction

Hello and Welcome to Golang Tutorial for Beginners. In this Blog Post, We'll take a look at Looping Constructs in Golang.

GO has only one Looping Construct.
The basic for loop has 3 components separated by semicolons.

1. the init statement: executed before the first iteration
2. the condition expression: evaluated before every iteration
3. the post statement: executed at the end of every iteration

The init statement will often be a short variable declaration, and the variables declared there are visible only in the scope of the for statement.

## Simple For Loop

Now let's look at a simple for loop in Golang. This is a standard way of writing a for loop in Golang and you will see this in most of the codebases you will be writing code into.

```
 package main

import "fmt"

func main() {
    // Sum of first 10 whole numbers
	sum := 0
	for i := 0; i < 10; i++ {
		sum += i
	}
	fmt.Println(sum)
}
```
<script src="https://utteranc.es/client.js"
        repo="gshanbhag525/portfolio"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>