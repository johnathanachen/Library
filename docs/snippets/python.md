# Python Snippets

## itertools loop result (without modules)
## match each item in list with all other items in the same list

````python
for i in range(len(ar) + 1): 
        for x in ar:
            print('item %s, matching with %s.'%(ar[i],x))
````

## list of int -> int
### [10] -> 10

```python
int(''.join(str(i) for i in a))
```

## Keep list in the same order when sorting
```python
sorted(set(updated_scoreboard), key=updated_scoreboard.index)
```