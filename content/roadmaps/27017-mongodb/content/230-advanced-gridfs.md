# GridFS

In MongoDB, the maximum size of your BSON document can only be 16 megabytes. The maximum document size helps ensure that a single document cannot use excessive amount of RAM or, during transmission, excessive amount of bandwidth. 

 GridFS is a specification for storing and retrieving files that exceed the BSON-document size limit of 16 MB. Instead of storing a file in a single document, GridFS divides the file into parts, or chunks, and stores each chunk as a separate document.



<ResourceGroupTitle>Free Content</ResourceGroupTitle>

<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.mongodb.com/docs/manual/core/gridfs/'>GridFS</BadgeLink>
