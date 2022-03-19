# Hello World

Tutorial repo to familiarize you with the basic workflow of contributing to a R package.

## Follow these steps

We first clone the repository, then open it in your favourite IDE (i.e. RStudio), extend a function and commit our changes back to the repo.

This corresponds to `Case 1` as mentioned on the main wiki page.


1. Clone the repository

```{bash}
cd ~
mkdir github
mkdir github/ivt-baug-ethz
cd github/ivt-baug-ethz

## if SSH
git clone git@github.com:ivt-baug-ethz/helloworld.git

cd helloworld
```

2. You now have the respository in your local file system. Open it in RStudio.

3. Run in your console `devtools::load_all()` then `devtools::document()` and finally `browseVignettes("helloworld")` and click on HTML.

4. Follow the steps as ellaborated in the html document.

