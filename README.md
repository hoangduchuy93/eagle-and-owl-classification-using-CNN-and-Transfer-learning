![image](https://user-images.githubusercontent.com/91864024/181451237-d51b1c4d-9fdd-45ef-b1c9-97e7f37909f5.png)

# Eagle and owl classification using CNN
## I. Outline
- People have always been fascinated with owls and eagles, which haven’t changed over time. Both of these are aggressive birds that are known to combat and protect their territory. 
- However, eagles are considerably more powerful and more sturdy than owls. Also, they are larger and weigh more than owls.
- This project will classify two species of eagle and owl using CNN neural network for learning purposes

## II. Business Objective/ Problem
- Assume that you work in the Data Science department of a company that specializes in providing automated solutions, including image classification systems. Your client is currently working on a poultry farm.
- They complain that their animals have been lost due to being taken by large native birds. In the area, only owls and eagles are large native species. They are sure that it can only be due to the eagle because only this species is capable of catching chickens, ducks and lambs. Moreover, owls are more profitable because they hunt mice, helping to protect crops.
- Clients want a system that emits audible and visual warnings (when the eagle appears, it will make a sound and the screen will project an image of a person to scare the bird). This will not happen if the system recognizes it as an owl.
- The Data Science team's task is to find a way to classify these two bird species, then give this model to the audio and visual engineering team for further work.

## III. Project implementation
### 1. Business Understanding
Based on the above description => identify the problem:
- Find methods to classify eagle and owl based on their physical characteristics
- Objectives/problems: build a classification model to classify these 2 species for further purpose.
- Applied method: CNN model
### 2. Data Understanding/ Acquire
- Image data of the above 2 birds are downloaded from many sources for learning purposes
- 5937 images for training and 1340 for testing.

![image](https://user-images.githubusercontent.com/91864024/181462904-35f42152-d0b5-4df2-9250-2ae674516140.png)

### 3. Build model

**Init CNN model**

![image](https://user-images.githubusercontent.com/91864024/181463928-a6a61e7f-31a7-4f49-8010-1453a170b432.png)

**Compile CNN model**

![image](https://user-images.githubusercontent.com/91864024/181464065-a2668e5d-d827-48c6-b00e-c7e10350c46a.png)

**Desclare EarlyStopping and fit model**

![image](https://user-images.githubusercontent.com/91864024/181464185-92b36c08-72b1-4425-9469-a420c6fe8188.png)

![image](https://user-images.githubusercontent.com/91864024/181464236-4babf7f2-737e-4cab-940d-cc3b006090ef.png)

![image](https://user-images.githubusercontent.com/91864024/181464342-8bb14e79-a015-4bd0-b5e3-ad5a4e4758c5.png)

**Save model**

![image](https://user-images.githubusercontent.com/91864024/181464501-1f21369b-f579-4ba8-9fbe-7b00d700728a.png)






















