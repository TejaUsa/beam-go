##  to run the hello program
## go run hello.go

### Install GoLang and check for the Version
`go version`
## go version go1.18 windows/amd64d

### Get the SDK and the examples
`go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`

### Run wordcount (the below command didn't work for me)
`go install github.com/apache/beam/sdks/v2/go/examples/wordcount`

###  So, I used the following command to run
 `go run wordcount.go --input sample.txt --output counts`

 #### After running the above command, it asked me to get the following
 `go get github.com/apache/beam/sdks/v2/go/pkg/beam/runners/dataflow/dataflowlib@v2.37.0`
 ` go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0`

 ###  Now, Run the Word Count
 `go run wordcount.go --input sample.txt --output counts`
4. About how long did this take you?

It took around 30 minutes for me to complete.

5. What was the hardest part? 

Running the word count file was the hardest part for me as it asked me to get some more files from GitHub.