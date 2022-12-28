# Indexing

Indexes support the efficient execution of queries in MongoDB. Without indexes, MongoDB must perform a collection scan, i.e. scan every document in a collection, to select those documents that match the query statement. If an appropriate index exists for a query, MongoDB can use the index to limit the number of documents it must inspect.

Indexes are special data structures that store a small portion of the collection's data set in an easy to traverse form. 

<ResourceGroupTitle>Free Content</ResourceGroupTitle>
<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.mongodb.com/docs/manual/indexes/'>Indexes</BadgeLink>
<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.mongodb.com/docs/manual/applications/indexes/'>Indexiing Strategies</BadgeLink>
<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.mongodb.com/docs/manual/tutorial/equality-sort-range-rule/'>The ESR (Equality, Sort, Range) Rule</BadgeLink>

<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.mongodb.com/blog/post/performance-best-practices-indexing'>Performance Best Practices: Indexing</BadgeLink>



<BadgeLink badgeText='Watch' href='https://learn.mongodb.com/courses/mongodb-indexes'>MongoDB Indexes</BadgeLink>


