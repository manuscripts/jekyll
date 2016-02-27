Simple • Static • Blog-aware 

# Jekyll Documentation (Book Edition)

by Tom Preston-Werner, Nick Quaranto, Parker Moore, et al


> **Note:** The book edition is still an early release and a work-in-progess.


This is the [(official) documentation](https://github.com/jekyll/jekyll/tree/master/site/_docs)
for the Jekyll static site builder / generator
reformatted in a single-page book edition.

See the [source repo](https://github.com/hydepress/hydepress.github.io) for how
the book gets auto-built with "plain" Jekyll - of course - and hosted on GitHub Pages.



### Questions? Comments?

Send them to the Jekyll Talk forum post titled
[Jekyll Docu Reformatted as a Single-Page in Black 'n' White (Book Version) - Why? Why Not?](https://talk.jekyllrb.com/t/jekyll-docu-reformatted-as-a-single-page-in-black-n-white-book-version-why-why-not/1908).
Thanks.


### Build Notes

For local build use the github-pages gem with bundler:

    $ bundle exec jekyll build --safe  # or
    $ bundle exec jekyll b --safe
   

#### Git Submodules

To add use:

    $ git submodule add https://github.com/hydepress/jekyll _jekyll

To check try:

    $ cat .gitmodules
   
Printing something like:

    [submodule "_jekyll"]
        path = _jekyll
        url = https://github.com/hydepress/jekyll


Todo: Add/use  --name jekyll option to keep original name - why? why not?

Update Submodule.  Follow these steps:

to be done


### Todos

- Add preface to manuscript ??
- Move available plugins to appendix ??
- Add Jekyll F.A.Q. to appendix ??
- Auto-add book.yml and chapters.yml datafiles ??
    - liquid not possible in datafile ??
      e.g. include_relative ../_pages/book.yml is not working/possible
    - change data_dir to _pages/data  (not possible in safe mode with github pages ???)



