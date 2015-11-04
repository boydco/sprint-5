# Review

Wireframe photos look good. Thanks!

Nice work on the testing. Looks like you got some good input. Beware what users tell you, however. Often they don't know what they want, but they want to be helpful so they guess. Or they think that they do know what they want, but when they get it they find out that no, not really. Literally millions of dollars have been wasted because user testers *thought* that they wanted something.

Better to provide different interfaces and then ask which they prefer. Or to watch them choose without being asked. The more you can observe the users in their natural, unbiased environment, the more likely you are to get good data.

The form looks good. The CSS is good, but you probably want to add some margin (or padding) at the bottom of the page so the submit button doesn't hug the bottom of the window. Whitespace is your friend! Lovely photo, by the way. The form looks great!

I didn't notice this when I decided to use the tutorial, but it's a good lesson to learn early: Tutorials are often wrong. When it comes to HTML, they are *almost always* wrong. It is really astonishing how few developers really understand HTML!

Rather than write this in every review, I'll just post a comment on Slack. Yay, Tuts. Sigh . . .

Your form is almost right. But you didn't validate the HTML (or probably you did, but then made changes and forgot to revalidate). Three errors that could easily have been avoided . . . Always validate as the *last* step before deployment or Murphy's law will get you every time.

The grids look fine. Do you feel comfortable with them now?

What happened to wrapping at 80 characters? Some of your lines are over 120. This:

```html
<input type="submit" id="button" value="Win a Free Trip to NYC" class="btn btn-large btn-success center-block">
```

Should be this:

```html
<input type="submit" id="button" value="Win a Free Trip to NYC"
  class="btn btn-large btn-success center-block">
```

I know it's a lot of material to cover in a week, but you will be under stress all the time as a pro. Now is the time to develop good habits. It is no harder to do it cleanly and elegantly than it is to do it otherwise.

Your comments on the accessibility of forms are good. I'm glad you thought it was succinct and worth bookmarking. WebAIM is an excellent resource.

Outstanding work on the usability. It's clear that you put effort into this. I think it will be well rewarded in your career. It may surprise you to discover how many developers aren't all that worried about usability (or accessibility, or, as I pointed out on Slack, standards compliance, semantics, separation of concerns . . . the list goes on and on). If you make the effort here, you will stand head and shoulders above most developers. That should help you to find better jobs, do more interesting work, get better pay, and advance more quickly. It's actually pretty generous of the average developer to make it so easy to stand out in this field. :-)


What happened to the screenshots?

