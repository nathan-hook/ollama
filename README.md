TO DO

Move your compose file and this readme file to github.


You copied your docker-compose.yml file from the Open WebUI github repository:
https://github.com/open-webui/open-webui

You then started the two containers using:
$ docker-compose -f docker-compose.yml up -d

Then you had to create an account to login with.  You used a fake email address, test@test.com and 'password'
as the password.

Then you needed to download a model from Ollama:
https://ollama.com/library?sort=popular

## Downloading Models

This is super confusing and no longer as straight foward as it use to be...

Click on your Name Icon in the upper left -> Admin Panel

Click on Settings tab.

Click on side Connections tab.

Click on the little Wrench Icon.

FWIW, you have to be very clear on the name of the model you want to download.

You have downloaded:
* llama3:8b
* llama3.2:3b
* mistral:7b
* mistral-small:22b-instruct-2409-q2_K

Then you set llama3.2:3b or llama3:8b as your default model.

llama3.2:3b is suppose to be a really tiny model that you are using to experiment with using the Continue Intellij plugin:
https://github.com/ollama/ollama/issues/7423


Image Generation

Takes a bit of setup.

https://docs.openwebui.com/tutorial/images/



IDEAS

Try adding a new docker container for testing out Fabric:
https://github.com/danielmiessler/fabric

Fabric is a CLI that has pre-built prompts that allow you to feed information into an AI model and get a summary of that information.


"okay, but I want GPT to perform 10x for my specific use case" - Here is how - AI Jason
Fine Tuning vs Knoweldge Base (Embedding)
https://youtu.be/Q9zv369Ggfk?si=_G3WfpBlAnbFE6xf

"How to give GPT my business knowledge?" - Knowledge embedding 101 - AI Jason
https://youtu.be/c_nCjlSB1Zk?si=jZTBIx6TvbaDYfSl


