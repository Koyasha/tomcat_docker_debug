1. Have Docker up and running.
2. Open and run the `docker-compose.yaml` file
3. Open http://localhost:8888/Tomcat_docker_debug-1.0-SNAPSHOT/api/hello-world to make sure the application is deployed
4. Run the `remote_tomcat_debug` configuration in the debug mode
5. Reopen http://localhost:8888/Tomcat_docker_debug-1.0-SNAPSHOT/api/hello-world
6. Observe how the debugger hits a breakpoint set in `src/main/java/com/example/tomcat_docker_debug/HelloResource.java`
