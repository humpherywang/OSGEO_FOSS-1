  <repositories>
    <repository>
      <id>central.maven.org</id>
      <name>Central Maven repository</name>
      <url>http://central.maven.org/maven2</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
    
    <repository>
      <id>osgeo</id>
      <name>OSGeo Nexus Release Repository</name>
      <url>https://repo.osgeo.org/repository/release/</url>
      <!-- contains release (including third-party-dependences)                            -->
      <!-- ucar (https://artifacts.unidata.ucar.edu/content/repositories/unidata-releases) -->
      <!-- geosolutions (http://maven.geo-solutions.it/)                                   -->
      <snapshots><enabled>false</enabled></snapshots>
      <releases><enabled>true</enabled></releases>
    </repository>

    <repository>
      <id>osgeo-snapshot</id>
      <name>OSGeo Nexus Snapshot Repository</name>
      <url>https://repo.osgeo.org/repository/snapshot/</url>
      <snapshots><enabled>true</enabled></snapshots>
      <releases><enabled>false</enabled></releases>
    </repository>
    
    <repository>
      <id>geosolutions</id>
      <name>GeoSolutions Repository</name>
      <url>http://maven.geo-solutions.it</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
    
    <repository>
      <id>maven-restlet</id>
      <name>Restlet Maven Repository</name>
      <url>http://maven.restlet.org</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
  </repositories>
