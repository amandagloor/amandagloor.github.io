---
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  ## Site is still under construction 
---

# .append()


`append` is a built-in method in Python that is used to add an element to the end of a list. The `append` method modifies the original list by adding the new element at the end, and returns `None`.   

Here is an example of using the `append` method to add a new element to a list:   

```python
my_list = [1, 2, 3]
my_list.append(4)
print(my_list)   # Output: [1, 2, 3, 4]
```

In this example, we create a list `my_list` containing three elements `[1, 2, 3]`. We then call the `append` method on `my_list` and pass in the value `4`. The `append` method adds the value `4` to the end of `my_list`, and the result is a new list `[1, 2, 3, 4]`.   

The `append` method can also be used to add a list to another list, which concatenates the two lists:   

```python
my_list = [1, 2, 3]
new_list = [4, 5, 6]
my_list.append(new_list)
print(my_list)   # Output: [1, 2, 3, [4, 5, 6]]
```

In this example, we create a new list `new_list` containing three elements `[4, 5, 6]`. We then call the `append` method on `my_list` and pass in `new_list`. The `append` method adds `new_list` as a new element to `my_list`, resulting in a new list `[1, 2, 3, [4, 5, 6]]`.   

Note that the entire `new_list` is added as a single element to `my_list`, since `append` always adds a single element to the end of the list. If we want to add each element of `new_list` to `my_list` individually, we can use the `extend` method instead of `append`.   