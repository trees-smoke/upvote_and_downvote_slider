# Upvote and Downvote Slider for Minnows

### What Will I Learn?
The Steemit interface gives a vote slider for minnows only when they are over 500SP.

This is also valid for the downvotes.

There are many other interfaces that provide you this ability but if you are interested how to make one for yourself, this is the correct tutorial. 

- Using steem.js API to broadcast upvote or downvote with the desired percentage.
- Make a slider to decide the percentage of the vote.
- Take out the author and permlink from a given steemit post or comment URL in javascript.

### Requirements
No requirement, just a text editor ( notepad is fine ) and any internet browser
Basic javascript knowledge and basic HTML knowledge would help.

### Difficulty
- Basic

### Tutorial Contents
We need four HTML elements for the vote slider 
1- A slider that can take a value between -100 and +100 

![image.png](https://cdn.utopian.io/posts/8b5934f0908e3e75fd2b50c4180be89889faimage.png)

2- An input box where we will paste the URL of the post or comment that we will upvote or downvote

![image.png](https://cdn.utopian.io/posts/a0f761a54e1ed2b28a9b64bcf7a8f3b78a93image.png)

3- A button to complete the action

![image.png](https://cdn.utopian.io/posts/9e946bafbdb77125d21607030a91da0e0141image.png)

4- A message to inform us when the operation is performed

![image.png](https://cdn.utopian.io/posts/e27c0e6d46994d397335f2d0dbb5c287c3b7image.png)
### Complete code
Complete code can be found at GitHub : https://github.com/firedreamgames/upvote_and_downvote_slider/blob/master/upvote_slider.html

![image.png](https://cdn.utopian.io/posts/3356f3f04192303994fed7c72ea8eade3063image.png)

### Step-by-step instructions
* #### Making the input box

![image.png](https://cdn.utopian.io/posts/c9dd832f12ab9f8fdae63c4a9d8d25514efeimage.png)

An HTML element where we paste the URL we copied from SteemIt.

* #### Making the slider

![image.png](https://cdn.utopian.io/posts/44b38be079a769d8bebac521ae530e3f3f3fimage.png)

When the slider value is changed, we send this value to a function ShowValue to display the value selected.

The slider ranges between -100 to +100 allowing downvotes(flags) also.

* #### Making the button

![image.png](https://cdn.utopian.io/posts/c8e6e0ab2efa89b23dde51d32b54b73246a9image.png)

The button, when presses calls the send_vote() function

* #### Making the Elements Function with JavaScript

##### <center> Include steem.js API in the project</center>

![image.png](https://cdn.utopian.io/posts/b3ddc8288e097ada805a56875e934a98a63aimage.png)


##### <center>Make a function to show value of slider</center>

![image.png](https://cdn.utopian.io/posts/f99ab41c65fcaa892dc7eed500413c7d76e0image.png)

##### <center> Build the vote sending fuction</center>

![image.png](https://cdn.utopian.io/posts/5e3571085bc42de3f4e8786fcbc066ca8e40image.png)
Write your Steemit Name without *@* and your posting key in the code.

##### <center>Read the voting weight and URL from HTML</center>

![image.png](https://cdn.utopian.io/posts/f3ac218dfe6ad4adfd519bf3946518d9fffeimage.png)


##### <center>Find author and permlink from URL</center>

![image.png](https://cdn.utopian.io/posts/a8c41dcc608048fd3dae36bf1434c6a0c8e1image.png)

##### <center>Use steem.js API to broadcast the vote and inform user</center>

![image.png](https://cdn.utopian.io/posts/14ea32aeaaafa515d0d3d6b259196509a51cimage.png)

### Contact

@FireDream - Steemit

@firedream#3528 - Discord

