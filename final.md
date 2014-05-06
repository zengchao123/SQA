#zengchao 13126168
  we need to use at least three types of tests:
    1.unit tests - tests for individual units. If you give function A the inputs x, y and z, does it return the right 
value? These are cheap, easy and fast, and help you to understand that individual units of code work precisely as 
they are designed to work. 
    Most often unit tests are written by the developer that wrote the unit.
    2.system tests - do the individual units work together? This is where you test the business logic of your application,
and to test the contract between units ("if you provide the arguments x,y,z I'll return A" and "if you give me the wrong 
arguments I'll raise error B"). These help you to understand whether the individual units work together to accomplish a 
task. 
    system tests can take many forms, and there's not always a single solution that will work for a particular application. 
For example, if your site is a web site you can have service layer tests ("if I call the web API of my site, does it return
the right value") and presentation layer ("if I click on the button in the UI, does the form get posted to the proper URL?) 
tests.
    3.performance tests. Performance in this context could mean raw speed, or it could mean capacity ("can the website 
handle 1 million hits per day?"), system load, latency, etc.
    Performance tests are almost exclusively automated，and also watch system metrics such as CPU and memory utilization 
while your system tests are running. This isn't an ideal performance testing strategy, but it's good enough if you're
just starting out.
    At first, we should know something basic about Software quality assurance.
    In my opinion, software test is a part of Software quality assurance, if you want to make sure that the software will
complete with a high quality, the work you should do when the project is not exactly start and software test is at last.
    For example, reasonable requirement, excellent design and document of development is important and so on.
    Software testing is an investigation conducted to provide stakeholders with information about the quality of the product
or service under test. Test techniques include, but are not limited to the process of executing a program or application with 
the intent of finding software bugs (errors or other defects).
    Software testing can be stated as the process of validating and verifying that a computer program/application/product:
    1.meets the requirements that guided its design and development,
    2.works as expected,
    3.can be implemented with the same characteristics,
    4.and satisfies the needs of stakeholders. 
  Five things we should always keep in mind:
    1.	Understand what the software is supposed to do. 
    2.	Decide how to verify that it does. 
    3.	Agree your test strategy with the stake-holders: there should be people who care about whether you are testing the right things, they need to have confidence that you are doing so. 
    4.	Perform the verification 
    5.	Report the results, accurately, in enough detail to allow problems to be fixed 
 
