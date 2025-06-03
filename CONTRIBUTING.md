## How to Contribute

Contributing to this project is actually pretty simple compared some other projects. I like to keep it as simple as possible to avoid confusion and frustration. With that being said I do have just a few things to tell you about before you can start.

## Research

If you want to submit changes, please ensure that the references you are submitting are the most authoritative sources available.  Think RFC or official software or device documentation including versioning information instead of SpeedTest. Reputable forum discussions *may* be accepted with appropriate justification.

## Submitting Changes

Follow the formatting guidlines (below) and include a pull request, appropriately sized for review by a human, listing the changes you would like to include. 

Always write a clear log message for your commits.  One-line messages are fine for smaller changes, but anything beyond ten lines should look like this:

```
$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
```

## Formatting Guidelines

The format of the list is fairly straightforward. I optimize for readability.

* The pattern is Port, Protocol, Service, Note, Reference 
	* Port is a number
	* Protocol is something like tcp,udp,sctp etc.
	* Service is the lowercase service name if it exists. For example: "msp"
	* Note is the proper name of the service, program, or device i.e. "Message Send Protocol"
	* Reference is at minimum, the name of the reference document (RFC/Documentation) followed by a link to said reference document.

* All of these fields are comma separated. 
* Always check that there are no extra spaces between the commas (`1,2,3,4,5`), not (`1, 2, 3, 4, 5`).
* This is an open source project. I am a human who will review your submission, make it easy and nice to look at. While I'm sure that I *could* clean it up, I'd rather not have to. The chances of your submission being approved decreases proportionally according to how much extra work it causes me. :wink: 

Thanks for playing!
