Web Scrapping involves writting of codes that get data from website using programming language such as python, java, C and swift etc.

Three steps of getting data
1. Download
2. Extract Data
3. Profit i.e doing something useful with the data 

why Scrapping of website?
1. There's data on the site you want to store or analyze
2. You can get it by other means (e.g API)
3. You want to Pragrammatically grab the data (instead of lots of manual cpoying and pasting)

best practice for web scrapping 
1. Consult the robots.txt file (i.e domain/robots.txt)
2. If making many requests time each rquest to avoid being block 
3. If you are agresive your IP can be blocked

Beautiful Soup only Extract data but does not download HTML

Navigating and Parsing HTML
BeautifulSoup(html_string,"html.parser")
Once parsed there are several ways to navigate HTML:
1. using fin - returns one matching tag
2. using find_all - return a list of all matching tags
3. By Tag Name  

Navigating with CSS Selectors
Select - returns a list of element matching a CSS selectors
Selectors CheatSheet 
1. select by id of foo: #foo
2. select by class of bar: .bar
3. select children : div > p
4. select descendents: div p 

Acessing Data in Elements
1. get_text - access the inner text in an element
2. name - tag name
3. attrs - dictionary of attributes
4. accessing attribute values using brackets

More on Navigating with BeautifulSoup 
# via Tags
1. parent / parents
2. contents
3. next_sibling / next_siblings
4. previous_sibling / previous_siblings

# via Searching
1. find_parent / find_parents
2. find_next_sibling / find_next_siblings
3. find_previous_sibling / find_previous_siblings

# Task
1. scrapping data into csv
2. Goal: Grab all link website 
3. Data: Store URL, anchor tag text and date 