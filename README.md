# skroutz-web-scraper-go
 CLI based web scraper written in Go, that scrapes www.skroutz.gr for any new deals.

# Installation 
Make sure you are running ```go version 1.20.x```

```
git clone https://github.com/petersid2022/skroutz-web-scraper-go.git
cd skroutz-web-scraper-go
go build .
```
**TIP:** Move the binary to ```~/.local/bin```. That way, you can execute the command from the terminal, wherever you are!

# Possible Optimizations

* Use goroutines (Concurrency)

* Use a database (GORM)

* Use a caching mechanism

* Use a better URL shortener service (Bitly or Google URL Shortener)

* Use a better HTML parsing library (GoQuery)

# Things I am going to implement
* Command-Line flags (change category, add filters, prices ascending/descending etc.)

* Add colors.


Input is very much appreciated. This is a ["Hello, World!"](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) program, so as you would expect there are a few* rough edges.
Distribute, edit and make Pull Requests freely. 

Peter Sideris 2023
