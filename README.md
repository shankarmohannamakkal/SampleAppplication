This is the sample ASP.NET Core service application which is running in kestreal server.

Steps for create a docker image in linix container

1. Navigate to the Dockerfile folder at SampleApplication
2. docker build -t sampleapp .
3. docker run -it --rm -p 5000:80 --name aspnetcore_sample sampleapp
4. Go to http://localhost:5000/hellow in a browser to test the app. It should display `Hello!`

The same image is publically available `docker pull shankarmohan/aspnetapp:1.0`
