## Set-up an audio version of your blog articles [Works Automatically]

If you like the kind of articles I publish and follow my weekly machine learning issues subscribe to my newsletter.

%%[newsletter]

If you want to listen to this article as audio while you read you can do it here

%%[setup-audio]

If you want your blog articles as audio and make them available at the top of your post you can follow my steps. Currently, Hashnode has no support for audio embedding but we'll make it work. If you host your blogging in WordPress or Ghost you can embed an HTML5 Audio player directly into a post. Let's first generate all the audios.

[![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1613025383277/qT41p1MVB.png)](https://github.iamroyakash.com/AKDSFramework-docs/)

Last week I came across a platform called [Send As A Podcast](https://audiblogs.com/). It creates an audio version of the podcast and stores it in an amazon s3 bucket. Now once you've set up your audiblogs account, you need to do these steps to add the audio to your blog post.
- First create a public link for the draft of the blog. Here's how to do this
![Screen Shot 2021-02-10 at 12.13.34 PM.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612939491364/91CN-xfRQ.png)
- Then you need to open the link and send this as a podcast via the audiblogs chrome extension.
- Remember when you set up the audiblogs platform for your chrome you got a link that looks like this `https://rebrand.ly/......`.
- Now open a chrome tab and go to that website. Now you have access to all the articles you've saved with this platform that will look like this
![Screen Shot 2021-02-10 at 12.06.50 PM.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612939016434/2l3_CMA8z.png)
- Now look for the `enclosure URL` tag in the XML file.
![Screen Shot 2021-02-10 at 12.09.13 PM.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1612939158362/gm5JKv1j-.png)
- Copy that `mp3` link, and with that create an HTML5 Widget like this
```HTML
<audio controls>
  <source src="https://s3.us-west-2.amazonaws.com/audiblogs/613be84b-99a8-48e1-864d-0e75fbd74eda.mp3" type="audio/mpeg">
</audio>
```
For hashnode users, until hashnode supports audio embedding in articles you have to create new custom widgets every time and embed the HTML in them or you can just add a link to the audio file at the top of the post. Now enjoy.

## But why tho?
A natural-sounding audio experience can help your blog readers to engage more with a post. If you listen to a post while reading it, your mind can not be distracted from the around the world and you would engage more with the post. An audio experience for an engaging article engages people more with the blogs.