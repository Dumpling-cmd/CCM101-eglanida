# Mission Reflection

This laboratory activity helped me understand the difference between traditional Virtual Machines and containers. Installing an operating system on a Virtual Machine usually requires more time because the VM needs its own operating system and virtualized hardware resources. In comparison, a Docker container can start much faster because it shares the host operating system kernel. During the activity, running an Nginx container required only a few Docker commands, which showed me how quickly applications can be deployed using containerization.

The port mapping `-p 8080:80` is necessary because the Nginx web server is listening on port 80 inside the container, while I accessed the service through port 8080 on the host environment. The mapping connects the host's port 8080 to the container's port 80. Without this mapping, I would not be able to access the Nginx service through `localhost:8080`.

When the `docker rm` command is used, the specified stopped container is removed from Docker. The container itself and its writable container layer are deleted. This is different from simply stopping the container because stopping only changes its running state while keeping the container available for later use.

Containerization can also improve collaboration between software developers and IT operations teams. Developers can package an application and its dependencies into a container, while operations teams can run the same containerized application in different environments. This supports the DevOps approach by making deployment more consistent and easier to reproduce.

My GitHub portfolio is also evolving as I complete each laboratory activity. Instead of only containing individual tasks, it is becoming an organized record of my cloud computing skills. Laboratory 4 adds practical Docker and containerization experience to the previous cloud computing activities. Keeping the files, documentation, and screenshots organized also makes it easier to demonstrate what I have learned.
