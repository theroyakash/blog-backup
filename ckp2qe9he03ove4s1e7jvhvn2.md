## Pre order, In order and Post Order Traversal under 2 minutes

Let's don't waste time and finish the "confusing" topic of pre order, post order and in order traversal on binary trees. Most of my friends tell me that they often forget how each traversal works and ask me how to remember them. Well, here you go

When running through a tree (binary or binary search tree) we start from the root. Two things to do

- Add dummy nodes to the end of the leaf (Blue entry point in the image),
- Then after marking those go to the root and start traversing.

![O.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1621867384171/QwkrhQnfK.png)

Now arrange the queue of nodes like this if we visit

- the node for the first time we add that to the pre-order queue,
- the node for the second time we add that to the in-order queue,
- the node for the 3rd time we add that to the post-order queue.

And now you have 3 queues each with pre-in-post order traversal path.

Also make a note that if the binary tree is a binary search tree, then the in-order traversal will give a sorted array. We can use this property to check if the binary tree is a binary search tree or not.

### More on this
To see the proper algorithm on this visit [here](https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/)

Get all the updates directly into your inbox by putting your email below