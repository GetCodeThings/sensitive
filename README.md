# sensitive
A native version of the kibana sense plugin for elasticsearch



### A little bit of history  
A long time ago, [elastic.co](http://elastic.co) released a chrome extension called Sense that made it really easy to communicate with your elasticsearch server. It had a simple and comfortable UI, but more importantly it offered auto-complete (a.k.a. intellisense) when building elasticsearch queries.  
This was an amazing tool, and I used it a lot.  

Then, (for some unknown reason) they decided to remove it from the Google extensions library, and it was only offered to customers who bought a license for marvel (the elasticsearch monitoring app).  

Recently elastic released the sense code as a plugin for kibana.  
This is great news! ...but what if I'm not using kibana ? I'm using elasticsearch and want to use sense, but I don't want to install kibana for that!  

### Sensitive to the rescue!  
Sensitive is the sense plugin wrapped as a native desktop application, using [electron](http://electron.atom.io/).  
It basically has all the kibana code in it, which will be cleaned out hopefully, along with the sense plugin code, but it doesn't run as a server, and doesn't use any ports on your computer.  


### Running from the source code  
* Install [nodejs](https://nodejs.org/en/)
* Download the 'Sensitive' source code
* Open your terminal (or cmd) and open the directory where you put the source code
* run `npm install` (this might take a while)
* run `npm start` to run the application
  
### Executable  
If you just want a running executable of this, then click on the appropriate link :
* [MacOS](https://github.com/gillyb/sensitive/releases/tag/Mac_0.1)  
*I will create executables for other platforms soon*  

### Helping out  
If you want to help out improving this, then feel free to open issues, send pull requests or email with me suggestions.  
Thanks :)
