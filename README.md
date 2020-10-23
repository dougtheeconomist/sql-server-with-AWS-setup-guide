# sql-server-AWS-setup-guide-
A collection of tips I learned the hard way to successfully connecting to a Sql Server instance using Python

I recently went through the experience of setting up and connecting to a sql server database instance hosted by Amazon Web Service’ Relational Database Service. While the actual instance setup via the AWS dashboard was fairly straightforward, connecting to it via Python was less so and I ended up running into several pitfalls along the way. It is my intention to therefore document those pitfalls and how I got past them here in one place in the hopes that this may save someone else some headache in the future. 

## Setup

The first step to creating a usable database is the actual instantiation of the database server that can be used by whatever user base will actually be making queries at the end of this process. Amazon has a fairly easy to use dashboard system set up to do this, but there are a couple of things to keep in mind when going through this process. 
