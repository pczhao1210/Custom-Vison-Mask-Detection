##Instruction##

1. Train your model from [Custom Vision](https://www.customvision.ai/projects);

2. Export you model as Dockerfile

3. Build your docker image (docker build -t <your image name> . )

4. Run your docker and map 8888 port to docker 80 port (docker run -p 8888:80 <your image name>)

5. Use Postman or THIS CODE to test
