## Deep dive into the Facebook photo description system

If you wish to listen to this article as audio you can listen to it here

%%[audio-fb]

Facebook recently launched a machine learning system for users who are visually impaired. This service describes photos in a robotic voice and can recognize over 1200 visual concepts.

This system is called automatic alternative text. The system can recognize and explain what’s happening in a picture, including the relative size and position of people and objects, in any of 45 languages.

## How does it work?
In 2016 Facebook launched a similar service that initially learned to describe from 100+ common concepts trained with hand-labeled data like trees, mountains. The following year face recognition was also added with this. This new upgrade to the system extends the previous versions in the following ways
* FB used a weakly supervised approach to train ResNeXt image recognition models on 3.5 billion images and 17000 hashtags that users put with them. Using a similar architecture they applied transfer learning to train linear classification heads to recognize concepts including selfies, national monuments, and foods like rice and French fries.
* They used an existing object detection library to build a Fast R-CNN that recognizes the number, size, and position of various items in an image and determines its primary subject.
* The system starts each description with, “Maybe…,” and it doesn’t describe concepts that it can’t identify reliably. Users can request extra details, and the model will display a page that itemizes a picture’s elements by their position (top, middle, left, or bottom), relative size (primary, secondary, or minor), and category (people, activities, animals, and so on).


## Why it matters?
World health organization estimates there are around 285 billion people who are visually impaired and around 39 million are blind. People who don’t see well are as reliant on information as anyone — and they represent a sizable market. It should be a crime that large internet companies that don’t make their services accessible for everyone. Online accessibility should be recognized as a right, not a privilege.