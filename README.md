# Partially Derivative Jekyll Site

## Adding a new podcast episode

1. Upload to audio file to S3
2. Create a new file in \_posts
3. Make the filename YYYY-MM-DD-TITLE.md
4. Set that post to category: podcast

## Adding a new blog post

1. Create a new file in \_posts
2. Make the filename YYYY-MM-DD-TITLE.md
3. Set that post to category: blog

## Adding a new data love letters

1. Create a new file in \_posts
2. Make the filename YYYY-MM-DD-TITLE.md
3. Set that post to category: dataloveletters

## Adding an author

1. Go to \_config.yml and follow the examples there
2  Add their photo to assets/img/authors

## To Build:

```jekyll build --watch```

## To preview

```jekyll serve```

## To deploy

- Push to master, Github will do the rest

## Left to do
 - Write subscribe page
 - set CNAME
 - set base url
 - set user photos
 - Write sponsor page
 - Import data love letters past issues
