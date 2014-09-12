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

# Freemarker

## Cheat sheet
 * Missing value operator `??`, returns boolean
 * Has content operator `?has_content`, returns boolean
 * Default value operator `!`, return default value if the variable is missing (e.g. `model.data.str!"na"`)
 
 Note: `default`, `exists` and `if_exists` are all deprecated.
 For more information, Freemarker missing values [documentation](http://freemarker.org/docs/dgui_template_exp.html#dgui_template_exp_missing)

## Eclipse
If you are using [Eclipse IDE](http://www.eclipse.org/), you can download and use our [Formatter profile](https://raw.githubusercontent.com/Canadensys/canadensys-code-conventions/master/java/eclipse/canadensys-code-format.xml).To import it in your project go to `Project/Properties/Java Code Style/Formatter` and check 'Enable project specific settings'. Then, you can import the XML file and set it as active profile.
