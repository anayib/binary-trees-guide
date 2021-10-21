# Binary Tress Practical Guide - 101 -

## Who is this for
Programmers who want to understand what a binary tree data structure is, how to create them and when it makes sense to use them.

## Who this is NOT for
Programmers with an advanced understanding of data structures.

| Note: This is a guide in progress. You may find some appendix some topics that have not been developed yet, or even incomplete. This guide is also part of a series of guides on programming foundations and data structures that I will publish and link here in the future.

## Prerequisites
You need to be familiar with writing code in any programming language. I'm using JavaScript to write the code examples - and will add examples in C later -.


## Introduction to Binary Trees

A  tree is a data structure composed by `nodes` and `edges` that connect those nodes.
A node (parent node) can have children nodes.

```
    a (parent of b and c)
   / \
  b   c (children of a)

```
Above a is the parent of `b` and `c`, and `b` and `c` are children of a.

`a` is the root, and `b` and `c` are leaves (leaf). A leaf is a node with 0 children.

```
          a (root)
         / \
        b   c (leaf)
       / \
 leaf d   e (leaf)

```
If we turned aronud the drawing, it would look like a tree.

```
  (leaf) b   c (leaf)
          \ /
           a (root)
```

A binary tree is a type of tree where:

* it has only one root
* Each parent has at most 2 children (0, 1, or 2);
* Theres is just exactly one path between the root and any node.

In JS you can represent each node with an object. The object should have three properties. The value of the node and the values of the right and left children. If the node have 1 or no children, the values of left and right should be assigned to null.


`let a = {value: "a",left:"b, "right: "c" }` this object represent the node `a` from the drawing above.

## Binary Tree Example with Java Script

## An Improved Binary Tree Implementation
