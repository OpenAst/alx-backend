# 0x00. Pagination

Backend

This project is about reading creating pages from dataset. Returns page and page number.

# Resources
- [REST API Design: Pagination](https://intranet.alxswe.com/rltoken/7Kdzi9CH1LdSfNQ4RaJUQw)
- [HATEOAS](https://intranet.alxswe.com/rltoken/tfzcEbTSdMYSYxsspJH_oA)

The datafile for the project is this [file](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2020/5/7d3576d97e7560ae85135cc214ffe2b3412c51d7.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231023%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231023T081613Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2544301a04ece04cf82dee1b3bb957fc6eec4c9bf4e93fb01363dafe4a60b015)


## Setup: Popular_Baby_Names.csv

#TASKS


1. 0. Simple helper function
	Write a function named index_range that takes two integer arguments page and page_size.

	The function should return a tuple of size two containing a start index and an end index corresponding to the range of indexes to return in a list for those particular pagination parameters.

	Page numbers are 1-indexed, i.e. the first page is page 1.

