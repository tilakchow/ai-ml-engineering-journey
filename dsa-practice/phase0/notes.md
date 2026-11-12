# Phase 0 Notes

Format per problem (3 lines):
- **Pattern:**
- **Key trick:**
- **Mistake:**

---
Slicing a[start:stop:step]: grabs elements from index start up to (not including) stop, moving step at a time. Negative step reverses direction.
List comprehension [expr for x in iterable if cond]: shorthand for a loop that filters with if and transforms with expr, building a new list in one line.
Mistake: used two separate comprehensions (filter, then square) instead of combining both into one.