<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Biggner Guide to Create Docker Image</title>
</head>
<body>
    <h1>>Biggner Guide to Create Docker Image</h1>
    <p>Brief description of your project.</p>
    <h2>Table of Contents</h2>
        <li>Clone this repository.</li>
        <pre><code>git clone https://github.com/iamrohanmane/temp_docker.git</code></pre>
        <li>Change to the project directory.</li>
        <pre><code>cd yourproject</code></pre>
    </ol>
    <h2 id="usage">Usage</h2>
    <p>Explain how to use your project, including any configuration options, settings, or command-line arguments. Provide examples and use cases.</p>
    <h2 id="docker-commands">Docker Commands</h2>
    <p>If your project uses Docker for containerization, provide clear instructions on how to build and run the Docker container. Include any environment variables, volume mounts, or other relevant information.</p>
    <h3>Build the Docker Image</h3>
    <p>To build the Docker image, use the following command:</p>
    <pre><code>docker build -t project-name:tag .</code></pre>
    <p>Replace <code>project-name</code> with your project's name and <code>tag</code> with an appropriate version or tag for your Docker image.</p>
    <h3>Run the Docker Container</h3>
    <p>To run the Docker container, use the following command:</p>
    <pre><code>docker run -d -p 8080:80 project-name:tag</code></pre>
    <p>Replace <code>project-name</code> and <code>tag</code> with the same values used during image building. This example assumes your application listens on port 80 inside the container.</p>
    <p>Access the Application</p>
    <p>Once the Docker container is running, you can access your application in a web browser by navigating to <a href="http://localhost:8080">http://localhost:8080</a> or the appropriate URL.</p>
</body>
</html>

