Instruction
-----------

  pax-run.sh scan-composite:file:karaf-1.6.0.composite scan-composite:file:jersey-osgi.composite

Testing
-------

* Jersey
  * check out, build and deploy the following jersey samples: 
  https://jersey.dev.java.net/svn/jersey/trunk/jersey/samples/osgi-http-service. 
  * Point your browser to : http://localhost:8080/jersey-http-service/status

* Camel
  osgi:install -s mvn:org.apache.camel/camel-example-osgi/2.3.0 
