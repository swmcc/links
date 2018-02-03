# Links

## Description

I have a collection of links that I take note of during my work day. It is a simple text file and looks like:

```text
Some description - Some Link - Timestamp
```

It resides in my [Dropbox](http://www.dropbox.com) folder so it is accessible on multiple machines.

This is a good example of a simple solution. I could have used a [Rails](http://rubyonrails.org/) or [Django](https://www.djangoproject.com/) but that would have been too much. I simply have two `bash` scripts. One for searching and one for adding to the file.

### Scripts

`links <search term>` # if no search term is given it will display all linnks

`add_link "the description" link`
