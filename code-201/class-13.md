# Local Storage

## Local Storage and How To Use It On Websites

1. **Why would a developer use local storage for a web application?**

    Local storage allows your make elements of a web application persist between sessions without having to rely on server side storage. This allows to storage without necessitating users logins and can also reduce bandwidth between the server and user client.

2. **What information should not be stored in local storage?**

    You should not store information that should be kept private such as user information or security related information like passwords.

3. **Local storage can store what type of data? How would you convert it to that type before storing?**

    Local storage can only store strings. You can convert it before storing it using the `JSON.stringify()` method.

## Things I want to know more about

- To efficiently convert and parse strings to and from local storage

## References

- [Smashing Magazine: Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
- [Dive Into HTML 5: “The Past, Present, and Future of Local Storage for Web Applications”](https://diveinto.html5doctor.com/storage.html)
