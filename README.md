# XAI Stories 2.0. eXplainable Artificial Intelligence for Retail Analytics

ebook: https://pbiecek.github.io/xai_stories_2/

In 2020, as part of the Interpretable Machine Learning course, students created XAI Stories, an ebook that collects the experiences of the subjects covered in the form of a series of chapters on different applications of XAI techniques.

This was a great idea. Each team developed an interesting solution and then described it in a clear and interesting way. Some of these results were later presented at relevant industry conferences.

This year we are continuing this experiment but focusing on applications in one sector - retail analytics. In cooperation with students from the universities of Warsaw and Lodz, as well as partners from McKinsey and Shumee, this ebook has been created - presenting various ideas and applications on how to use predictive modelling in retail, but also how to enrich these solutions with XAI.

I hope that the presented solutions will trigger development of new interesting solutions implementing explainable machine learning in the retail industry.

## How this book came about

This book is the result of a student projects for [Interpretable Machine Learning](https://github.com/pbiecek/InterpretableMachineLearning2021) course at University of Warsaw and University of Łódź. Each team has prepared one case study for selected XAI technique.

This project is inspired by a fantastic book [Limitations of Interpretable Machine Learning Methods](https://compstat-lmu.github.io/iml_methods_limitations/) done at the Department of Statistics, LMU Munich.
We used the LIML project as the cornerstone for this repository.

## How to build the book

Step 1: Clone or download the repository https://github.com/pbiecek/xai_stories_2.

Step 2: Install dependencies

```
devtools::install_dev_deps()
```

Step 3: Render the book (R commands)

```{r}
bookdown::render_book('./', 'bookdown::gitbook')
```

