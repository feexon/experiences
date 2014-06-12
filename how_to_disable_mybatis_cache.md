## How to disable mybatis cache
set two settings into <settings> in mybatis-config.xml
```xml
<settings>
     <setting name="cacheEnabled" value="false"/>
     <setting name="localCacheScope" value="STATEMENT"/>
</settings>
```
