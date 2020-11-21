# 00x01  Foreword
The intended audience of the course is students of mathematics in the fifth
semester of their studies. The goal is to provide a brief but up to date introduction to information systems with special attention to web-based solutions.
The topic is treated as a supplementary subject to the studies in mathematics,
with no desire of comprehensive, detailed and far reaching discussion of any
of the areas it deals with. These notes introduce only the essential concepts
providing additional examples for easier understanding. After the course, the
student should have a clear concept of elementary problems and solution techniques in relational data modeling and he should have basic knowledge in relational database manipulation. With additional programming skills (PHP/Perl)
he should be able to write simple web-interfaces to relational databases, using SQL. He should be able to create moderately complex XML documents,
validate them using XSchema, address its parts using XPath and, provided he
knows HTML, transform it into a displayable HTML document by XSLT.
These lecture notes are built up as follows. In Chapter 1 we present an
introduction to the theoretical foundations of relational data modeling. In Section 1.2 we discuss the Entity-Relationship (ER) model from the basic concepts
till the standard ER-techniques to be used for data modeling. In Section 1.3 we
continue by applying the results of Section 1.2 for relational database design,
now dealing also with manipulation of tables and redundancy elimination i.e.
normalization. Section 1.4 contains the SQL specifications (a standard language
to form queries for- and to create, destroy and manipulate relational databases)
and via several examples demonstrates its usage.
In Chapter 2 we briefly discuss more practical issues of on-line databases to
“scratch the surface” ofthe enormous amount of knowledge accumulated in the
nowadays ubiquitous web-based information systems with relational database
support. In Section 2.1 we discuss two relevant kind of on-line information
systems: transaction management systems, and static archives (which are often
filled with transaction data forlater analysis). Wedescribe the arising problems
in both environments and the rigorous requirements they pose for information
systems whichintendto achieve success inthese scenarios. Finally,in Section2.2
we introduce state of the art free software from which one can build web based information systems for virtually any purpose.
In Chapter 3 we provide a small survey on a few XML technologies which
are related to hierarchical data description and retrieval. In Section 3.1 we
introduce the generic XML framework with the example of XHTML followed
by a discussion on data identification problems and solutions in Section 3.2.
Section 3.3 deals with document validation. Section 3.4 provides means to refer
to parts of XML document and to navigate in them, and in Section 3.5 we
present an introduction to the topic of XML document transformations e.g.
for data presentation using HTML. Section 3.6 addresses the problem of data
retrieval in more general context.
As this document is of purely introductory nature, I tried to supply enough
references for further studies. Most of the information sources are freelyavailable on the Internet.

# 00x02 Information Sources
In this section we summarize the information sources these lecture notes rely
on. The sources are by no means the only ones that can be used to study the
topics discussed in these notes, however they provide a good introduction to
them.
For the (relational) data modeling part of the notes a standard reference is
[3],whichgivesanextensiveoverviewandathoroughintroductiontodatabases.
It is also recommendable to look at the excellent lecture notes of [14].
For the part on on-line databases one can also use [3], and in particular for
search engines [7].
For the XML part a brief, to the point introduction can be found in [2].
However the original specifications are all available on line: [8, 9, 10, 13, 11].
It cannot be emphasized enough to search the Internet for further information. By the nature of the topic, an enormous amount of information is available
on-line, awaiting to be discovered.
