---
layout: default
title: Containers
parent: Tutorial
nav_order: 4
---

# Containers

L3 has 2 built-in container types: **collection** and **map**.  
A **collection** only contains elements, while a **map** contains mapping from a key to an element.

Containers can have constraints defined on them. Available constraints are:
- unique elements
- ordered elements

# Container Operations

## first() -> value
Return the first element in the container.

## last() -> value
Return the last element in the container.

## insert_first(value)
Insert a new element before the first element.

## insert_last(value)
Insert a new element after the last element.

## delete_first()
Delete the first element.

## delete_last()
Delete the last element.

## insert(iterator, value)
Insert a new element at a given position.

## delete(iterator)
Delete an element at a given position.


## find(value) -> iterator
Search for an element with a given value.

## insert(value)
Insert an element without specifying position.

## delete(value)
Delete an element with a given value.


# Map-only Operations

## insert(key, value)
Insert mapping from key to element.

## delete(key)
Delete a key and its element.

## lookup(key)
Lookup an element by its key.

**inputs:**
- container variable
- key value
- variable decleration for the found element

**outputs:**
- if found branch
- if not found branch