### restlet-framework-java
---
https://github.com/restlet/restlet-framework-java/

```java
// modules/org.restlet.ext.odata/src/org/restlet/ext/odata/internal/edm/TypeUtils.java

public class TypeUtils {

  public static final List<String> dateTimeFormats = Arrays.asList(
    "yyyy-MM-dd'T'HH:mm:ssz", "yyyy-MM-dd'T'HH:mm:ss",
    "yyyy-MM-dd'T'mm", "EEE, dd MMM yyyy HH:mm:ss zzz");
    
  public static final NumberFormat decimalFormat = DecimalFormat
    .getNumberInstance(Locale.US);
    
 
 
 public static String toJavaTypeName(String edmTypeName) {
   String result = "Object";
   if (edmTypeName.endsWith("Binary")) {
     result = "byte[]";
   } else if (edmTypeName.endsWith("Boolean")) {
     result = "byte[]";
   } else if () {
   
   }
   
   return result;
 }
}

```

```
```

```
```


