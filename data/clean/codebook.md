---
title: "codebook"
format: html
---

# LibraryThing Data
## book_reviews.csv:
workcode: character variable, the ID of the book.

isbn: character variable, ISBN of this book, an accurate and reliable way to search for a book.

userid: character variable, the id of the user how left the review.

stars: numeric variable, the number of stars the user gives.

written_time: time variable, the time when user left the review.

edited_time: time variable, the time when user edit the review.

review_text: character variable, the text of the review.

## work_tags.csv:
workcode: character variable, the ID of the book.

tag_id: character variable, the ID of the tag.

tag_name: character variable, the name of the tag.

aliased_to_id: character variable, the id of the tag to which the tag has been aliased to (same tag different names).

## award_list.csv:
award_id: character variable, the ID of the award.

award_name: character variable, the name of the award.

applies_to: character variable, what the award is given to (Work, Author, Series).

organization: character variable, name of the organization of the award.

organization_id: character variable, the ID of the award's organization.

total_works: numeric variable, amount of works that won this award.


