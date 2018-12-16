# Web Development Basics
Since finishing Dev Bootcamp and starting my first tech job at Optoro, several friends have asked me for tips on beginning their web development journey. Since I found myself giving the same advice repeatedly, I put together this readme to be a bit more [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) with my life.

Most of these resources were found at the code study group that I attend at my company, Optoro. Some came from Dev Bootcamp, where I spent a good chunk of time getting better at programming. There's a lot to explore out there, and I think this collection is good start.

If anything on this guide could be improved or should be changed, just make a pull request and/or email me at gabezurita@gmail.com. Here goes!

Prior to beginning, it’s important to be aware of resources to help get you unstuck or to learn more:

## Getting Unstuck
As you're progressing through these tutorials, you will at times find yourself unable to proceed without outside help. This is normal. 
* After being stuck for more than 10 minutes or three unsuccessful attempts, search Google for the specific error message or problem you’re attempting to solve. To do this effectively, here's a few [Google search tips](https://www.reddit.com/r/LifeProTips/comments/3yis0k/lpt_how_to_get_the_most_out_of_googlesearch/).
* [Stack Overflow](https://stackoverflow.com/) - for a more focused google search, input the error message you’re getting and limit the search to stackoverflow by including "site:stackoverflow.com" in your search string--see [this link](https://www.google.com/search?ei=PRJWW5DJOMjBjwTW2oqAAw&q=%22no+implicit+conversion+from+nil+to+integer%22+ruby+site%3Astackoverflow.com&oq=%22no+implicit+conversion+from+nil+to+integer%22+ruby+site%3Astackoverflow.com&gs_l=psy-ab.3...9291.9872..10082...0.0...106.465.4j1......0....1..gws-wiz.......0i71.EoxpbF8ncwE) for an example. If there are no posts around your error message, feel free to create a new post asking for help. [Here's some guidelines on how ask for help on Stack Overflow](https://stackoverflow.com/help/how-to-ask).    
* Typing code to learn syntax is an important aspect of learning to program. Do not copy/paste solutions you find on the internet, be sure to type them out.
* Really try to understand why the found solution works and do not move on until you do. **If you can’t understand the problem and/or its solution, get ahold of a friend who might!**

## General Tips
* Get connected to other people who are attempting to learn. There's lots of online and in-person communities, e.g. [DCTech Slack](http://www.dctechslack.com/) and [DC Code Newbie Meetup](https://www.meetup.com/CodeNewbie-DC/).
* Don’t be afraid to reference (or even simply explore) the [documentation](http://devdocs.io/ruby~2.4/) of the language you’re studying.
* [Time Management - Pomodoro Timer](https://cirillocompany.de/pages/pomodoro-technique) - Generally speaking, it’s easy to get distracted or to spend one’s time inefficiently -- using the Pomodoro Technique will help you get more done. Here’s a useful [Pomodoro Cheatsheet](http://i.imgur.com/zB4YdEi.png)
* Podcasts are a great way to get introduced to various tech topics. [Codenewbie](https://www.codenewbie.org/podcast) is a excellent for new developers.
* Get a text editor to edit code – [Atom](https://atom.io/) is a good one, but there's many alternatives out there.

## Web Development Concepts and Languages
Here’s some resources to explore, and languages to learn (from top to bottom):

### Web Basics
Let's learn about the infrastructure web apps run on
   * Watch: The Internet -- <a href="https://www.youtube.com/watch?v=AEaKrq3SpW8" target="_blank">How does it work?</a>
   * Read: Web concepts -- <a href="http://skillcrush.com/2012/08/19/the-internet-vs-the-web/" target="_blank">Internet vs. Web</a>, <a href="http://skillcrush.com/2012/10/01/web-browsers/" target="_blank">Web Browser</a>, <a href="http://skillcrush.com/2012/07/03/web-server-2/" target="_blank">Web Server</a>
   * Read: <a href="http://skillcrush.com/2013/03/28/websites-vs-web-applications/" target="_blank">Web site vs Web App</a>
   * Read: Domain concepts -- <a href="http://coding.smashingmagazine.com/2011/05/25/introduction-to-dns-explaining-the-dreaded-dns-delay/" target="_blank">DNS intro</a>, <a href="http://skillcrush.com/2012/04/24/dns/" target="_blank">DNS in-depth</a>, <a href="http://skillcrush.com/2012/07/03/ip-address-2/" target="_blank">IP Address</a>
   * Read: <a href="http://skillcrush.com/2012/04/02/html/" target="_blank">What's HTML?</a>

As an alternative course to any of the below: Udemy has excellent content, though their courses tend to be expensive. Be sure to look for sales there, you can regularly get $200 courses for only $10 (yes, 95% off!). I repeat, do not pay full price, as [Udemy regularly has sales](https://www.reddit.com/r/learnprogramming/comments/6rc5tf/how_often_do_udemy_courses_go_on_sale/) (like a mattress store).

### [HTML](http://devdocs.io/html/) & [CSS](http://devdocs.io/css/)
HTML (Hypertext Markup Language) and CSS (Cascading Style Sheets) are two of the core technologies of the web. HTML provides the structure of the page, CSS the (visual and aural) layout, for a variety of devices. Check [World Wide Web Consortium (W3C)](https://www.w3.org/standards/webdesign/htmlcss) for more info.
    * [Codeacademy](https://www.codecademy.com/learn/web) ←great and free, but there’s excellent paid options: [code school, or treehouse](https://www.reddit.com/r/learnprogramming/comments/1dvhrt/codecademy_vs_code_school_vs_treehouse/)
    * [Flexboxfroggy](http://flexboxfroggy.com/) and/or [CSS Garden](http://cssgridgarden.com/) + [CSS Grid Tutorial](https://mozilladevelopers.github.io/playground/)
    * Now make make a website on your computer through this [Codeacademy tutorial](https://www.codecademy.com/articles/local-web-page)!

### [JavaScript | ECMAScript](http://devdocs.io/javascript/)
The programming language the web (currently) runs on. Here's [some good reasons to learn it](http://www.bestprogramminglanguagefor.me/why-learn-javascript).
* [Codeacademy](https://www.codecademy.com/learn/javascript) - Free course and a good enough intro
* [Javascript30](https://javascript30.com/) - 30 days of free, JS code challenges by [Wes Bos](https://twitter.com/wesbos)
* [ES6.io](https://es6.io/) - Excellent, paid, JavaScript course (also by the above author)  
* [Eloquent in Javascript](http://eloquentjavascript.net/) - Great JS book, though a perhaps too detailed for an intro

### [Ruby](http://devdocs.io/ruby/)
A beginner friendly programming language for the back-end. Feel free to go work on these things at a programming meetup such as [this one](https://www.meetup.com/dcruby/)!
* [Codeacademy](https://www.codecademy.com/learn/learn-rails) (it’s good to know [how to read Ruby error messages](https://learn.co/lessons/ruby-lecture-reading-error-messages) for this)
* [A good article giving you a general outlook on Ruby](https://hackhands.com/beginners-guide-ruby/)
* [Ruby Essential Training](https://www.lynda.com/Ruby-tutorials/essential-training/47905-2.html?srchtrk=index:1%0Alinktypeid:2%0Aq:ruby%0Apage:1%0As:relevance%0Asa:true%0Aproducttypeid:2)
* [Good book on Ruby](http://poignant.guide/)
* Learn a little more about Ruby through [Ruby Koans](http://rubykoans.com/) -- or feel free to come back to this later
* [Exercism -- more difficult exercises](http://exercism.io/languages/ruby/about) -- feel free to skip for now and come back to it later

### [SQL](https://www.reddit.com/r/explainlikeimfive/comments/1jid0b/eli5_what_is_a_database_and_what_is_sql_language/)
It's important to learn to work with data (the backbone of the tech world)
* [Codeacademy](https://www.codecademy.com/learn/learn-sql) and/or [this well made SQL tutorial](http://sqlzoo.net/wiki/SELECT_basics).
* If you'd like to go more in depth, there's some free, [self-paced Stanford SQL classes](https://lagunita.stanford.edu/courses/DB/SQL/SelfPaced/about) you can explore.

### [Git](https://guides.github.com/introduction/git-handbook/)
Managaging changes in app development
* [Tutorial](https://learngitbranching.js.org/)—some useful resources on [the site](http://try.github.io/).
* [Thoughtbot video on how git is used in some tech companies](https://thoughtbot.com/upcase/videos/git-workflow)

### [Ruby on Rails](http://devdocs.io/rails/)
Let's start making web apps!
* [Codeacademy](https://www.codecademy.com/learn/learn-rails)
* Buy a Used or Refurbished [Macbook](https://www.amazon.com/Apple-MacBook-15-4-Inch-Laptop-Yosemite/dp/B00PZLRWVE/ref=pd_sbs_147_4?_encoding=UTF8&pd_rd_i=B00PZLRWVE&pd_rd_r=4S2TWVDYFN5F2HC06GTY&pd_rd_w=yYbjY&pd_rd_wg=cWZlC&psc=1&refRID=4S2TWVDYFN5F2HC06GTY) and [set up your dev environment](https://github.com/codehbs/computer-setup/blob/master/mac-instructions.md)
* Get more Rails practice through [Rails for Zombies](http://railsforzombies.org/)
* [Build a ruby on rails web app!](https://emkaydeum.wordpress.com/2016/04/28/tutorial-build-a-rails-app-using-the-nasa-astronomy-photo-of-the-day-api/) -- the best way to learn is by making something!

___

## Additional Resources
* This [reddit post](https://amp.reddit.com/r/learnprogramming/comments/43dvma/best_online_courses_you_took/) has some great Computer Science courses
* [edEx course](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11)
* [Online Community Resource (such as /r/learnprogramming)](https://www.reddit.com/r/learnprogramming/wiki/index)
* [Progressive Web Apps](https://developers.google.com/web/ilt/pwa/)
* Programming Puzzles: [The Human Resource Machine](https://tomorrowcorporation.com/humanresourcemachine) and [Bandit](http://overthewire.org/wargames/bandit/)
* Programming Katas: [Code Wars](http://www.codewars.com/)
* [Linux](https://bash.cyberciti.biz/guide/Main_Page)
* Learning a javascript framework such as [Angular](https://thinkster.io/a-better-way-to-learn-angularjs) and then building a rails app with it is a good exercise. Once you've gotten past that, you can then [build a rails app with an Angular frontend](https://thinkster.io/tutorials/angular-rails).

## Next Steps
* Volunteer in a programming project through the [Code for America Brigade](http://brigade.codeforamerica.org/brigade/)
* Contribute to an [open source project](https://github.com/MunGell/awesome-for-beginners)
