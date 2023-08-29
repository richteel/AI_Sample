# AI_Sample
AI Example using CodeProject.AI Server

These examples require the installation of the CodeProject.AI Server being installed on a machine accessible from the client machine running the samples. If the CodeProject.AI Server is running on a machine other than the one that the samples are run from, then the samples will need to be modified to point to the CodeProject.AI Server location. As an example, lines that contain "http://localhost:32168" or "http://localhost:5000" will need to be modified by replacing "localhost" with the IP Address or host name for the CodeProject.AI Server.

It is recommended to install the CodeProject.AI Server Docker image. If you do so, do not forget to set the ports for the services so that they are able to be accessed outside of the container.

## Brief description of the contents

- Sample_01
	- AI_Sample.html: A test to see which APIs are accessible from current installation. Line 50, "fetch('http://localhost:32168/v1/text/summarize', {", was changed for each API listed in lines 16 to 47 to determine which ones worked for my instance.


## References

- [CodeProject.AI Server](https://www.codeproject.com/ai/docs/)
- [CodeProject.AI Server: AI the easy way](https://www.codeproject.com/Articles/5322557/CodeProject-AI-Server-AI-the-easy-way)
- [API Reference - CodeProject.AI Server](https://www.codeproject.com/AI/docs/api/api_reference.html)