The UNIX console
- Learn most commonly used UNIX-based console commands.

  Advice: Understanding Unix/Linux is key to become a better developer.
          Many things which might require complex programs can be done easily
          by pipelining basic Unix commands.

  - The Basics.
    - Basic commands everyone should be comfortable with.
    (http://bit.ly/1nVrUGa)

    - Basics about Unix in general, I/O redirection and pipelines
    (http://bit.ly/14wPCpj)

  - AWK tutorial. AWK is a real handy command all developers should know.
    (http://bit.ly/1DVsZYw)

  - SED tutorial. Another powerful and handy command.
    (http://bit.ly/1y8N7HV)

  - Advanced but incredibly handy.
    - AWK cheat sheet
      (http://bit.ly/1KGSBgp)

    - SED cheat sheet
      (http://bit.ly/1xXJkuT)

  - Beyond just the basics
    - UNIX : The ultimate guide covers nearly all aspects of Unix/Linux
     (http://amzn.to/1FRUzKY)

HTML
  - Advice: "HTML is meaningful".
    - Lesson:
      - Use the appropiate tags for the following:
        - Headings
          - Heading Structure http://bit.ly/1AgtQmB
        - Articles
          - The article element http://bit.ly/13QWuxK
        - Lists
          - HTML Lists http://bit.ly/1zOisPL
        - Navigation
          - Semantic Navigation with the nav element http://bit.ly/1xeALLQ
        - Adresses
          - The Adress element http://bit.ly/1B2nkQD
        - Times
          - Best of Time http://bit.ly/1wyUFwd
  - Use \<dl\>
    - The dl Element http://bit.ly/13QXqSS
  - Forms
    - Placeholders
      - HTML5 Placeholders http://bit.ly/1CRWBIH
    - Select Multiple
      - HTML Multiple http://bit.ly/1rNklte
    - label for={{ id-of-control-element }}
      - W3 Standard Definition http://bit.ly/1wMQq0a
    - Optgroup
      - MDN Reference for optgroup http://mzl.la/1xCNDgR
    - Mobile
      - Autocomplete=off
        - MDN Web Security Blog Post http://mzl.la/1Br6ARk
      - Autocapitalize=off
        - Disabling Auto-Correct And Auto-Capitalize Features On iPhone Inputs http://bit.ly/1tHUpRi
  - Advice: "Code Smells."
    - Lesson: "Clean up before deploying. Comments are for you, not for the end user."

CSS
  - Master the Box Model
    - The Box Model for Beginners http://bit.ly/1ljbFYS
    - W3 Box Model Specifications http://bit.ly/13TljZD
  - Tricks that can save you a ton of time
    - border-box for box sizing
      - http://bit.ly/1Fnj3p2
    - display: table-cell
      - http://mzl.la/1FqkDrr (all display properties)
    - @media selectors
      - http://bit.ly/1EQxYHP
    - Attribute selectors 
     - Explained: http://bit.ly/1FZvFro
     - input[type=radio]
     - div[data-foo~=value]
     - div[data-foo|=value]
     - a[href^=http]
     - a[href$=.zip]
  - Advice: "CSS animation is way better than Javascript animation"
    - Lesson: Take with a grain of salt (http://bit.ly/1AGVrAq)
  - Learn one of the following:
    - SASS
      - http://bit.ly/OqI5Rm
    - LESS
      - http://bit.ly/QfzOjE

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
    - http://www.nngroup.com/articles/designing-effective-carousels/
  - Advice: "Don't move the cheese".
    -Lesson: "Messing with elements while scrolling will confuse and distract your users. Stop moving stuff."
  - Advice: "Don't block the content with an email subscription call to action."
    - My Advice: "Use sparingly. Only use when you feel your users have consumed most of the content they would in that visit and are about to leave the site."

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
      - SQL is actually great
      - http://seldo.com/weblog/2010/07/12/in_defence_of_sql
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
  - ORM is an antipattern
    - http://seldo.com/weblog/2011/08/11/orm_is_an_antipattern

