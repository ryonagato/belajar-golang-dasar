
Step by step to execute Go function using Docker
1. docker build -t belajargolangdasar .
2. Modify Dockerfile in line 10. Change 'go file' to name of specific go file
    RUN go build -v -o /usr/local/bin/app 'go file'
3. docker run --rm belajargolangdasar
4. Remove image if you want to execute another go file