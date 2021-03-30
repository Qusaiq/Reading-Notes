# Local Storage

### What is HTML Web Storage?
***With web storage, web applications can store data locally within the user's browser.***

- Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

- Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

- Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

### HTML Web Storage Objects
***HTML web storage provides two objects for storing data on the client:***

1, window.localStorage - stores data with no expiration date
2. window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)
Before using web storage, check browser support for localStorage and sessionStorage:
```
if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}
```

### Web Storage interfaces
1. ***Storage***
Allows you to set, retrieve and remove data for a specific domain and storage type (session or local.)

2. ***Window***
The Web Storage API extends the ```Window``` object with two new properties — ```Window.sessionStorage``` and ```Window.localStorage``` — which provide access to the current domain's session and local ```Storage``` objects respectively, and a ```Window.onstorage``` event handler that fires when a storage area changes (e.g. a new item is stored.)

3. ***StorageEvent***
The storage event is fired on a document's ```Window``` object when a storage area changes.

### Examples
To illustrate some typical web storage usage, we have created a simple example, imaginatively called Web Storage Demo. The landing page provides controls that can be used to customize the color, font and decorative image. When you choose different options, the page is instantly updated; in addition your choices are stored in ```localStorage```, so that when you leave the page then load it again later on your choices are remembered.

In addition, we have provided an event output page — if you load this page in another tab, then make changes to your choices in the landing page, you'll see the updated storage information outputted as the ```StorageEvent``` is fired.