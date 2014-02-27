My maven repository




<!-- 具体依赖项目--> 

        <repositories> 
          <repository> 
            <id>maven-repository</id> 
            <url>https://raw.github.com/soarcn/mvn/master</url> 
          </repository> 
        </repositories> 

        <dependency>
            <groupId>com.notificationcompact</groupId>
            <artifactId>library</artifactId>
            <version>1.0</version>
            <type>apklib</type>
        </dependency>

        <dependency>
            <groupId>com.cocosw.framework</groupId>
            <artifactId>framework</artifactId>
            <version>1.0-SNAPSHOT</version>
            <type>apklib</type>
            <exclusions>
                <exclusion>
                    <artifactId>support-v4</artifactId>
                    <groupId>com.google.android</groupId>
                </exclusion>
            </exclusions>
        </dependency>
        
        <dependency>
            <groupId>android.support</groupId>
            <artifactId>compatibility-v4</artifactId>
            <version>18</version>
        </dependency>
