Docker was used to encapsulate the Java application in a self-contained, reproducible environment. Instead of relying solely on local configurations, a Dockerfile was created to specify the runtime requirements by selecting an appropriate base image, setting up a dedicated application directory, copying the compiled Java files into the container, and defining the command to execute the application. This approach allowed the developers to build a Docker image that includes all necessary dependencies and configurations, which could then be deployed and run consistently across different systems using commands like docker build and docker run. Ultimately, Docker streamlined the process by automating both the setup and execution of the Java program, ensuring that it operated reliably regardless of the underlying host environment.
