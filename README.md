Please Contribute
=================
Source Repository: https://github.com/omarduarte/juniors_should_know/

Any suggestions on the format and structure of this list are more than welcome. 
To contribute:
   1. Fork this repository
   2. Find awesome links, shorten them, and add to the list (101, advanced, etc...)
   3. Send me a pull request
   4. ...
   5. Profit!


NON-TECH
- Impostor Syndrome
  - Overcoming Impostor Syndrome http://bit.ly/1nPfFkA
  - 
- Knowing your tools
  - Advice: "Stop judging people for their choice of editor."
  - Touch Typing
    - TODO
  - Sublime Shortcuts
    - TODO
  - Mac Shortcuts
    - TODO
  - Chrome Shortcuts
    - TODO

The UNIX console
- Learn the used UNIX-based console commands.
  - TODO
- (Need help adding stuff here!)
  
HTML
  - Advice: "HTML is meaningful".
    - Lesson:
      - Use the appropiate tags for the following:
        - Headings
          - TODO
        - Articles
          - TODO
        - Lists
          - TODO
        - Navigation
          - TODO
        - Adresses
          - TODO
        - Times
          - TODO
    
  - Use \<dl\>
    - TODO
  - Forms
    - Placeholders
      - TODO
    - Select Multiple
      - TODO
    - Label for="id"
      - TODO
    - Optgroup
      - TODO
    - Mobile
      - Autocomplete=off
        - TODO
      - Autocapitalize=off
        - TODO
  - Advice: "Code Smells."
    - Lesson: "Clean up before deploying. Comments are for you, not for the end user."
CSS
  - Master the Box Model
    - TODO
  - Tricks that can save you a ton of time
    - Border-box for box sizing
      - TODO
    - Display: table-cell
      - TODO
    - @media selectors
      - TODO
    - Attribute selectors
     - input[type=radio]
       - TODO
     - div[data-foo~=value]
       - TODO
     - div[data-foo|=value]
       - TODO
     - a[href^=http]
       - TODO
     - a[href$=.zip]
       - TODO
  - Advice: "CSS animation is way better than Javascript animation"
    - Lesson: TODO
  - Learn one of the following:
    - SASS
      - TODO
    - LESS
      - TODO

FrontEnd
  - Advice: "Learn Javascript, CoffeeScript is not Javascript."
  - Advice: "You don't always need an app."
  - Advice: "Don't sacrifice UX over using a tool that makes your life easier."
    - Lesson: "Your Rich apps take long to load up, specially when the user is using a mobile device. If you don't need an app to show the content, don't use an app. If you do, then show a static page (mocking the app) while your app loads in the background."
  - Advice: "Handle the read case."
    - Lesson: "Nothing makes a user more angry than being unable to reach the information they need."
  - Indexability (SEO Basics)
    - URLs
      - TODO
    - Crawlers
      - TODO
    - Site maps
      - TODO
    - Insite Links
      - TODO

UX
  - Advice: "No one cares about carousels"
  - Advice: "Don't move the cheese".
    -Lesson: "Messing with elements while scrolling will confuse and distract your users. Stop moving stuff."
  - Advice: "Don't block the content with an email subscription call to action."
    - My Advice: "Use sparingly. Only use when you feel your users have consumed most of the content they would in that visit and are about to leave the site."

State
  - Advice: "Never break links."
    - Lesson: "If you changed the URL for a page, always re-direct the old URL to the new one."
    - URL Redirection
      - TODO
  - Advice: "Keep URLs Meaningful."
    - Lesson: "Use pushState to change URL in Rich web apps. Your users should be able to copy an URL from their browser and be able to share it with their friends."
      - pushState
          - TODO
  - Advice: "Avoid hashbangs!".
    - hashbang
        - TODO

Sessions
  - Cookies
      - TODO (What are cookies?)
      - Advice: "Cookies are not for storage. Your cookies shouldn't be larger than 4096 bytes."
      - Security
        - HttpOnly = true
        - Secure = true
        - TODO (Aditional cookies security).
  - LocalStorage
    - TODO (What is LocalStorage?)
    - Advice: "Use it."

Security
  - OWASP TOP 10
    - https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project
  - XSS
    - TODO
  - Cross Site Request Forgery
      - TODO
  - Input Validation Bugs
    - Advice: "Use Regex".
    - TODO
  - SQL Injections
    - TODO
    - Get all passwords
    - Drop Tables
  - Command Injection
    - Advice: "eval() is evil."
    - TODO
  - Direct Object Reference
    - TODO
  - Auth
    - Identification
      - TODO
    - Authentication
      - TODO
    - Authorization
      - Advice: "Don't do Authority via Identity" i.e. Everyone can edit cookies.
      - TODO
  - Salting and hashing passwords
    - Advice: "Use bcrypt."
    - TODO

Performance
  - Speed
    - Time taken to process 1 request
    - TODO
  - Efficiency
    - Resources used per request
    - Todo
  - Throughput
    - Total amount of requests processed per second.
    - Concurrent Requests / Process time of one request
    - Todo
  - Latency
    - Time that the user perceives to get a response.
    - Todo

Caching
  - Caching === storage for speed
  - Client caching
    - TODO
  - Edge Caching
    - CDNs
      - TODO
    - Multicast DNS
      - TODO
  - Asset Caching
    - Todo
  - Full Page Caching
    - TODO
  - Fragment Caching
    - TODO
  - Query Caching
    - TODO
  - Preprocessing
    - Todo
    
Debugging and Testing
  - Advice: "Don't be supersticious."
    - Lesson: TODO
  - Advice: "Be Explorative."
    - Lesson: "Use your language's Read Eval Print Loop (console) to test out everything you don't quite understand."
  - Error Messages
    - Advice: "'Oops!' is not an error message"
  - Source Maps
    - TODO

Coding Antipatterns
  - Globals
    - Advice: TODO
  - God Objects
    - Advice: TODO
  - Giant Function Signatures
    - Advice: TODO
  - Variable Names
    - Advice: "You're not charged by the character."
      - Lesson: "Most editors have autocomplete. A long explicit variable name is better than a short, confusing one."
  - Advice: "Stop Being clever."
    - Lesson: "You're coding for the next programmer that's going to read your code 2 years later when you're out in vacactions. Using obscure patterns and hard to read, yet clever, code requires a much higher investment of time to understand."
  - Advice: "Be Boring."
    - Lesson: "Use what works. Don't re-invent the wheel. Not everything is special."

Code Readability
  - Advice: "Pretend the person that's going to read your code 6 months from now has your address and a gun."
    - Lesson: "Before commiting, try to read your code from scratch and see if it's readable enough for the next person to understand. Change structure when necessary, try to eliminate confusion (or code line hopping) by being extra explicit. Your coding style shouldn't be unique and representative of yourself, but something understood and consumeable by everyone."

Time
  - Advice: "Use UTC"
    - TODO
  - Advice: "Use ISO 8601 as timestamps"
    - TODO
    
- Character Encoding
  - UTF-8
    - TODO
  - UTF-32
    - TODO
  - Internationalization
    - TODO

Chosing a DataBases
  - CAP Theorem
    - TODO
  - Other DB Characteristics
    - Indexability
      - TODO
    - Durability
      - TODO
    - Scalability
      - TODO
    - Speed vs throughput
      - TODO
  - Types
    - Memory
      - TODO
    - Memcache
      - TODO
    - Redis
      - TODO
    - MongoDB
      - Advice: "For prototypes only."
      - TODO
    - CouchDB
      - Advice: "Don't use CouchDB."
      - TODO
    - Level DB
      - TODO
    - MySQL
      - TODO
    - Postgres
      - TODO
    - Oracle
      - TODO
    - Cassandra
      - TODO
    - Riak
      - TODO
    - Neo4J
      - TODO
    - The File System as a DB
      - TODO
    - Hadoop
      - HDFS
        - TODO
      - HBase
        - TODO
    - S3
      - TODO
  - Replication
    - Advice: "Replication is not a substitute for Backups."
  - Race Conditions
    - TODO

Tips
  - Javascript
    - Advice: "Who cares is it tabs or spaces"
      - Fred Recommends: "Use spaces, tabs are shown as '\t' in outside of text editors and are a not a good indicator for indentation."
  - Git
    - Advice: "Know the ins and out of Git. Don't be afraid of rebasing"
    - Git Rebase
      - TODO
    - Git Merge Conflicts
      - TODO
  - Deployment
    - Automate Deployment
      - TODO
  - Architecture Patterns
    - MVC
      - TODO
    - MVP
      - TODO
    - SOA
      - TODO
    - Event-driven
      - TODO
    - P2P
      - TODO
