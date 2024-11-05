<?xml version="1.0" encoding="UTF-8"?>
<settings xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
	<localRepository>C:\Users\ecmo\.m2\repository</localRepository>
	<pluginGroups>
		<pluginGroup>org.sonarsource.scanner.maven</pluginGroup>
	</pluginGroups>
	<servers>
	    <server>
            <id>Artifact-release</id>
            <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
		<server>
            <id>all-nexus-dependencies</id>
          <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
		<server>
            <id>Maven-Dependencies</id>
          <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
	</servers>
	<profiles>
		<profile>
	      <id>definedInM2SettingsXML</id>
	      <activation>
	        <activeByDefault>true</activeByDefault>
	      </activation>
	      <properties>
	        <maven.wagon.http.ssl.insecure>true</maven.wagon.http.ssl.insecure>
	        <maven.wagon.http.ssl.allowall>true</maven.wagon.http.ssl.allowall>
	        <maven.wagon.http.ssl.ignore.validity.dates>true</maven.wagon.http.ssl.ignore.validity.dates>
	      </properties>
	    </profile>
		<profile>
			<repositories>
				<repository>
				  <id>Artifact-release</id>
				  <name>Artifact Release</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/libs-release-local/</url>
				</repository>
				<repository>
				  <id>all-nexus-dependencies</id>
				  <name>all-dependencies</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/all-nexus-dependencies/</url>
				  
				</repository>
				<repository>
				  <id>Maven-Dependencies</id>
				  <name>Maven-Dependencies</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/Maven-dependencies/</url>
				</repository>
			</repositories>
			<id>artifactory</id>
		</profile>
		<profile>
            <id>sonar</id>
            <activation>
                <activeByDefault>true</activeByDefault>
            </activation>
            <properties>
                <!-- Optional URL to server. Default value is http://localhost:9000 -->
                <!-- <sonar.host.url>
                  http://myserver:9000
                </sonar.host.url> -->
            </properties>
        </profile>
	</profiles>
	<activeProfiles>
		<activeProfile>artifactory</activeProfile>
	</activeProfiles>
	<proxies>
    <!--proxy>
      <id>my-proxy</id>
      <active>true</active>
      <protocol>http</protocol>
      <host>127.0.0.1</host>
      <port>8080</port>
      <username>eric.martinez@gft.com</username>
      <password>gFTemp_EM*19</password>
    </proxy-->
  </proxies>
  
  
</settings>




<?xml version="1.0" encoding="UTF-8"?>
<settings xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
	<localRepository>C:\Users\ecmo\.m2\repository</localRepository>
	<pluginGroups>
		<pluginGroup>org.sonarsource.scanner.maven</pluginGroup>
	</pluginGroups>
	<servers>
	    <server>
            <id>Artifact-release</id>
            <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
		<server>
            <id>all-nexus-dependencies</id>
          <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
		<server>
            <id>Maven-Dependencies</id>
          <username>sabadell-developer</username>
            <password>Sabadell-developer1</password>
        </server>
	</servers>
	<profiles>
		<profile>
	      <id>definedInM2SettingsXML</id>
	      <activation>
	        <activeByDefault>true</activeByDefault>
	      </activation>
	      <properties>
	        <maven.wagon.http.ssl.insecure>true</maven.wagon.http.ssl.insecure>
	        <maven.wagon.http.ssl.allowall>true</maven.wagon.http.ssl.allowall>
	        <maven.wagon.http.ssl.ignore.validity.dates>true</maven.wagon.http.ssl.ignore.validity.dates>
	      </properties>
	    </profile>
		<profile>
			<repositories>
				<repository>
				  <id>Artifact-release</id>
				  <name>Artifact Release</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/libs-release-local/</url>
				</repository>
				<repository>
				  <id>all-nexus-dependencies</id>
				  <name>all-dependencies</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/all-nexus-dependencies/</url>
				  
				</repository>
				<repository>
				  <id>Maven-Dependencies</id>
				  <name>Maven-Dependencies</name>
				  <url>https://tools.devops.onp-bsi-bsi-0001-k801.mx.bsab/artifactory/Maven-dependencies/</url>
				</repository>
			</repositories>
			<id>artifactory</id>
		</profile>
		<profile>
            <id>sonar</id>
            <activation>
                <activeByDefault>true</activeByDefault>
            </activation>
            <properties>
                <!-- Optional URL to server. Default value is http://localhost:9000 -->
                <!-- <sonar.host.url>
                  http://myserver:9000
                </sonar.host.url> -->
            </properties>
        </profile>
	</profiles>
	<activeProfiles>
		<activeProfile>artifactory</activeProfile>
	</activeProfiles>
	<proxies>
    <!--proxy>
      <id>my-proxy</id>
      <active>true</active>
      <protocol>http</protocol>
      <host>127.0.0.1</host>
      <port>8080</port>
      <username>eric.martinez@gft.com</username>
      <password>gFTemp_EM*19</password>
    </proxy-->
  </proxies>
  
  
</settings>




<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    
    <groupId>com.example</groupId>
    <artifactId>spring-boot-3-demo</artifactId>
    <version>0.0.1-SNAPSHOT</version>
    <name>spring-boot-3-demo</name>
    <description>Spring Boot 3.x Demo Project with Jakarta EE</description>
    
    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>3.2.0</version>
        <relativePath/>
    </parent>
    
    <properties>
        <java.version>17</java.version>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
    </properties>
    
    <dependencies>
        <!-- Spring Boot Starters -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
        
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-data-jpa</artifactId>
        </dependency>
        
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-validation</artifactId>
        </dependency>
        
        <!-- Jakarta EE API -->
        <dependency>
            <groupId>jakarta.platform</groupId>
            <artifactId>jakarta.jakartaee-api</artifactId>
            <version>10.0.0</version>
            <scope>provided</scope>
        </dependency>
        
        <!-- Database -->
        <dependency>
            <groupId>com.h2database</groupId>
            <artifactId>h2</artifactId>
            <scope>runtime</scope>
        </dependency>
        
        <!-- Development Tools -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
            <scope>runtime</scope>
            <optional>true</optional>
        </dependency>
        
        <dependency>
            <groupId>org.projectlombok</groupId>
            <artifactId>lombok</artifactId>
            <optional>true</optional>
        </dependency>
        
        <!-- Test Dependencies -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-test</artifactId>
            <scope>test</scope>
        </dependency>
    </dependencies>
    
    <build>
        <plugins>
            <plugin>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-maven-plugin</artifactId>
                <configuration>
                    <excludes>
                        <exclude>
                            <groupId>org.projectlombok</groupId>
                            <artifactId>lombok</artifactId>
                        </exclude>
                    </excludes>
                </configuration>
            </plugin>
        </plugins>
    </build>
</project>





<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>3.2.0</version>
        <relativePath/>
    </parent>
    
    <groupId>com.example</groupId>
    <artifactId>soap-client</artifactId>
    <version>1.0.0</version>
    <name>soap-client</name>
    <description>Spring Boot SOAP Client with Jakarta</description>
    
    <properties>
        <java.version>17</java.version>
        <jakarta.xml.ws-api.version>4.0.0</jakarta.xml.ws-api.version>
        <jakarta.jws-api.version>3.0.0</jakarta.jws-api.version>
    </properties>
    
    <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
        
        <!-- Jakarta XML Web Services API -->
        <dependency>
            <groupId>jakarta.xml.ws</groupId>
            <artifactId>jakarta.xml.ws-api</artifactId>
            <version>${jakarta.xml.ws-api.version}</version>
        </dependency>
        
        <!-- Jakarta Web Services API -->
        <dependency>
            <groupId>jakarta.jws</groupId>
            <artifactId>jakarta.jws-api</artifactId>
            <version>${jakarta.jws-api.version}</version>
        </dependency>
        
        <!-- Implementación de Jakarta XML Web Services -->
        <dependency>
            <groupId>com.sun.xml.ws</groupId>
            <artifactId>jaxws-rt</artifactId>
            <version>4.0.0</version>
        </dependency>
        
        <!-- Jakarta Annotations API -->
        <dependency>
            <groupId>jakarta.annotation</groupId>
            <artifactId>jakarta.annotation-api</artifactId>
            <version>2.1.1</version>
        </dependency>
        
        <!-- JAXB Runtime for XML Processing -->
        <dependency>
            <groupId>org.glassfish.jaxb</groupId>
            <artifactId>jaxb-runtime</artifactId>
        </dependency>
        
        <!-- Spring WS Core -->
        <dependency>
            <groupId>org.springframework.ws</groupId>
            <artifactId>spring-ws-core</artifactId>
        </dependency>
        
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-test</artifactId>
            <scope>test</scope>
        </dependency>
    </dependencies>
    
    <build>
        <plugins>
            <plugin>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-maven-plugin</artifactId>
            </plugin>
            
            <!-- CXF Maven Plugin para generar clases Java desde WSDL -->
            <plugin>
                <groupId>org.apache.cxf</groupId>
                <artifactId>cxf-codegen-plugin</artifactId>
                <version>4.0.3</version>
                <executions>
                    <execution>
                        <id>generate-sources</id>
                        <phase>generate-sources</phase>
                        <configuration>
                            <sourceRoot>${project.build.directory}/generated-sources/cxf</sourceRoot>
                            <wsdlOptions>
                                <wsdlOption>
                                    <wsdl><!-- URL de tu WSDL aquí --></wsdl>
                                    <packagenames>
                                        <packagename>com.example.soap.client.generated</packagename>
                                    </packagenames>
                                </wsdlOption>
                            </wsdlOptions>
                        </configuration>
                        <goals>
                            <goal>wsdl2java</goal>
                        </goals>
                    </execution>
                </executions>
            </plugin>
        </plugins>
    </build>
</project>

import java.io.IOException;
import java.nio.file.*;
import java.util.*;
import java.util.stream.Collectors;

public class ProjectComparator {
    public static void main(String[] args) {
        String legacyProjectPath = "ruta/a/proyecto_legacy"; // Cambia a la ruta de tu proyecto legacy
        String refactoredProjectPath = "ruta/a/proyecto_refactorizado"; // Cambia a la ruta de tu proyecto refactorizado

        try {
            // Obtener lista de clases en ambos proyectos
            Map<String, String> legacyClasses = getClassStructure(legacyProjectPath);
            Map<String, String> refactoredClasses = getClassStructure(refactoredProjectPath);

            // Comparar clases
            System.out.println("Comparación de Clases:");
            compareClasses(legacyClasses, refactoredClasses);

            // Comparar dependencias
            System.out.println("\nComparación de Dependencias:");
            compareDependencies(legacyProjectPath, refactoredProjectPath);

        } catch (IOException e) {
            e.printStackTrace();
        }
    }

    // Método para obtener la estructura de clases y sus paquetes en un proyecto
    private static Map<String, String> getClassStructure(String projectPath) throws IOException {
        Map<String, String> classMap = new HashMap<>();

        Files.walk(Paths.get(projectPath))
            .filter(Files::isRegularFile)
            .filter(file -> file.toString().endsWith(".java"))
            .forEach(file -> {
                String packagePath = file.getParent().toString();
                String className = file.getFileName().toString().replace(".java", "");
                classMap.put(className, packagePath);
            });

        return classMap;
    }

    // Método para comparar clases y su ubicación en ambos proyectos
    private static void compareClasses(Map<String, String> legacyClasses, Map<String, String> refactoredClasses) {
        Set<String> legacyOnly = new HashSet<>(legacyClasses.keySet());
        Set<String> refactoredOnly = new HashSet<>(refactoredClasses.keySet());

        legacyOnly.removeAll(refactoredClasses.keySet()); // Clases eliminadas o renombradas
        refactoredOnly.removeAll(legacyClasses.keySet()); // Clases nuevas o renombradas

        System.out.println("Clases eliminadas o renombradas en el refactor:");
        legacyOnly.forEach(className -> 
            System.out.println(" - " + className + " en paquete " + legacyClasses.get(className)));

        System.out.println("\nClases nuevas en el refactor:");
        refactoredOnly.forEach(className -> 
            System.out.println(" + " + className + " en paquete " + refactoredClasses.get(className)));

        System.out.println("\nClases que cambiaron de paquete:");
        legacyClasses.forEach((className, legacyPackage) -> {
            String refactoredPackage = refactoredClasses.get(className);
            if (refactoredPackage != null && !legacyPackage.equals(refactoredPackage)) {
                System.out.println(" * " + className + ": de " + legacyPackage + " a " + refactoredPackage);
            }
        });
    }

    // Método para comparar dependencias entre dos proyectos (Maven o Gradle)
    private static void compareDependencies(String legacyProjectPath, String refactoredProjectPath) throws IOException {
        List<String> legacyDependencies = getDependencies(legacyProjectPath);
        List<String> refactoredDependencies = getDependencies(refactoredProjectPath);

        Set<String> legacyOnly = new HashSet<>(legacyDependencies);
        Set<String> refactoredOnly = new HashSet<>(refactoredDependencies);

        legacyOnly.removeAll(refactoredDependencies); // Dependencias eliminadas o cambiadas
        refactoredOnly.removeAll(legacyDependencies); // Dependencias nuevas o cambiadas

        System.out.println("Dependencias eliminadas o cambiadas en el refactor:");
        legacyOnly.forEach(dep -> System.out.println(" - " + dep));

        System.out.println("\nDependencias nuevas en el refactor:");
        refactoredOnly.forEach(dep -> System.out.println(" + " + dep));
    }

    // Método para obtener la lista de dependencias de un proyecto (Maven o Gradle)
    private static List<String> getDependencies(String projectPath) throws IOException {
        Path mavenFile = Paths.get(projectPath, "pom.xml");
        Path gradleFile = Paths.get(projectPath, "build.gradle");

        List<String> dependencies = new ArrayList<>();
        if (Files.exists(mavenFile)) {
            dependencies = Files.readAllLines(mavenFile).stream()
                .filter(line -> line.trim().startsWith("<dependency>"))
                .collect(Collectors.toList());
        } else if (Files.exists(gradleFile)) {
            dependencies = Files.readAllLines(gradleFile).stream()
                .filter(line -> line.trim().startsWith("implementation") || line.trim().startsWith("api"))
                .collect(Collectors.toList());
        }
        return dependencies;
    }
}


<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>3.3.5</version>
		<relativePath/> <!-- lookup parent from repository -->
	</parent>
	<groupId>com.fifththird</groupId>
	<artifactId>WsdlClient</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<name>WsdlClient</name>
	<description>WsdlClient</description>
	<url/>
	<licenses>
		<license/>
	</licenses>
	<developers>
		<developer/>
	</developers>
	<scm>
		<connection/>
		<developerConnection/>
		<tag/>
		<url/>
	</scm>
	<properties>
		<java.version>17</java.version>
	</properties>
	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-devtools</artifactId>
			<scope>runtime</scope>
			<optional>true</optional>
		</dependency>
		<dependency>
			<groupId>com.h2database</groupId>
			<artifactId>h2</artifactId>
			<scope>runtime</scope>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web-services</artifactId>
			<exclusions>
				<exclusion>
					<groupId>org.springframework.boot</groupId>
					<artifactId>spring-boot-starter-tomcat</artifactId>
				</exclusion>
			</exclusions>
		</dependency>

	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>

			<!--plugin>
				<groupId>org.jvnet.jaxb2.maven2</groupId>
				<artifactId>maven-jaxb2-plugin</artifactId>
				<version>0.15.3</version>
				<executions>
					<execution>
						<goals>
							<goal>generate</goal>
						</goals>
					</execution>
				</executions>
				<configuration>
					<generatePackage>com.example.howtodoinjava.schemas.school</generatePackage>
					<generateDirectory>${project.basedir}/src/main/java</generateDirectory>
					<schemaDirectory>${project.basedir}/src/main/resources/wsdl</schemaDirectory>
					<schemaIncludes>
						<include>*.wsdl</include>
					</schemaIncludes>
				</configuration>
			</plugin-->

			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
			<!-- tag::wsdl[] -->
			<plugin>
				<groupId>com.sun.xml.ws</groupId>
				<artifactId>jaxws-maven-plugin</artifactId>
				<version>3.0.0</version>
				<executions>
					<execution>
						<goals>
							<goal>wsimport</goal>
						</goals>
					</execution>
				</executions>
				<configuration>
					<packageName>com.example.consumingwebservice.wsdl</packageName>
					<wsdlUrls>
						<wsdlUrl>http://localhost:8080/ws/countries.wsdl</wsdlUrl>
					</wsdlUrls>
					<sourceDestDir>${sourcesDir}</sourceDestDir>
					<destDir>${classesDir}</destDir>
					<extension>true</extension>
				</configuration>
			</plugin>
			<!-- end::wsdl[] -->

		</plugins>
	</build>

</project>


