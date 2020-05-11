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

  In this project, we are trying to analyze the scan paintings by Vincent van Gogh artworks from (1862 - 1890) throughout his life (1853 - 1890) with respect to its correlation to his experiences. We are using images of all of Vincent van Gogh’s paintings in his lifetime from Wikiart.org. To understand the analysis we are going to do, we need to firstly know Vincent van Gogh’s life and the style and genre of his paintings (both the early ones and later ones). 
  
  Born in a religious family, Van Gogh is affected by the environment he grew up in and became a Protestant missionary after his education in schools. He preached to the poor coal miners in a coal mine in southern Belgium where preachers were sent as punishments. But van Gogh did it voluntarily. During that time, he drew about the miners and their families, along with some landscapes and things he saw around him. After this time period of his life, he went to art school to start learning art formally and then started his career as a painter in 1880 in Brussels, where he studied art. In 1886, he moved to Paris and was affected by Impressionism and post-impressionism, which contributed to the style change to his paintings. However, his paintings were seldom noticed or liked by people in his time. Along with his suffering from psychotic episodes and delusions, he gradually became depressed. His drinking problem and lack of income made him more moody. After an argument with his friend, he cut off his left ear. Even though recovered after some time, he still suffered from loneliness and depression, which partially led to his suicide in 1890, with an age of 37 years old.
  
  Vincent van Gogh’s style is seen as post-impressionism. According to Wikipedia, “Post-Impressionists extended Impressionism while rejecting its limitations: they continued using vivid colours, often thick application of paint, and real-life subject matter, but were more inclined to emphasize geometric forms, distort form for expressive effect, and use unnatural or arbitrary colour”. In this project, we are going to analyze van Gogh’s paintings’ colors and other elements that potentially show his emotions in relation to the time of the paintings and his personal experiences.
  
  This idea is inspired by an academic research about the relation between colors and emotions by Sevinc Kurt and Kelechi Kingsley Osueke. The research is trying to find out the effects colors have on people’s mood and the psychological reasons behind. It is explained that different colors have different wavelengths when struck by light to the human eyes, causing different perceptions. This is the reason for the effects of colors on emotions. This gives us the inspiration to study the color in Vincent van Gogh’s paintings and the emotions within them. The emotions van Gogh wanted to deliver through his painting are also related to the emotions he had when drawing those paintings. In our project, we will analyze how van Gogh’s artworks are affected by his experience and therefore emotions and how they are shown in his paintings.


## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- data acquisition/scraping
- cleaning
- analysis
- generating results. 

Link each of your notebooks or .py files within this section, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section will contain links to documentation of your results. This can include figures, sound files, videos, bitmaps, as appropriate to your domain of analysis. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally relevant?
- How does your computational approach differ from the traditional art historical, musicological, manuel/subjective approach to analyzing your cultural subject? 
- How do you think the original artists/musicians would respond to this type of analysis? Would it change/inform their practice in some way?
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
