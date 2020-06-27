---
title: How I revamped the design of W261
date: 2019-09-01
tags: ['post', 'article', 'design', 'blog']
---

In this article, I will share with you the steps I went through to revamp the design of this website you are on right now (W261).
 
I thought it would be a simple and straightforward exercise to do web design, but realized, along the way, its complexity and the importance of decision-making in this craft.

This was my first complete design experience (from design to development).

It was fun. 🎎

_W261 is a platform where people commit to sharing knowledge related to tech, career, skills, business, and other areas of expertise._

# **(I) Analysis**

First of all, I analyzed the original layout and sought feedback from designers:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/bgp907aakwde35x9objv.jpg"
    alt="Original design layout of W261."
  />
<figcaption>Original layout.</figcaption>
</figure>

They identified several issues related to margins, spacing, font size, color contrast, line height, alignment, and even questioned me on the value of some items in there, such as the author name, date, and others I created as I was modifying the design. 

Here are 3 examples of problems the original layout had:

## **(1) Spacing distribution**

Clearly, there is a spacing issue. The titles were too far from their respective article preview, and it caused confusion.

I had to re-structure in a way to keep the title, author, date and first sentences of the article together.

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/2zwmtyqqsvie0ooxc7j2.png"
alt="Spacing issue with W261 original design layout."
  />
<figcaption>Elements are detached from each other.</figcaption>
</figure>

## **(2) Title colors**

The first version of W261 was created by Seif (web developer), using a [template](https://www.npmjs.com/package/gatsby-theme-blog).
 
Not so glad about the color scheme, he asked me to work on a fresh palette for the new version.

The color of the titles was purple and it seemed like it was clicked on already. Why? Because this is how browsers style anchors (links) that have been clicked on previously. 

For example, in the image below, I clicked on "My Favorite Things", hence its purple color:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/de2ewptpryhg5nwp25r8.png"
alt="When you click on a link the color changes to purple."
  />
<figcaption>Golden track. 🎷</figcaption>
</figure>

I had to find a color that would encourage readers to click on the title, and not be misled by its color.

## **(3) Small-sized logo**

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/jjc44tqyszrhemcup5hc.png"
alt="W261 logo on hover."
  />
<figcaption>The "W" looks like Wutang's W, somehow.</figcaption>
</figure>

However, the number "6" did not look good as it seemed hollow:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/xuttpppzhtqs50lxk1mv.png"
alt="W261 logo did not look good before."
  />
<figcaption>The hole in the 6 puts me off.</figcaption>
</figure>

# **(II) Transfer**

I did not have the original layout on any design tool, so I had to create it from scratch, and iterate based on it. 

This is how I did it:

## **WhatFont Chrome extension**

I used this [Chrome extension](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en) to get the color, font, font size, and line-height of the elements on the page:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/vbdrsksl861qdf1s8qb2.jpg"
alt="WhatFont extension is useful to design from scratch."
  />
<figcaption>Just hover on text to make the tooltip appear.</figcaption>
</figure>

## **PageRuler Chrome extension**

This [extension](https://chrome.google.com/webstore/detail/page-ruler/emliamioobfffbgcfdchabfibonehkme?hl=en) has a very handy feature. It allows you to see the spacing and positioning of elements.

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/ca3wl7ffrtjgmucp1edr.jpg"
alt="PageRuler Chrome extension to do a design from scratch."
  />
<figcaption>You can see the spacing of each element on the page.</figcaption>
</figure>

## **Figma**

With the information you collect using the two extensions above, you can easily re-create the design of a web page. Here is the result using [Figma](https://www.figma.com/downloads/):

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/zmi90jszayu14oiogmye.jpg"
    alt="Using Figma to create the design layout of an existing page."
  />
<figcaption>It looked like I designed the original layout.</figcaption>
</figure>

That's it. It was surprisingly simple.

# **Execution**

## **Grids**

Shortly after creating the original layout on Figma, a designer told me about [responsive grids](https://uxdesign.cc/responsive-grids-and-how-to-actually-use-them-970de4c16e01), and I started using a grid to properly place elements. You can see below that it was "off" the grid:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/zsrjkpf8dnzejrqz9y9h.png"
    alt="12 column grids on Figma."
  />
<figcaption>It made my life easier.</figcaption>
</figure>

This is how it looked like after using the 12-columns grid:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/tc988qzsbqd7jpu7uqox.PNG"
    alt="Using 12-column grids in Figma."
  />
<figcaption>Centered.💢</figcaption>
</figure>

## **Logo reparation**

First of all, I opened the logo again on Inkscape and fixed the number 6 by filling the inner side:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/pulks7bw37o6kkug77fq.png"
    alt="Repairing the W261 logo."
  />
<figcaption>I was so happy when I fixed it.</figcaption>
</figure>

I then removed the pink sparkles and kept the logo free of distractions:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/dnx0npa2zxf8z6ynwl9z.JPG"
    alt="Removing the pink sparkles from the W261 logo."
  />
<figcaption>Who sees Wu-Tang's logo?</figcaption>
</figure>

## **Logo on hover**

The pink sparkles still looked good, so they are kept only when the reader hovers on the logo.

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/fnfgja9aqeflbxoiuaga.gif"
    alt="Hovering on the W261 logo."
  />
<figcaption>HOVOOOOOOR 🧙‍♂️.</figcaption>
</figure>

## **Avatar creation**

The original version of W261 did not have avatars. To give a more human aspect to the platform, and enable the community to recognize members, I added faces.

To create consistency across avatars, in comparison with other blogs, I created a specific style. Faces would appear on top of a yellow background surrounded by a circle (blue in light mode, pink in dark mode):

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/vr5swkyctimvhwiy9ic7.png"
    alt="Creating avatar style guidelines."
  />
<figcaption>There is some yellow in my eye. At first, it frustrated me, but I could live with it.</figcaption>
</figure>

Why yellow, blue and pink? I don't know, it just looks good. 😘

## **Spacing solution**

To avoid the confusion created by the incorrect spacing, I kept all the elements (titles, avatar and details, article preview) of one single article close to each other, and separate from the following article's group of elements. In this case, we clearly separate an article from another:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/3qzp82hstbv5k3gkhiaq.png"
    alt="Separating elements on W261 for the new design."
  />
<figcaption>No doubt about which title the article preview refers to..</figcaption>
</figure>

## **Placement of avatars**

Now that I got a clearer idea of what elements I would use, I started to experiment with different versions.

### **Version 1**

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/h7062pgaa13ukh1x36s0.JPG"
    alt="Version 1 of avatar use."
  />
<figcaption></figcaption>
</figure>

I liked this version but came to realize that separating the title from the article preview is confusing. Also, the alignment looked "off", given how the title and article preview are aligned, but separated by a circle in the middle.

### **Version 2**

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/0q47rwiy4wwapepnyuus.JPG"
    alt="Version 2 of avatar use."
  />
<figcaption></figcaption>
</figure>

The avatar is linked to the title, while it should be linked to the author's name.

### **Version 3**

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/5y1eahys4n5ejk3ky0k8.JPG"
    alt="Version 3 of avatar use."
  />
<figcaption></figcaption>
</figure>

The avatar is bigger, off the grid, and it would be complicated to design this for mobile.

### **Version 4**

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/djinf59bnbq94qc3caqg.JPG"
    alt="Version 4 of avatar use."
  />
<figcaption></figcaption>
</figure>

I liked this version, but visually the topics' alignment on the right is confusing.

I sought feedback and kept iterating for days. You already know what the final version looks like since you are reading from the website (spoiled #sorrynotsorry).

## **Longer titles**

Not all titles are one sentence only, so I created a longer title and realized it would not break anything:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/915smy4yjfedqy9ku8p2.JPG"
    alt="Edge case with longer title on W261."
  />
<figcaption>Create the longest title you want.</figcaption>
</figure>

## **Two authors**

W261 is a community platform where some authors cooperate to write joint content pieces, so I created a layout to adapt for two authors:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/gcsl6d7xl6r5bdbdcvx7.JPG"
    alt="Experimenting with double authoring and avatars on W261."
  />
<figcaption>When siblings write.</figcaption>
</figure>

## **Color**

To avoid the purple I mentioned above, and keep color consistent for both dark and light mode, I went for this bright blue:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/9yebpfng3zipnevvhgnx.JPG"
    alt="Title colors on W261."
  />
<figcaption>This color entices you to click on it. 👅</figcaption>
</figure>

## **Title and article preview**

To keep the connection between title and article preview, I pushed the avatar, author name, and date, beneath the article preview. It looked better, but the minutes to read and topics were still not well positioned:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/r7opt6qes3xznxnbferz.JPG"
    alt="Sticking title and article preview in W261"
  />
<figcaption></figcaption>
</figure>

## **Alignment**

Super, I managed to keep the author name, date, minutes to read and topics together, but could not figure out which alignment to use (left or right):

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/cq2hah60918v68m5ncik.jpg"
    alt="Left alignment of avatar on W261 design."
  />
<figcaption>Left version.</figcaption>
</figure>

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/viwfzrlishp0ucswsy3p.JPG"
    alt="Right alignment of avatar on W261 design."
  />
<figcaption>Right version.</figcaption>
</figure>

## **Margins**

The original version was too centered and "squeezed":

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/38digzblzr3ent8h0b07.JPG"
    alt="Original W261 design layout had big margins."
  />
<figcaption>Looks like you read a manuscript.</figcaption>
</figure>

To create more space, and eventually add more elements to the title, I shortened the margins:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/b012rs8p0c17cym3pyhn.png"
    alt="New W261 design layout with smaller margins."
  />
<figcaption>Pushing to the left.</figcaption>
</figure>

## **Number of items**

As I was experimenting, I ended up with layouts with 4 items: (1) title, (2) minutes to read and hashtags, (3) article preview, and (4) avatar, author name, and date:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/a4twx8yfhu9j7que3w49.JPG"
    alt="4 different items in the original layout of W261 on homepage."
  />
<figcaption>1, 2, 3, and 4!</figcaption>
</figure>

Following the almighty advice "the less the better", I ended up with 3 items instead of 4 and managed to combine (2) minutes to read and hashtags with (4) avatar, author name, and date:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/4klo87lwzy97z4weofdr.png"
    alt="3 different items in the original layout of W261 on homepage."
  />
<figcaption>1, 2, I mean … you know how to count.</figcaption>
</figure>

## **Fixing the "dot"**

Invisible to my eye, I did not notice that the dot I used "." was not serving the purpose I wanted:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/5i8b7gz5zuzv50pshzay.png"
    alt="Difference between full stop and the middle dot."
  />
<figcaption>Omar Benseddik. FULL STOP. Date.</figcaption>
</figure>

A colleague designer pointed me in the right direction, and showed me the difference between the "middle dot" and the "full stop":

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/ussa60cd3bhg9hg4lag5.png"
    alt="Difference between middle dot and the full stop."
  />
<figcaption>Can you see the difference?</figcaption>
</figure>

## **Mobile version**

I should have started with mobile design, instead of desktop design. Why? Shifting from desktop to mobile turned out to be complicated, as I dealt with new spacing, positioning, and layout problems I did not think of. Here are some layout versions:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/cooyj9loswae29py63js.JPG"
    alt="Different mobiles versions of W261 during the 1st design phase."
  />
<figcaption></figcaption>
</figure>

## **Two authors on mobile**

The desktop versions clearly did not fit, as it pushed the text one line below:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/rl0mfiigdm3n0e27uc3l.png"
    alt="Double authoring is hard to position on mobile."
  />
<figcaption>I don't like this. Neither do you.</figcaption>
</figure>

The solution was to overlap the avatars and cut the "last names" (sorry to the proud parents)💇:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/m37hkp8qxvce925f7rb2.png"
    alt="Finding a solution for double authoring in a blog."
  />
<figcaption>Spot the typo.</figcaption>
</figure>

## **Alignment on mobile**

Shortly after sticking title with article preview, I either aligned the avatar:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/kcf5s86yf9cyxavtb8m5.png"
    alt="Double authoring issues on mobile for W261."
  />
<figcaption>Avatars are aligned.</figcaption>
</figure>

Or I aligned the text, creating a white space if there was a single author (the most common scenario):

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/nnbljkoy2imqvi4qe5eu.png"
    alt="Alignment of text instead of avatars."
  />
<figcaption></figcaption>
</figure>

After much reflection, I decided for the first option and accepted to have the text misaligned in case of double authoring (sniff). 🥶

## **Line-height on mobile**

The line-height in the original version was too large:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/oqvxjhv0bh5k7b2gdals.png"
    alt="Line-height on mobile."
  />
<figcaption></figcaption>
</figure>

Following a tip from the designers that helped me, I multiplied the font size times 1.333 (or 1.5) and rounded either up or down, and eventually came up with the line-height. It looks more compact, and cleaner:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/ennipx3wbdzglimosbn4.png"
    alt="Line-height on mobile is now fixed."
  />
<figcaption></figcaption>
</figure>

## **Dark mode background**

In the original version (inspired by Sarah Drasner's [code editor tool](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl) "Night Owl"), the background in the dark mode was purple:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/hvqy3ll9wd470tr69cz9.png"
    alt="Purple dark mode of W261."
  />
<figcaption></figcaption>
</figure>

It did not look that aesthetic, so the developer and I experimented with different colors and came up with this dark blue:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/q43in4jd3ht5sewf6rcq.JPG"
    alt="Dark blue dark mode of W261."
  />
<figcaption>Love this dark blue. 💙</figcaption>
</figure>

## **Custom dark/light mode icons**

To differentiate W261 from other platforms who have a dark/light mode, and to be in line with the brand style, Seif suggested I create icons to replace the existing "Moon" and "Sun". This is what the original ones looked like:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/r2enx2djwvw98crqee25.png"
    alt="Basic version of a dark and light mode toggle button."
  />
<figcaption>Basic.</figcaption>
</figure>

"Give me 8 minutes, and I'll come up with something dope" - that's what I told Seif, and in fact, I managed to create the new icons in such a short amount of time. 

However, they were absolutely not in line with the brand style, so it did not serve the purpose:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/gwpqb1awqh8puabju2lg.png"
    alt="Dark and light icons for the Benseddik website."
  />
<figcaption>I ended up using these for my portfolio.</figcaption>
</figure>

I worked on different icons, and ended up with this outcome:

<figure>
  <img
    src="https://thepracticaldev.s3.amazonaws.com/i/ht6glh21mgcoopubhqae.png"
    alt="New dark and light mode icons for W261."
  />
<figcaption>Blame my crap Paint skills to do this screenshot :/</figcaption>
</figure>

# **(IV) Result**

The website you're reading this from right now. 👽

# **(V) Future**

Cleary, in a single month I could not cover all the aspects. These are the following topics to tackle:

* Responsive typography.
* Design system for W261.
* Profile page.
* New features roadmap.
* Accessibility.
* Newsletter button.
* Design handoff.

If you want to learn a new topic or get in-depth in a current one, ask me about our Manifesto page and start writing to share your knowledge.

W261 will keep growing. 👹


---

Thank you to Christophe, Niels, Tim, John, and Perry, for the support and guidance. 👏

I will annoy you even more in the months to come. 👀