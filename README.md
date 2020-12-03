Astronauts
================
by The Mousebreakers

## Summary

The space industry has been male-dominated from the start, and this
trend has continued in recent years, as shown by the graph’s
proportionality display. While this may be due to space-related
occupations being primarily populated by STEM graduates, a notoriously
gender-imbalanced field, we were still surprised at the lack of female
representation in space when skimming through the “astronauts” dataset
from the TidyTuesday Database. We aimed to find trends behind our data;
is there a systematic problem with gender in space? In the Western
world, military structures prohibited capable women from becoming
eligible to launch. It was only in 1978 that anti-discrimination laws
were passed to open up the job to female applicants. This Violin plot
simply shows the time astronauts spent spacewalking, with women having
spent significantly less time performing EVA than men. Upon initial
research, it is a lack of well-fitting space suits and a lower radiation
tolerance that could be responsible for this. However, variables such as
the type of job women typically perform in space may play a part.

Since 1959 people from 40 different nationalities have ventured into
outer-space. This includes countries you would expect such as the U.S.
and Russia, as they are well known for their space programmes, but also
lesser expectant countries such as Mongolia, Afghanistan and Saudi
Arabia. Out of the 40 different nationalities only 9 had a female
astronaut. The U.S. had 125 female astronauts. This would be expected as
the U.S. had the highest overall amount, however, only equates to only
14%. The U.S.S.R/Russia has 6 female astronauts and this equates 2% of
their astronauts being female. When considering the selection programme
these women enrolled in and their nationality, NASA enrolled the highest
number of female astronauts. This is consistent with what we have
previously seen as it is an American based space exploration company.

The next variables we considered were occupation and military status. A
common indicator of workplace gender inequality is women having to
outperform their male counterparts to receive the same level of
treatment.Aware of this, we sought to investigate how military status
affected selection for missions, and whether there are more female
civilians.We found that a higher proportion of all the astronauts are in
the military, around 60%.However, if we look at the genders of the
astronauts separately, a much smaller proportion of women who were in
space are in the military. As for the occupation levels, we found that
there is a drastic difference between the male and female
astronauts.There are very few high ranking female astronauts, and most
of them are mission specialists. Furthermore, male astronauts are more
likely to be higher ranking,which means that there are signs of gender
inequality in the astronaut industry by not offering higher ranks to
female astronauts with potentially the same experience.

The next variable we investigated was ‘Mission hours’ of women as
compared to men and how likely women were to be recalled for missions as
compared to men. The first visualization we completed showed that women
weren’t being employed for missions over 7500 hours or 300 days. After
further investigation this turned out to only be only 10 of 1772
missions but despite this it still seemed interesting that women weren’t
being considered for these length of missions. The next visualization
showed that where the bulk of the data lied for mission hours, below 800
hours, both women’s and men’s length of mission seemed to be comparable.
The ratio of men to women stayed relatively constant between 1 and 5
missions. Implying that women were being recalled just as much as men
and that once employed were doing just as good a job.

To see how each variable contributes to the gender of the astronauts we
used logistic regression. We split the data into two sets: training and
testing, and predicted the gender of an incoming astronaut based on
covered variables. The Receiver Operating Characteristic curve came out
to be above the diagonal line, meaning that the variables do in fact
contribute to the gender of the astronauts.

In conclusion, we have found that different variables contribute
differently to the gender of the astronaut, with nationality and
selection programme being the most influential. We have shown that there
is an upward trend in the number of female astronauts. Possible reasons
for that are changing traditional gender roles and striving for equality
in the workplace which results in a progression towards gender equality
in the space industry.

## Presentation

Our presentation (slides) can be found
[here](https://ids-s1-20.github.io/project-the_mousebreakers/).

Our pre-recorded presentation can be found here
<https://media.ed.ac.uk/media/The+Mousebreakers+-+Astronauts/1_zva3l3ss>

## Data

Stavnichuk, Mariya; Corlett, Tatsuya (2020), *“Astronaut database”*,
Mendeley Data, V1, doi: 10.17632/86tsnnbv2w.1

## References

Valentina Tereshkova, Copyright RSC Energia,
<https://anotherimg-dazedgroup.netdna-ssl.com/482/azure/another-prod/340/7/347259.jpg>

Spacewalk, Copyright NASA,
<https://techcrunch.com/wp-content/uploads/2016/01/nasa-spacewalk.jpg?w=1390&crop=1>

Stavnichuk, Mariya; Corlett, Tatsuya (2020), *“Astronaut database”*,
Mendeley Data, V1, doi: 10.17632/86tsnnbv2w.1
