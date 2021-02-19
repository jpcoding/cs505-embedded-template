# cs505-embedded-template

## Building and running package
The class VM has Java but not Maven, which is used for building the package.  

To install Maven run 
`mvn clean package
cd target
java -jar cs505-embedded-template-1.0-SNAPSHOT.jar`

Then run ./run.sh to build and start the package.

You will see lots of output the first time you build the package, as Maven is pulling down all dependencies.  The process will build a Java Jar located in the target directory (cs505-embedded-template/target/cs505-embedded-template-1.0-SNAPSHOT.jar)

Once built you will see something like this:
<code>
Starting Database...
Database Started...
Starting Web Server...
Feb 19, 2021 8:46:11 AM org.glassfish.grizzly.http.server.NetworkListener start
INFO: Started listener bound to [0.0.0.0:9000]
Feb 19, 2021 8:46:11 AM org.glassfish.grizzly.http.server.HttpServer start
INFO: [HttpServer] Started.
Web Server Started..
<code>

