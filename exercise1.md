In GoLang, there are several tools for setting up CI pipelines that include testing, linting, and building.
For linting, there is golangci-lint, which is a customizable linter for Go. It can be used with most
popular code editores and CI systems and many linters.
	For testing, Go has a built in testing tool "go test" It allows to write and run tests for Go code.
There is also testify, which is a popular testing toolkit that enhances the standard testing package, with 
additional packages and assertions.
For building, there is go-build, which is the standard Go command for building executable binaries from 
the Go source code. There is Mage, which us a make-like build tool for go. It allows to define build 
targets in Go code, thus providing a more flexible and maintainable way to build a project.
Makefile is not Go-specific, makefiles are commonly used for defining build steps and dependencies in a
project. They can be used to orchestrate the build process. 
The alternatives for setting up a CI-pipeline on top of Jenkins and Github Actions are, for example,
Gitlab CI and Travis CI. These platforms allow to define and automate build, test and deployment process.
	There are pros and cons in self-hosted and cloud-based CI/CD services. In self-hosted environment, you
have full control over the infrastructure, configuration, resources and customization. However, this 
might be more time consuming, as well as not so easily scalable. Setting up the initial setup may also 
require more effort. In a cloud-based CI/CD, there are readily available CI/CD services that can handle 
infrastructure maintenance, updating and scalability. Integration with other cloud services is often 
easier. Cloud-based services often come with a cost, so it might be a more expensive solution in the 
long term. It also means that your CI/CD pipeline is is reliant on the provider's services. Data privacy 
might also be a concern for cloud-based CI/CD pipeline.