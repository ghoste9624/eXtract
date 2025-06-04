# eXtract
Extract headers and cookies data from a selected target URL
 
<br>

# Description 
HTTP headers and cookies are both used in the HTTP protocol to exchange information between a client and a server. HTTP headers are used to convey information about the request or response, such as content type, authorization, and caching instructions. Cookies are a specific type of header used to store small pieces of data on the client's computer to help the server identify the client and personalize their experience. 

<br>

# Installation 

<br>

```bash
git clone https://github.com/ghoste9624/extract
cd extract
python cookie.py -h
```

<br>

# example usage

<br>

* Display headers only from a target

```bash
python cookie.py https://github.com/ghoste9624/extract
```
<br>

* Display cookies only from a target

```bash
python cookie.py https://github.com/ghoste9624/extract --cookies
```
<br>

* Display both headers and cookies from a target

```bash
python cookie.py https://github.com/ghoste9624/extract --headers --cookies
```

<br>

# Updated On
``
June 4, 2025 6:00
``
<br>
