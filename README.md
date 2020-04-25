# Project Title

DSC160 Data Science and the Arts - Midterm Project Repository - Spring 2020

Project Team Members: 
- Kaixin Huang, k3huang@ucsd.edu
- Xingyu Jiang, xij080@ucsd.edu
- Yicen Ma, yim095@ucsd.edu
- Chang Yuan, chy238@ucsd.edu
- Firstname Lastname5, name5@ucsd.edu

## Abstract

(10 points) 

For the project proposal, please write a short abstact addressing the questions below. You should replace the entire contents of this section with one to two paragraphs addressing the following:

  In this project, we are going to analyze Vincent Van Gogh artworks from the wikiart.org with 1931 artworks. Vincent Van Gogh was a dutch post-impressionist painter who is still one of the most influential and famous figures in art. It is known that his art style, especially his self portraits, changed drastically due much to his mental health. As context, Van Gogh was mostly unsuccessful in his life and art. He became depressed as he was an art dealer that was unable to truly rise up and become famous. He only became famous after his suicide and we see that his art style changed drastically due to his failing mental health at that time. We would like to study this change as we feel that it is an important and significant topic. Culturally, due to Van Gogh being such a famous figure,  he and his art has affected both the art style (post-impressionism) and art in general. We have all seen Van Gogh’s art and know who he is, now if we are able to study his mental health through his art and depict it, we can see how psychology is able to affect art. This is important as art carries an emotional weight and is able to affect our mood and atmosphere. Personally we are also able to further understand why some paintings are more dark than others, or if they affect us on a deeper level and give us a certain feeling. Our research question is with the differences shown in Van Gogh artworks, what can we know about his experiences and emotions in his life by creating a timeline of his artworks. The hypothesis for this project is that Vincent Van Gogh’s artworks are correlated with his personal experiences and emotions in the process of time.
  
  We are going to analyze features such as brightness, hue, rgb values (different kinds of colors), saturation, whether there are people in an artwork by using face detection, and edges in each painting to address our question. We will scrape Van Gogh’s artworks from the wiki art website. Then, we will use face detection and basic image features methods to see whether there exists any differences in Van Goph’s artworks in different time periods. Furthermore, we can get the image width, image height, mean hue, mean saturation, mean brightness, resolution, RGB values and edge counts which we will use in our analysis (ie. calculate the number of colors that exist in Van Gogh’s artworks). The analytic techniques we’ll use are histogram, scatter plot, bitmap, and line chart using bokeh. We can plot the brightness, hue, resolution to get the distribution of those values we need and find the relationship between 2 features. As a result, we will create a bitmap to show the trend for Van Gogh’s artworks in a certain period or a time series graph plotting Van Gogh’s artworks over time. We will use the techniques we learned from class to extract the features of each painting. As we find different transformations in his paintings, we look up his personal experiences. In this project, we attempt to seek out his emotional presentation in his artworks through analyzing features. 


## Data

(10 points) 

This section will describe your data and its origins. Each item should contain a name of the data source, a link to the source, and any necessary background information such as:
- What is your cultural data source? 
- When was it made? 
- Who created the works? 
- Is it digital native, or is it some kind of scan, recording, photo, etc., of an analog form? 

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
