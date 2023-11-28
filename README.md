# jenkins-docker-example

Integrating GitHub code with pipeline in Jenkins tool.

1. Install Java
2. Install Jenkins and start service.
3. Install docker and start service.

**Plugins to be installed:**

1. maven integration
2. docker pipeline and other related docker plugins if needed.

3. If maven wasn't installed in target server then include maven tool in pipeline as,

   tools {
      maven 'mavenpluginname'
   }

Create and enable webhook between github and Jenkins server to make it s Continuos Integration with jenkins Pipeline.
