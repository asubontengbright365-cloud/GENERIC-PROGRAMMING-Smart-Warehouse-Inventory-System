# GENERIC-PROGRAMMING-Smart-Warehouse-Inventory-System 
The lab demonstrates the use of Python Generics using typing.Generic and TypeVar to build reusable, type-safe classes for a warehouse inventory system

##Case Study Activities

### Activity 1: TRIAL - Storage[T]
A generic class that can store and retrieve a single item of any data type.
Demonstrated with:
- int
- str 
- list

### Activity 2: Warehouse Inventory System - Inventory[T]
A reusable generic inventory system for a logistics company that handles different categories of items.
Instead of creating separate classes for each category, one generic Inventory[T] class handles all.

Features:
1. store(item: T) → Store an item of type T
2. retrieve() -> List[T] → Retrieve all stored items 
3. display() → Display item type and all values
 Supports multiple items while maintaining type consistency

Demonstrated with:
1. Inventory[str] → Product Names
2. Inventory[int] → Stock Quantities
3. Inventory[float] → Product Prices
4. Inventory[list] → Batches of Serial Numbers
