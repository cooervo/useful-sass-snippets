# Useful-sass-snippets

just some useful Sass snippets:
```

/* centers everything inside the container usually a div */  
@mixin horizontal-center-everything-inside-container($width) {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: $width;
}    

/* makes the text use elipsis (...) if text is bigger than container width */ 
@mixin elipsis-text($width) {
  width: $width;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
} 



```
