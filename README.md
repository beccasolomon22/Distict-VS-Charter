# pandas-challenge

## Sources

1. Starter Code provided in the asssignments files
2. Our class's discord provided general tips for common errors received by many in the class. This was only used on the pd.cut functions where I originally called directly from the dataframe columns but through discord help realized that I only needed to call from the data used to create the dataframe.
3. Stack Overflow was a great help in reminding me of tolist() which I used for per_school_counts

## Analysis

### District VS Charter

Through sorting the Overall Passing percentages I saw a clear divide between District and Charter schools. The top 5 highest percentages were all from charter schools, whereas the bottom 5 lowest percentages were all from district schools.

This discovery was fascinating because of the large difference between the hightest percentages and the lowest. The Highest % Overall Passing is 91.33% at Cabrera HS Charter. The Lowest % Overall Passing is 52.99% at Rodriguez HS District. That is a 38.34% difference between 15 schools. However, the difference between the top 5 schools is only 0.79% and the difference between the bottom 5 schools is only 0.54%. 

The Lowest % Overall Passing for Charter Schools is 89.22%.
The Highest % Overall Passing for District Schools is 54.64%

The 7 District Schools % Overall Passing is 53.67%
The 8 Charter Schools % Overall Passing is 90.43%


### School Size

Before this assignment I would have guessed that the difference between the school types would have been been. However, based on the information we have, this is not the case.

The greatest difference between District and Charter Schools is the total students. 

The 7 District Schools average around 3,854 students. With the lowest total being 2,739 students and highest being 4,976 students.
The 8 Charter Schools average around 1,524 students. With the lowest total being 427 students and highest being 2,283 students.

Out of the 15 schools:
Schools with <1000 students had an % Overall Passing of 89.88%.
Schools with 1000-2000 students had an % Overall Passing of 90.62%.
Schools with 2000-5000 students had an % Overall Passing of 58.29%.

Once a school rises above 2000 students the overall passing grade drops by around 32%

### School Budget per Student

This is the area that surprised me the most as I would have thought that a higher budget per student would lead to a higher overall passing percentage. However we see through these 15 schools that this is not the case at all.

Schools with a Budget per Student of <$585 have a % Overall Passing of 90.37%
Schools with a Budget per Student of $585-630 have a % Overall Passing of 81.42%
Schools with a Budget per Student of $630-645 have a % Overall Passing of 62.86%
Schools with a Budget per Student of $645-680	 have a % Overall Passing of 53.53%

A schools % Overall Passing decreases as the Budget per Student increases.

## Areas for Improvement

1. The district_summary dataframe only works the way it is formatted because each column is a single row. I realized this once working on the other dataframes. I could change the format of this dataframe to match the others.
2. Overall, being more careful in which variable I am using because I spent too much time in creating the per_school_summary dataframe due to me inputting the wrong variable for the overall percentage of passing
