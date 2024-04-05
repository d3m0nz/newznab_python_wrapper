# Newznab Python Wrapper 

Simple python wrapper for NewzNab API calls.
At the moment it does everything through json. 
  
  
---
### Usage

    from client import wrapper
    c = wrapper("my_url.com", "my_api_goes_here")
    result = c.search(q="my query", maxage="20")
    categories = c.categories()

---

Credits
* **Author**: [Gustavo Hoirisch](https://github.com/gugahoi)
