<repositories>
  <repository>
   <id>boundless</id>
   <name>Boundless Maven Repository</name>
   <url>https://repo.boundlessgeo.com/main/</url>
   <!-- contains snapshot and release (including third-party-dependences)               -->
   <!-- Restlet maven Repository (http://maven.restlet.org)                             -->
   <!-- ucar (https://artifacts.unidata.ucar.edu/content/repositories/unidata-releases) -->
   <snapshots>
     <enabled>true</enabled>
   </snapshots>
   <releases>
     <enabled>true</enabled>
   </releases>
  </repository>
  
  <repository>
    <id>osgeo</id>
    <name>Open Source Geospatial Foundation Repository</name>
    <url>http://download.osgeo.org/webdav/geotools/</url>
    <!-- release repository used by geotools (and third-party dependencies) -->
  </repository>
   
   <repository>
      <id>geosolutions</id>
      <name>geosolutions repository</name>
      <url>http://maven.geo-solutions.it/</url>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
     <releases>
       <enabled>true</enabled>
     </releases>
    </repository>
 </repositories>
