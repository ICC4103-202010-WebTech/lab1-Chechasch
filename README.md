3. The article are straightfoward, first we got the head and then, as we viewed last class, the body, thats literally the page, its the code that the server send to us when we click or send the instruction to it (MVC), it's organized, you can see they go from "the outside" to "the inside", first it designates the space that the table with the links will occupie, then it defines wheres the "head" of the table and it,s borders,color, etc. Then there's the space designed specialy for the links in the code this segment it's called "table", defining as well it's border, cellpadding, cellspacing and it's class, in this case it'a an "itemlist", then they define each one of the links, each one with a class and an id, after this is defined, it establishes it's number, where it's positioned, the title and it's specific reference, the source, the subtext wich in this specific case is under the class of "score" and "age", which has the option to hide with an hyperlink joined o it and the comments as well, and finally the spacer between the first and the second article and it goes on and on. The identation is straightfoward as well, the table and in the table heach article and in the aricle the subtext, etc.


4. First analysing the "hn.js" file, the first thing i notice is that there are only functions, so it leads me to think that's like a file that stores all the functions that the page can use. Although i can see the code i dont understand what each function does. Unlike "hn.js", "news.css" defines the "decoration" of the page, all the code in it defines the font the body will use, the td, its subtext, the title, comments, etc. Also the font size and color of the links (it makes a difference between the visited and the ones that are not different), beside this, it also defines the display of the different images of the page and the pixels which they will occupie. Basically the "news.css" worries about the aesthetics aspects of the page meanwhile the "hn.js" defines the diferent functions the page wil use depending on how the user interacts with it.


5. There are 6 different requests for the Hacker News main page.

          - news.ycombinator.com: GET
          - y18.gif: GET
          - s.gif: GET
          - hn.js?S5Ty60GFbTgUrObD86pQ: GET
          - grayarrow.gif: GET
          - favicon.ico: GET
          
 As we can see in the headers the server's name is "nginx". Looking at the different types of servers available, i belive it's a "web server", a web server serves static content to a Web browser by loading a file from a disk and serving it across the network to a user’s Web browser. This entire exchange is mediated by the browser and server talking to each other using HTTP. The other possiblitie could be a "Proxy Server" but the difference between these two, is that the proxy server looks to improve preformance and share connections, so it's not the main objective of "nginx" which is to upload the informtion to the browser.
