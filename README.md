# test_markdown webscraping

The code you will find here is some code I used to collect covid related news for two articles/papers I'm working on. It may be a bit long, but it does the job. In this case, we only have one example, one for latercera.cl (only R code). You can check this link https://github.com/felobusta/newsrecollection/blob/main/emolscraping_1.py for Python under a different webpage. You can use this code for any other news media outlet that lets you get the xpaths from the HTML code, like elpais.es, or theclinic.cl. You can also check the website related to this code with examples: https://felobusta.github.io/test_markdown/test_1

There are two important aspects to consider:

- R code: may work even on paywalls
- Python code: when there is a pop up there could be some issues, so you must check the website and its structure before running the code

You must also consider the type of webpage you are facing, if it's a java base website this code may or may not work, if it's just a normal html document then there shouldn't be any problem.
