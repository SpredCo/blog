# Spred blop

## Deploy
 This blog needs ruby > 2.3.0 and bundler to run. Once you have ruby installed just clone this repository, install dependencies and run:
 
 ```bash
git clone https://github.com/SpredCo/blog
cd blog
bundle install
bundle exec jekyll serve
 ```
## Write a post
1. Clone the repoitory

 ```bash
 git clone https://github.com/SpredCo/blog
```
2. Create post file

 You need to create one file by post, the file must be in the _posts folder. Post file name should be current_day_article_name.md
 E.G:
 ```bash
 touch ./_posts/2017_01_01_happy_new_year.md
 ```
3. Commit and push

 ```bash
 git commit -am "add happy new year post"
 git push origin master
 ```
