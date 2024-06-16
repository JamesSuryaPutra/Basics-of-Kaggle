# Example of Lists
In the Petal to the Metal competition, your goal is to classify the species of a flower based only on its image (This is a common task in computer vision, and it is called
image classification).

Towards this goal, say you organize the names of the flower species in the data. One way to do this is by organizing the names in a Python string:

    flowers = "pink primrose,hard-leaved pocket orchid,canterbury bells,sweet pea,english marigold,tiger lily,moon orchid,bird of paradise,monkshood,globe thistle"

    print(type(flowers))
    print(flowers)

    <class 'str'>
    pink primrose,hard-leaved pocket orchid,canterbury bells,sweet pea,english marigold,tiger lily,moon orchid,bird of paradise,monkshood,globe thistle


Even better is to represent the same data in a Python list. To create a list, you need to use square brackets ([, ]) and separate each item with a comma.
Every item in the list is a Python string, so each is enclosed in quotation marks:

    flowers_list = ["pink primrose", "hard-leaved pocket orchid", "canterbury bells", "sweet pea", "english marigold", "tiger lily", "moon orchid", "bird of paradise",
    "monkshood", "globe thistle"]

    print(type(flowers_list))
    print(flowers_list)

    <class 'list'>
    ['pink primrose', 'hard-leaved pocket orchid', 'canterbury bells', 'sweet pea', 'english marigold', 'tiger lily', 'moon orchid', 'bird of paradise', 'monkshood',
    'globe thistle']

At first glance, it doesn't look too different, whether you represent the information in a Python string or list. But as you will see, there are a lot of tasks that
you can more easily do with a list. For instance, a list will make it easier to:
1} Get an item at a specified position (first, second, third, etc.)
2} Check the number of items
3} Add and remove items

