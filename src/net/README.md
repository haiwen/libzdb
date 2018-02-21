# Unsafe characters
The URL.re contains a comment.
```
/* Unsafe URL characters: [00-1F, 7F-FF] <>\"#%{}|\\^[] ` */
```

For some reason this is breaking the re2c. And I can not find a way to tell re2c to ignore C style comments.
So I removed this comment from the .re file
