# Senior-Project
Utilizing scrubbed data from Dallas charity The Senior Source to create categorization models and analysis.

For my senior capstone project, myself and four other classmates were tasked with working with The Senior Source, a Dallas-based charity focuising on providing assistance to the elderly. For this project, we were asked to take the contact data from a period of approximately six months and draw meaningful analysis to present back to the company. We gave the company this analysis while also expanding upon what was asked of us by implementing categorization and prioritization models that would make the organization and legibility of these incoming requests more manageable for The Senior Source. My personal focus was on the categorization models, but we all contributed to the code seen here. Not all code from this project is listed in this repository, as me and my teammates had many notebooks for preliminary tests as well as numerous dead ends, but this code in this repository does show the final versions of our created models as well as notable analysis presented.

In our analysis, we used methods such as TF-IDF and BERTopic modeling to find insight into trends within the data, typically revolving around common words or demographic details. Not all analyses within the code were deemed useful, but many elements ended up in our presentation to our sponsor.

For our categorization model, we tried multiple models but ultimately settled on an NMF model, as we felt it gave the most diverse view of the issues The Senior Source's clientele were facing without getting repetitive. Since most of the methods we tried out were unsupervised, there were no meaningful comparison or accuracy metrics to create, so our choice was made subjectively but with much deliberation.

For our prioritization model, we made a CCM which also included CRF modeling and sentiment analysis. This combination of methods created a strong final model that allowed us to prioritize contact requests on a scale of 0-4 with an accuracy score of approximately 70% when compared to our determined priority scores.

Some files could not be uploaded in their original .ipynb formats, so are instead given here as .py files, but previews for the code output can be found by following the links at the top of each file.
