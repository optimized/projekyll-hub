Project Hub
===========

A Jekyll powered of [Super Friendly / Dan Mall's Project Hub](https://github.com/SuperFriendly/project-hub/)

All "projects" come from the `_posts` directory. Edit the "[frontmatter](http://jekyll.tips/jekyll-casts/front-matter/)" for each post and place content in HTML or Markdown below.

For local development, run `bundle exec jekyll serve`. To serve to clients, commit to the gh-pages branch.

### Original Notes

Original notes from SuperFriendly:

[Brad Frost](http://bradfrostweb.com/)—who I guess was [inspired by me](http://24ways.org/2013/project-hubs/)?—I&rsquo;ve taken a pass at a new Project Hub.

Here are a few details on what I thought needed improvement:

- **Seeing the future.** Good Project Hubs document the past in a way that makes it easy for a client—or you—to keep track of the process. However, I&rsquo;ve started to pre-populate the entire process for my clients so that they know not only what&rsquo;s happened but also what&rsquo;s coming up.
- **Focusing on a moment in time.** Though this Project Hub lets you see an  entire project timeline, it&rsquo;s still really valuable to know where you currently are in the process. By default, each milestone is labeled with a class name of `entry-future`, which keeps the upcoming milestone grayed out. Once you&rsquo;ve completed a milestone, remove this class name; that will darken the text and place a checkmark next to it. Lastly, add a class of `entry-latest` to the latest milestone to auto-scroll the page. (You can also change this class name on line 18 of the JavaScript file.)

You can see the finished result here: [project-hub.superfriend.ly](http://project-hub.superfriend.ly/)

Pull request or fork at your leisure. Happy Project Hubbing!
