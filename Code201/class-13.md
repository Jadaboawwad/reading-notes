## 1.  The Past, Present, and Future of Local Storage for Web Applications :

        in this part we will discuss the following points

* What is HTML5 Storage.
* How to check for HTML5 Storage
* How to track changes to HTML5 Storage.

<br/>

                           The beginning of Part One

### 1.1: HTML5 Storage is:

* it’s a way for web pages to store named key/value pairs locally, within the client web browser. 

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

### 1.2 : this is how to check for HTML5 Storage:

```javascript
function supports_html5_storage() {
    try {
        return 'localStorage' in window && window['localStorage'] !== null;
    } catch (e) {
        return false;
    }
}
```

or 

```javascript
if (Modernizr.localstorage) {
    // window.localStorage is available!
} else {
    // no native support for HTML5 storage :(
    // maybe try dojox.storage or a third-party solution
}
```

### 1.3 : We can track the changes in the html5 storage as :

If you want to keep track programmatically of when the storage area changes, you can trap the storage event.

```javascript
if (window.addEventListener) {
    window.addEventListener("storage", handle_storage, false);
} else {
    window.attachEvent("onstorage", handle_storage);
};
```

<br/>

                           The end of Part One

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
