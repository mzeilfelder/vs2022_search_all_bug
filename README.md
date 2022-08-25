# vs2022_search_all_bug
test-repository to reproduce a problem with the search-all functionality in VS2022
It got fixed with the 17.3.2 update.

To reproduce:  
Start with main branch.  
Open VS 2022.  
Search all "just a dummy" should find both.  
Checkout side_branch_one  
Checkout main  
Search all "just a dummy" should find only one now
