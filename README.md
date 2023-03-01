# HTTP

## How the internet works?


### Networks basics
NETWORK: Is simply two computers that are linked together somehow.
Typically there's a physical connection between the two computers and that is what we call the router so there's a piece of equipment that's only. There's a pice of equipment that's only job is sort of to talk to one another and send traffic back and forth between various computres on a network.
Now there's also technology a lot of routers these days are also routers and also Wi-Fi gateways that can also push internet signals wirelessly but there's always some sort of interface that connects these two computers together. One step futher and we of across the entire globe that is what call a **world wide web** or **www** so that's a global network of computers that are interconnected across cities, sates or even contries and oceans.

Pretty easy to think about my computer being connected to my computer in my office or maybe colleges could be connected. 

The reason the internet is able to works so quickly. 

Once the internet reaches your home typically it's not on fibre optic cables those are typically in these treanches which we call internet backbone once the internet reaches your house it typically runs over an electrial signal to go actually into your house and that reavels ver quicly but not as fasta as the speed of ligth in some newer developments you'll actually see fiber connectivity going straight into the homes so that's something that almosto all new developments are vuilding to it but a lot of the older homes don't have the infrasctuture to have fiber-optic cabel run directly to each individual address 
### What is HTTP? 

It's not initially about what HTTP is that's something that you probably type in your web browser.

HTTPS is simply a protocol and the protocol here: 

**HTTP** **H**yper **T**ext **T**ransfer **P**rotocl 

and it's a set of rules that govern how two computers are supposed to talk to one another so in the simplest form we have a computer and the computer that you're working ar of that your'e consuming is what call the clinet2 machine sometimes that's also referred to as the local machine now the computer that you're interfacing with that acually houses the website files that you're pulling up is what call the server or the remote computer and of course we have the router in between the two. 

What happens is the client machine makes a **request** to the server and the server machine has a **response** that it sends back to the client so we have a request and a response and those two whings always happend over HTTP. 
What happends herw is when this request happends so this guy's gonna send a request over here and this server is basically gonna ask itself a question it says do i have the files ehat the client machine is requesting so it's gonna respond back and send back a response with sort of yes or no, and if it has the files that were requested it of course sends those files along if it does not have the files that were requested it will send an error or a satus code so, the server always reponds with what is known as a status code and those satuts codes are simply three-difit numbers and that helps the client to know you know your or no correct or incorrect of if the files were found or not so let's take a look at some of those status codes of the server can send it back:

## HTTP STATUS CODES

- 1xx Informational
- 2xx Success
    - 200 (Success)
- 3xx Redirection:  website that redirects to another website 
- 4xx Client Error 
    - 404 (Page not found)
- 5xx Server error 

### HTTP REQUEST 

Each request sent by the HTTP client remove there's a request and reponse that request goes though what's known as header. 

The headear is the first few lines of the request that get that fet sent it's made up of three parts: 

- Star line:  GET/background.pngHTTP/1.0
- Headers: User-Agent: Mozilla/5.0
- Body: None for GET

Start line is made up of you can see three portions here then we have the actual 
headers which has some additional infroamtion and then we have the body.

Start line: 

```

              GET     /     background.pngHTTP      /       1.0
             method               target                   version        
```
start with what we call the methos so this is how the request is haveing put togerther it's typically wither get or post, next we have what we call the target so this is which exact file am i trying to locate and then the third paramter is the version of HTTP that we're using HTTP has severals versions one 1.12 and even version 3 is under development so that's all parts of the very sirst line that gets sent.


Headers: 
```
User-Agent: Mozilla/5.0      
```
Typically just has additional information about the request so in this little sample here you can see we have the user agent that's what web browser.
I'm using that's sent to the server becasuse that's helpful information for the server to be 



 