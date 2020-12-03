Astronauts
================
by The Mousebreakers

## Summary

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
previously seen as it is an american based space exploration company.
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
female astronauts with potentially the same experience. The next
variable we investigated was ‘Mission hours’ of women as compared to men
and how likely women were to be recalled for missions as compared to
men. The first visualization we completed showed that women weren’t
being employed for missions over 7500 hours or 300 days. After further
investigation this turned out to only be only 10 of 1772 missions but
despite this it still seemed interesting that women weren’t being
considered for these length of missions. The next visualization showed
that where the bulk of the data lied for mission hours, below 800 hours,
both women’s and men’s length of mission seemed to be comparable. The
ratio of men to women stayed relatively constant between 1 and 5
missions. Implying that women were being recalled just as much as men
and that once employed were doing just as good a job. To see how each
variable contributes to the gender of the astronauts we used logistic
regression for the covered variables. Then we divided the data into a
training set and a test set to predict the gender of an incoming
astronaut based on those variables. The Receiver operating
characteristic curve came out to be above the diagonal line. This means
that the variables taken into consideration do in fact contribute to the
gender of the astronauts. In conclusion, we have found that different
variables contribute differently to the gender of the astronaut, with
nationality and selection programme being the most influential. We have
shown that there is an upward trend in the number of female astronauts.
Possible reasons for that are changing traditional gender roles and
striving for equality in the workplace which results in a progression
towards gender equality in the space industry.

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.0 ──

    ## ✓ ggplot2 3.3.2     ✓ purrr   0.3.4
    ## ✓ tibble  3.0.4     ✓ dplyr   1.0.2
    ## ✓ tidyr   1.1.2     ✓ stringr 1.4.0
    ## ✓ readr   1.4.0     ✓ forcats 0.5.0

    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

    ## 
    ## ── Column specification ────────────────────────────────────────────────────────
    ## cols(
    ##   .default = col_double(),
    ##   name = col_character(),
    ##   original_name = col_character(),
    ##   sex = col_character(),
    ##   nationality = col_character(),
    ##   military_civilian = col_character(),
    ##   selection = col_character(),
    ##   occupation = col_character(),
    ##   mission_title = col_character(),
    ##   ascend_shuttle = col_character(),
    ##   in_orbit = col_character(),
    ##   descend_shuttle = col_character()
    ## )
    ## ℹ Use `spec()` for the full column specifications.

## Presentation

Our presentation (slides) can be found
[here](https://ids-s1-20.github.io/project-the_mousebreakers/).

Our pre-recorded presentation can be found here
<https://media.ed.ac.uk/media/The+Mousebreakers+-+Astronauts/1_zva3l3ss>

## Data

Stavnichuk, Mariya; Corlett, Tatsuya (2020), *“Astronaut database”*,
Mendeley Data, V1, doi: 10.17632/86tsnnbv2w.1

Include a citation for your data here. See
<http://libraryguides.vu.edu.au/c.php?g=386501&p=4347840> for guidance
on proper citation for datasets. If you got your data off the web, make
sure to note the retrieval date.

## References

Stavnichuk, Mariya; Corlett, Tatsuya (2020), *“Astronaut database”*,
Mendeley Data, V1, doi: 10.17632/86tsnnbv2w.1

List any references here. You should, at a minimum, list your data
source.
