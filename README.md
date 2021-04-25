# Realtime Chat Application

### [Live Site](tinyurl.com/gossip-chat-app)

![image](https://user-images.githubusercontent.com/49511150/115971730-c75e6980-a567-11eb-9638-8a78cdaf7cd8.png)

## RealTime Chat
![Screenshot (1674)](https://user-images.githubusercontent.com/49511150/115971843-713df600-a568-11eb-9475-05fcef6b430f.png)

## AIM 
To create a full Realtime Chat Application

## Working of the Project
With sockets, when the server receives a new message it will send it to the client and notify them, bypassing the need to send requests between client and server.

## Front end 
### React
> **React** is a JavaScript library for building user interfaces. It is used to build single page applications. React allows us to create reusable UI components. Read more about it [here](https://reactjs.org/)

## Backend 
### NodeJS + Socket.io web socket library + Heroku

>**Node.js** is an open source server environment. It runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.). Node.js uses JavaScript on the server. Read more about it [here] (https://nodejs.org/en/)

>>#### Why did we choose NodeJS?
- Here is how PHP or ASP handles a file request:
- Sends the task to the computer's file system.
- Waits while the file system opens and reads the file.
- Returns the content to the client.
- Ready to handle the next request.
- Here is how Node.js handles a file request:
- Sends the task to the computer's file system.
- Ready to handle the next request.
- When the file system has opened and read the file, the server returns the content to the client.
- Node.js eliminates the waiting, and simply continues with the next request.
- Node.js runs single-threaded, non-blocking, asynchronously programming, which is very memory efficient.

> **Socket.IO** enables real-time bidirectional event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed. Socket.IO is built on top of the WebSockets API (Client side) and Node.js. It is one of the most depended upon library on npm (Node Package Manager). Read more about it [here](https://socket.io/)

>>#### Working of Socket.io
>>>To establish the connection, and to exchange data between client and server, Socket.IO uses Engine.IO. This is a lower-level implementation used under the hood. Engine.IO is used for the server implementation and Engine.IO-client is used for the client.

> **Heroku** 
Heroku is a PaaS platform that offers support for several programming languages. It currently supports Node.js, PHP. Java, Python, Go, Scala, and Clojure. Heroku runs applications in virtual systems that can be customized based on the requirement of clients. The virtual computer systems of Heroku are known as dynos. These can be modified anytime based on the changing needs of users. Heroku users can add more resources through horizontal or vertical scaling.
Heroku charges customers monthly depending on the number of virtual computers they use. This PaaS platform and all applications built on it are all hosted on top of AWS. It makes development more convenient and easier for developers. Users can utilize the platform’s intuitive dashboard to easily perform actions based on requirements.

>>#### Why did we choose Heroku?
- Scalable – Heroku dyno containers are convenient as users can easily replicate them based on their resource requirements. Horizontal scaling is enabled by simply clicking a button and users can create as many instances of their application as required. 
- Simple – Heroku is preferred by users around the world for its simplicity, which makes it an easy-to-use platform. It offers a simple interface and easy one-click deployments. Releasing new software versions is also quite convenient using Heroku. 
- Secure – Heroku makes your applications secure at all times and reduces the need for repetitive security patching. It ensures complete security for your assets regardless of how complex your requirements are. 

## Hosted on Netlify

**Netifly** is a platform that offers cloud hosting and serverless backend services for static websites. Read more [here](https://www.netlify.com/)

>>#### Reasons for choosing Netlify
1. It is free  
It offers massive features on its free plan and as a matter of fact, almost all features are available on the free plan.
2. Easy to use  
The Netlify User Interface is perhaps one the of the easiest to understand and be able to find your way around without needing to Google a lot of “How to “ or spending time reading the docs. 
3. Deploy in seconds  
Deploying projects on Netlify are not just easy, but pretty fast too. You have the option to deploy from a Git repository or just by simply dragging your project folder and dropping it. Netlify takes care of everything else from there on. It identifies build commands (if any) and with just a click your project will be live in a few seconds
4. Continuous Deployment (CD)  
Anytime you deploy your project from a Git repo, Netlify automatically activates CD for you. With that, whenever you make a new commit and push to your repo, Netlify builds it for you and automatically updates your project to the most recent version. All this is achieved without having to create a configuration file and writing a long list of rules.
5. Branch Deploys  
You could easily choose any branch of your Git project and deploy just that branch. This comes in handy when testing new features that may or may not make it to the master branch or just a quick way to easily see how a PR would affect your site.
6. Free Private Repo Hosting  
If you have a private repo, you could easily still get it online and keep your codebase private without having to pay for anything. 
7. Deploy Previews  
Netlify gives you the ability to preview every deploy you make or want to make, This will allow you and your team to see what changes will look like in production, without having to deploy them in your existing site.
8. Asset Optimization  
Netlify gives you the ability to automatically optimize assets for your project. Available options like CSS and JS minification, image compression, and pretty URLs allow you to improve the performance of your sites with just a few clicks.
9. Free SSL  
Netlify adds security to your site with its Free SSL option with Let’s Encrypt. With one click install, HTTPS will instantly be available for your sites.
10. Rewrites and Redirects  
This gives you the ability to easily perform redirects and control certain actions on your website. 
11. Custom Subdomains  
By default, Netlify gives you a free custom subdomain whenever you create a new project (something like_mywebsite.netlify.com_), but they also give you the ability to use a custom domain name which you own and by simply updating your DNS records, your Netlify site will have it’s own domain.
12. Free DNS  
Netlify gives you the option of DNS Management absolutely free.

