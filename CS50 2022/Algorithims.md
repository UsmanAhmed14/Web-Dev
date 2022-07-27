- [Introduction](#introduction)
- [Algorithms](#algorithms)
- [Searching](#searching)
- [Big O Notation](#big-o-notation)
- [Common Running Times](#common-running-times)
- [Asymptotic Notation](#asymptotic-notation)
- [Searching Lockers](#searching-lockers)
- [Linear Search](#linear-search)
- [Binary Search](#binary-search)
- [Sorting and Searching vs. Just Searching](#sorting-and-searching-vs-just-searching)
- [Implementing Linear Search](#implementing-linear-search)
- [String Comparison](#string-comparison)
  - [Name](#name)
  - [Description](#description)
  - [Return Value](#return-value)
- [Storing Data in Arrays](#storing-data-in-arrays)
- [Structs](#structs)
- [Sorting](#sorting)
- [Visualizing Sorts](#visualizing-sorts)
- [Selection Sort](#selection-sort)
- [Bubble Sort](#bubble-sort)
- [Comparing Sorts](#comparing-sorts)
- [Recursion](#recursion)
- [Merge Sort](#merge-sort)
- [Sort Race](#sort-race)

# Introduction

Today we'll be focusing on [ Algorithms ](#Algorithms) which solve problems with arrays. It turns out a computer can't look at all the elements at once.

# Algorithms

# Searching

# Big O Notation

# Common Running Times

# Asymptotic Notation

# Searching Lockers

- On stage we have seven lockers with closed doors, with numbers hidden behind them. Since a computer can only look at one element in an array at a time, we can only open one door at a time as well.

- if we want to look for the number zero,for example we would have to open one door at a time and if we didnt know anything about the numbers behind the doors, the simplest algorithm would be goinf from legt to right.

- This algorithm, **Linear-Search**, would be correct but not very efficient,we might write pseudocode with:

# Linear Search

# Binary Search

# Sorting and Searching vs. Just Searching

# Implementing Linear Search

# String Comparison

## Name

> strcmp - Compares two strings

```c
#include <cs50.h>
#include <string.h>

int strcmp(String S1, String S2);

```

## Description

_This Function compares two strings case-sensitively_

## Return Value

This Function returns

- an `int`less than `0` if `S1` comes before `S2`,
- `0` if `S1` is the same as `S2`,
- an `int` greater than `0` if `S1` comes after `S2`.

> Wrote a program named Names.c
>
> > ```c
> >  #include <cs50.h>
> > #include <string.h>
> > #include <stdio.h>
> >
> >
> > int main(void)
> > {
> > string names [] = {"Bill","Charlie","Fred","George","Ginny","Percy","Ron"};
> > for (int i = 0; i < 7; i++)
> > {
> > if(strcmp(names[i], "Ron") == 0)
> > /*so as we have seen in the previous example '==' comapares only one letter or ascii valude like '65' however the function strcomp string compares lets us compares multiple letters and ascii values and letters.*/
> > {
> > printf("Found\n");
> > return 0;
> > }
> > }
> > printf("Not Found\n");
> > return 1;
> > }
> > ```
> >
> > will return positive

_We Created a file named **names.c**_

```c
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
    string names [] { "Bill", "Charlie" , "Fred" , "George" , "Ginny" , "Percy" , "Ron"};
    for (int i = 0 ; i < 7; i++)
    {
        if (name[i] == "Ron")
        {
            printf("Found\n");
            return 0;
        }
    }
    printf("Not Found\n");
}
```



we encountered an error but after that we made changes in code by adding `strcmp` function

```c
if (strcmp(names[i]) == 0)
```

This function compares two or more strings and checks if its [Return Value]( ##Return-Value ) is equal to zero

# Storing Data in Arrays

# Structs

# Sorting

# Visualizing Sorts

# Selection Sort

# Bubble Sort

# Comparing Sorts

# Recursion

# Merge Sort

# Sort Race

```

```

```

```
