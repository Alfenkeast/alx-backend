0x00. Pagination
Resources
Read or watch:

REST API Design: Pagination
HATEOAS

Tasks
0. Simple helper function
mandatory
Write a function named index_range that takes two integer arguments page and page_size.

The function should return a tuple of size two containing a start index and an end index corresponding to the range of indexes to return in a list for those particular pagination parameters.

Page numbers are 1-indexed, i.e. the first page is page 1.

AUTHOR
Eke Patience @github(Alfenkeast)

Files
Files	Description
main.py, 0-simple_helper_function.py	Simple helper function
1-main.py, 1-simple_pagination.py	Simple pagination
2-main.py, 2-hypermedia_pagination.py	Hypermedia pagination
3-main.py, 3-hypermedia_del_pagination.py	Deletion-resilient hypermedia pagination
Popular_Baby_Names.csv	Dataset
