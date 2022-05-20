# Replacing goodreads

I hate goodreads. It's owned by Amazon, it's clunky and unreliable. I'd like to use this space to both document replacing goodreads as a service, and a general tbr list.
### Approach A
- [ ] Initialize dataframes for primary shelves
- [ ] Collect titles from goodreads API
- [ ] Do data stuff with them once they're local!

 This is a bookshelf I made in goodreads. I'm trying to scrape from it now.
<iframe
	border=0
	frameborder=0
	height=250
	width=550  
	src="https://www.goodreads.com/review/list/85882054-ivy?ref=nav_mybooks&shelf=weird-shorts">
</iframe>


### [Approach B](https://www.youtube.com/watch?v=Gvke-vriQbY)
- [x] Initialize a ~~reading note~~ template with the following data:
	- Rating
	- Title + author
	- number of pages and/or number of hours (if digital listen)
	- link to book note
	
	```json
{
	'title':''
	'author':''
	'pub_year':''
	'year_fin':''
}
```

Individual book notes
	- Links to notes generated from book
	- Using the tag method: # SN for source note
Improvements:
- generate a personal-book-citation
-  store entries as a dictionary or df and print list >> obsidian [[dataview]] plugin

#programming #code #software #to-do 