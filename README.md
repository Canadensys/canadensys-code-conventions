canadensys-code-conventions
===========================

Canadensys code conventions

# Java

## Cheat sheet
 * File encoding is UTF-8
 * Indentation is one Tab
 * Blocks are using "Egyptian brackets" style

```java
public class Example {
    private String var;
    
    public Example(String initVar){
        if(var != null){
            var = initVar;
        }
        else {
            var = "empty";
        }
    }
}
```

For everything not covered by the cheat sheet, please refer to [Google Java Style] (https://google-styleguide.googlecode.com/svn/trunk/javaguide.html).

## Eclipse
If you are using [Eclipse](http://www.eclipse.org/) IDE, you can download and use our Formatter profile. You can import it in your project in Project/Properties/Java Code Style/Formatter after you 'Enable project specific settings'.
