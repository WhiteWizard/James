James
=====

Static PHP source code analyzer


-=< Purpose >=-

James is a static code analyzer for PHP that checks for insecure routing of input to sinks. 
Common attack vectors such as XSS and SQL injection rely on faulty code that doesn't properly 
filter input data before sending it to another application ("sink"). James identifies these 
vulnerabilities and can recommend solutions.

-=< Scope >=-

James includes a default set of language-specific sinks and can be extended with custom sinks 
for particular applications. James will analyze both procedural files and functions, so it is 
compatible with both object-oriented and procedural coding styles. James can be configured to 
scan one or multiple files at a time.

-=< Implementation Details >=-

James is written in PHP and should be run on a local development server (preferably one 
firewalled from the Internet).
