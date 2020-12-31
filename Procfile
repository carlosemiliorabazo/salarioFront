web: java $JAVA_OPTS -jar target/dependency/jetty-runner.jar --port $PORT target/*.war


<build>
    <plugins>
       
                <execution>
                    <phase>package</phase>
                    <goals>
                        <goal>copy</goal>
                    </goals>
                    <configuration>
                        <artifactItems>
                            <artifactItem>
                                <groupId>org.eclipse.jetty</groupId>
                                <artifactId>jetty-runner</artifactId>
                                <version>9.3.3.v20150827</version>
                                <destFileName>jetty-runner.jar</destFileName>
                            </artifactItem>
                        </artifactItems>
                    </configuration>
                </execution>
            </executions>
        </plugin>
    </plugins>
</build>
