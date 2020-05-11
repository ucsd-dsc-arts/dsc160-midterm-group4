# Project Title

DSC160 Data Science and the Arts - Midterm Project Repository - Spring 2020

Project Team Members: 
- Kaixin Huang, k3huang@ucsd.edu
- Xingyu Jiang, xij080@ucsd.edu
- Yicen Ma, yim095@ucsd.edu
- Chang Yuan, chy238@ucsd.edu
- Michael Kusnadi, mkusnadi@ucsd.edu

## Abstract

(10 points) 

For the project proposal, please write a short abstact addressing the questions below. You should replace the entire contents of this section with one to two paragraphs addressing the following:

  In this project, we are going to analyze Vincent Van Gogh artworks from the wikiart.org with 1931 artworks. Vincent Van Gogh was a dutch post-impressionist painter who is still one of the most influential and famous figures in art. It is known that his art style, especially his self portraits, changed drastically due much to his mental health. As context, Van Gogh was mostly unsuccessful in his life and art. He became depressed as he was an art dealer that was unable to truly rise up and become famous. He only became famous after his suicide and we see that his art style changed drastically due to his failing mental health at that time. We would like to study this change as we feel that it is an important and significant topic. Culturally, due to Van Gogh being such a famous figure,  he and his art has affected both the art style (post-impressionism) and art in general. We have all seen Van Gogh’s art and know who he is, now if we are able to study his mental health through his art and depict it, we can see how psychology is able to affect art. This is important as art carries an emotional weight and is able to affect our mood and atmosphere. Personally we are also able to further understand why some paintings are more dark than others, or if they affect us on a deeper level and give us a certain feeling. Our research question is with the differences shown in Van Gogh artworks, what can we know about his experiences and emotions in his life by creating a timeline of his artworks. The hypothesis for this project is that Vincent Van Gogh’s artworks are correlated with his personal experiences and emotions in the process of time.
  
  We are going to analyze features such as brightness, hue, rgb values (different kinds of colors), saturation, whether there are people in an artwork by using face detection, and edges in each painting to address our question. We will scrape Van Gogh’s artworks from the wiki art website. Then, we will use face detection and basic image features methods to see whether there exists any differences in Van Goph’s artworks in different time periods. Furthermore, we can get the image width, image height, mean hue, mean saturation, mean brightness, resolution, RGB values and edge counts which we will use in our analysis (ie. calculate the number of colors that exist in Van Gogh’s artworks). The analytic techniques we’ll use are histogram, scatter plot, bitmap, and line chart using bokeh. We can plot the brightness, hue, resolution to get the distribution of those values we need and find the relationship between 2 features. As a result, we will create a bitmap to show the trend for Van Gogh’s artworks in a certain period or a time series graph plotting Van Gogh’s artworks over time. We will use the techniques we learned from class to extract the features of each painting. As we find different transformations in his paintings, we look up his personal experiences. In this project, we attempt to seek out his emotional presentation in his artworks through analyzing features. 


## Data

(10 points)

Data Source:

“Vincent Van Gogh - 1931 Artworks - Painting.” www.wikiart.org, www.wikiart.org/en/vincent-van-gogh/all-works#!#filterName:all-paintings-chronologically,resultType:masonry.

  In this project, we are trying to analyze the scan paintings by Vincent van Gogh artworks from (1862 - 1890) throughout his life (1853 - 1890) with respect to its correlation to his experiences. We are using images of all of Vincent van Gogh’s paintings in his lifetime from Wikiart.org. To understand the analysis we are going to do, we need to firstly know Vincent van Gogh’s life and the style and genre of his paintings (both the early ones and later ones). 
  
  Born in a religious family, Van Gogh is affected by the environment he grew up in and became a Protestant missionary after his education in schools. He preached to the poor coal miners in a coal mine in southern Belgium where preachers were sent as punishments. But van Gogh did it voluntarily. During that time, he drew about the miners and their families, along with some landscapes and things he saw around him. After this time period of his life, he went to art school to start learning art formally and then started his career as a painter in 1880 in Brussels, where he studied art. In 1886, he moved to Paris and was affected by Impressionism and post-impressionism, which contributed to the style change to his paintings. However, his paintings were seldom noticed or liked by people in his time. Along with his suffering from psychotic episodes and delusions, he gradually became depressed. His drinking problem and lack of income made him more moody. After an argument with his friend, he cut off his left ear. Even though recovered after some time, he still suffered from loneliness and depression, which partially led to his suicide in 1890, with an age of 37 years old.
  
  Vincent van Gogh’s style is seen as post-impressionism. According to Wikipedia, “Post-Impressionists extended Impressionism while rejecting its limitations: they continued using vivid colours, often thick application of paint, and real-life subject matter, but were more inclined to emphasize geometric forms, distort form for expressive effect, and use unnatural or arbitrary colour”. In this project, we are going to analyze van Gogh’s paintings’ colors and other elements that potentially show his emotions in relation to the time of the paintings and his personal experiences.
  
  This idea is inspired by an academic research about the relation between colors and emotions by Sevinc Kurt and Kelechi Kingsley Osueke. The research is trying to find out the effects colors have on people’s mood and the psychological reasons behind. It is explained that different colors have different wavelengths when struck by light to the human eyes, causing different perceptions. This is the reason for the effects of colors on emotions. This gives us the inspiration to study the color in Vincent van Gogh’s paintings and the emotions within them. The emotions van Gogh wanted to deliver through his painting are also related to the emotions he had when drawing those paintings. In our project, we will analyze how van Gogh’s artworks are affected by his experience and therefore emotions and how they are shown in his paintings.


## Code

https://github.com/ucsd-dsc-arts/dsc160-midterm-group4/blob/master/code/DSC160%20project1%20%20(4).ipynb


## Results

https://github.com/ucsd-dsc-arts/dsc160-midterm-group4/blob/master/results/Result-dsc160-2.pdf

## Discussion

After plotting out the different characteristics of the paintings that Van Gogh had painted throughout his life, it can be seen from the results that his paintings and their characteristics depicted different stages of his life. The use of color and hue was able to depict his mental state and the difficulties or joys that Van Gogh faced through his life and chose to express through his paintings. For example, from the bitmap, we can clearly notice the changes in variables like energy, saturation and etc to show the difference between his mental state. Like when his mental state was healthy, he drew most sketches and not so many colored paintings. But we can clearly notice that when his mental state was not healthy, nearly all of his paintings were oil paintings or watercolor paintings, which shows high energy, high brightness etc. 

Art is everywhere, through this we are able to see how art is able to affect or show a certain emotional state that a person is in or is trying to convey. The use of colors and such are universal and thus through this we are then able to understand more artworks in a deeper manner. We are then able to also see deeper into what is currently present in our culture how artists are able to use colors and figures to show what they want and bring out certain emotions out of the viewers. Then there is also the fact that Van Gogh is one of the most prominent artists to have ever lived and understanding his artwork and his life more may bring a new light to understanding this artist. Looking further into the context at which these paintings were made and also reasons why he did certain things will bring people to understand more the person that he was.

Furthermore, analyzing Van Gogh’s artworks,especially the later ones, helps understanding post-impressionism much more. As we introduced in the background information part, the characteristics of post-impressionism is the use of vivid color and geometric shape to achieve expressive effect. As we can see in Van Gogh’s paintings and his life, the color usage and subject depiction is varying as he stepped into different phases of his life and encountered different incidents. For example, we can see major differences between The Starry Night and the Sunflowers. These two are in completely different styles, both in color and shape. The Starry Night uses dark themes and unrealistic shapes of the sky to reflect his fight with illness, while the Sunflowers uses bright themes and realistic shapes to show his gratitude to his friends, or some may say, hope. In fact, most of his later paintings are representatives of post-impressionism which are great treasures for people after him to admire and learn.

Compared to the more subjective traditional criticism that artforms usually receive, the computational approach done through this study is able to pinpoint exactly the characteristics that each artform has and is able to bring connections in a time series analysis manner. The way art is traditionally critiqued is through composition, and usually they are able to understand the artwork by asking questions such as how the artist made it, how the color compositions and lines bring about certain emotions and such. These change based on the viewer, while our study simultaneously studies all Van Gogh’s artworks at one time and compares them through time and each variable such as hue, saturation, brightness and more. Without the aid of this computational approach it would be impossible to calculate these things accurately, especially variables such as edges within an artwork. Furthermore, we are able to give an analytical and constant appraisal of these artworks, that bring about a more objective analysis. 

It would be difficult to fully infer the response that Van Gogh would have given to this analysis given the conditions of his time but it would be certainly insightful. With this study, he would have been able to fully understand the characteristics of each artwork that he did and maybe he could have used it as self reflection and also change the way he chose to use certain colors or depict certain things. Although this is so, maybe due to his way of perceiving art and the way everybody did back then, he would simply think that this study is not as helpful because art is an expression and it cannot simply be quantified. Artists in general are more inspired by feelings and emotions rather than facts and analytical figures so this would certainly clash with his viewpoints and could be disagreed upon. Although this is true, he could certainly gain certain benefits by understanding what his arts truly contain and it could be used as a means to explore new ways or techniques for him during that time. 

Humans psychologically like art, we like hearing, seeing and making art. A study conducted at the University of Toronto explains how art affects brian activity and when a person interacts with artwork, it stimulates the brain’s posterior cingulate cortex which is responsible for thoughts and emotions. Art is able to affect our senses, thoughts and emotions. This is why when people see yellow or green it lightens up their mood and makes them feel refreshed compared to seeing grey or black. Art is therefore universal and affects each one of us. It goes past culture, race and religion and it conveys diverse messages to different people. 
The results that we have found in our study allows us to further understand the emotional effects of artworks to both the observer and the artist. Especially because Van Gogh’s end was so tragic, we can further see the progression of his expression and understand how the psychology of a person is able to affect his or her art. This could be used to further understand a person’s state of mind and use it as self reflection in a time where many times we consume without thought. 

Another issue that could be brought up is the source of Van Gogh’s depression which came from a lack of recognition (IDEA).
For the future direction, we can blend in with traditional analysis and see different artists to compare the artistic styles. Also, we can use better visualization techniques to show our work more clearly and lively. For example, if possible, we can make a 3D model that includes each feature we analyzed on each third dimensional layer so that we can show multiple 2D charts at the same time, making the result of our work more informative. Furthermore, we can build a model that can take an artist’s life events and his or her paintings as inputs and outputs the correlation between the two inputs. With enough training data, we may be able to find out the reasons that contribute to the unique characteristics of each artist we study.


## Team Roles

Yicen Ma: writing code with Xingyu, generating the result, participating in the result part.

Xingyu Jiang: writing code with Yicen, generating the result, participating in the result part.

Chang Yuan: writing the data part and summarizing the background information for the result and discussion part.

Kaixin Huang: writing the result part.

Michael Kusnadi: writing the discussion part.

## Technical Notes and Dependencies

Need to import cv2 and imutils as pip packages.

## Reference

Kurt, Sevinc, and Kelechi Kingsley Osueke. “The Effects of Color on the Moods of College Students - Sevinc Kurt, Kelechi Kingsley Osueke, 2014.” SAGE Journals, journals.sagepub.com/doi/10.1177/2158244014525423.

“Vincent Van Gogh.” Biography.com, A&E Networks Television, 4 Mar. 2020, www.biography.com/artist/vincent-van-gogh.

“Vincent Van Gogh.” Wikipedia, Wikimedia Foundation, 7 May 2020 (accessed) , en.wikipedia.org/wiki/Vincent_van_Gogh.
