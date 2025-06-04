# eXtract
Extract headers and cookies data from a selected target URL
 
<br>

# Description 
HTTP headers and cookies are both used in the HTTP protocol to exchange information between a client and a server. HTTP headers are used to convey information about the request or response, such as content type, authorization, and caching instructions. Cookies are a specific type of header used to store small pieces of data on the client's computer to help the server identify the client and personalize their experience. 

<br>

![alt text](https://github.com/ghoste9624/eXtract/blob/main/files%2FScreenshot_20250604-062320_Termux.jpg)

<br>

# Installation 

<br>

```bash
git clone https://github.com/ghoste9624/eXtract
cd eXtract
python cookie.py -h
```

<br>

# Example Usage

<br>

* Display help message and exit

```bash
python cookie.py -h
```

<br>

* Display headers only from a target

```bash
python cookie.py https://github.com/ghoste9624/eXtract
```
<br>

* Display cookies only from a target

```bash
python cookie.py https://github.com/ghoste9624/eXtract --cookies
```
<br>

* Display both headers and cookies from a target

```bash
python cookie.py https://github.com/ghoste9624/eXtract --headers --cookies
```

<br>

# Updated On
``
June 4, 2025 6:00
``
<br>
