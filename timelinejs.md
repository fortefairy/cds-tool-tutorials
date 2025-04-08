# TimelineJS

This tutorial was adapted from a previous tutorial created by Elana Altman at the Barnard College Digital Humanities Center

*adapted by Taylor Faires*

<img align="left" width="75" src="/images/scalar/cc.png" alt="Creative Commons license">

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

Introduction to the tool:
-------------------------

TimelineJS is a free, open-source tool that allows you to make media-rich, chronological timelines. It can be helpful for illuminating cause and effect, putting stories into historical context, highlighting changes over a period of time and understanding the impact of time on narratives.

### The tool is great for:

-   Illuminating the chronological order of events to tell a clear story
-   Visualizing how something changes over a period of time
-   Smaller digital projects that stand on their own, or that can be included as part of a larger project

### The tool is not great for:

-   Telling stories that don't move in a linear, chronological fashion 
-   Making extremely customized visuals
-   Showing how quantitative data changes over time - data visualization is a better tool for that

Materials:
----------

-   [https://timeline.knightlab.com/](https://timeline.knightlab.com/)
-   [Spreadsheet Template](https://docs.google.com/spreadsheets/u/1/d/1pHBvXN7nmGkiG8uQSUB82eNlnL8xHu6kydzH_-eguHQ/copy)
-   A personal Google account


# Tutorial

## Step 1: Getting Started

### Familiarizing Yourself with the Format

To understand the types of projects that work well for this tool, it is helpful to look at some examples. As you take a look at the examples below, keep in mind that visualizing information always involves privelaging specific narratives. How do these timelines shape your view of cause and effect? Do they leave anything out? Are there assumptions that underly these stories? It's always helpful to reflect on how visualizing information affects understanding before starting your own project.

-   [The History of Wine](https://vinepair.com/wine-colonized-world-wine-history/)
-   [African American and Civil Rights History in Charlotte, 1940-1983](https://specialcollections.charlotte.edu/exhibits/cr/)
-   [Revolutionary User Interfaces](https://timeline.knightlab.com/examples/user-interface/index.html)

### The TimelineJS Spreadsheet

TimelineJS uses a formatted Google spreadsheet as a back-end. In order to create your own timeline, you need to make a copy of this spreadsheet. To make a copy of the spreadsheet:

1. Go to the [TimelineJS](https://timeline.knightlab.com/) website.
2. Click the green "Make a Timeline" button.
3. Click "get the spreadsheet template.
4. You may be directed to log-in with your Google account, once you do, you will be asked if you want to make a copy of the Official TimelineJS3 Template, click "make a copy"
5. You now have the TimelineJS template. You can rename it to whatever you want, but don't change any of the column headers

Once you have the spreadsheet copied, you'll notice that there are a number of columns. These are all associated with components of your timeline. Below is a description of the different sections of the spreadsheet:

**TimelineJS Spreadsheet**

-   **Date (Year, Month, Day, and Time):** These four columns are associated with the start date of your timeline slide. All slides in your timeline need at least a year in order to work properly except for the title slide (more on this in the next section).
-   **End Date (Year, Month, Day, and Time):** There are four optional columns that are associated with the end date of your slide if there is one.
-   **Display Date:** If you want your display date to be different from your listed start and end dates, you can type it in here.
-   **Slide Information (Headline and Text):** This is where you'll put the title of your slide and additiona information.
-   **Media (Media, Media Caption, Media Credit, and Media Thumbnail):** This is where you will embed media, give proper attribution, and describe your media.
-   **Additional Information (Type, Group, and Bacground):** This is where you can designate which slide is your title slide (there can only be one), if your slide belongs to a group, and the background color or image of a slide. 

Now, this may be hard to follow without looking at how this appears in the final product. A TimelineJS is a lot like a slideshow: Each TimelineJS includes a title slide and  several event slides, with a dated  timeline running along the bottom of the slides.  The slides themselves are fairly structured, so it's useful to understand the components before building your timeline. To understand the components, we'll take a look at a sample timeline [about the history of fandom.](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1VPzv3vH-_xlp-DzCLjNCHDA7KljrtOTmBhFmeas4fn8&font=Default&lang=en&initial_zoom=2&height=650)

#### *For Event Slides:*

![Slide showing placement of components: media, display date, headline, text, credit, caption, date, and group](/images/timelinejs/event-slide.png)

**Story-Portion of Slide (Top)**

-   **Media:** Image, video, audio, Tweet, webpage, or other type of media that helps tell your story.
-   **Display Date:** The date listed along with the story portion of your slide.  This can be same as the **date **on the bottom of the slide, but can also be formatted differently or contain additional information.
-   **Headline:** The name of your slide. It will likely be the name of an event, though it can be anything that makes sense with your story! This appears again on the bottom-portion of the slide.
-   **Text:** Additional text that helps tell your narrative.
-   **Credit:** Space to provide credit and sourcing information for your media. This can include links as well as text.
-   **Caption:** Short text that describes your media. While not required, it's a good idea to use a caption, as it's helpful for screenreader users, those with slower internet connections, and in cases where your media may not load.

**Timeline Portion of Slide (Bottom)**

-   **Date:** This is when the event in your slide takes place. It can be very specific (a single day) or broader (a span of years).
-   **Headline:** This will be the same headline from the top-portion of the slide
-   **Group:** Groups are a way of tagging related events, letting you showcase similar event subjects or types from anywhere in your chronology. Events in the same group appear on the timeline within the same horizontal row. In the Fandom History example, slides are grouped into media types.

Except for the date, all of these components are optional. So, you can pick and choose what makes the most sense for your slide. While including all of these components can help you tell a more complete, media-rich, narrative, there may be times where certain components don't make sense for the story you're telling.

#### *For Title Slides:*

The title slide can contain all of the same components as the event slides. However, it is not tied to any specific event or period of time:

![Title slide for History of Fandom](/images/timelinejs/title-slide.png)

## Step 2: Planning Your Timeline

It is helpful to outline your content *before* making your Timeline. Outlining ensures you have a strong, chronological story to tell that won't get lost in the technical weeds when you start making your timeline.

### Pick a Subject

Start by picking a subject for your timeline. Make sure to choose a subject that has a strong chronological component. Remember, visualization creates a narrative, so your timeline will likely do at least one of the following things:

- Show how something (a city, an art form, a movement, etc.) changes over time
- Show how specific events (social movements, passing of laws, earning a degree) lead to later events
- Highlight the pacing of events (the speed of a romance in a book, the long lead-up to a historical election, a sudden career switch, etc.)

### Plan Out Slides

Start thinking about which slides to include. It's often good to start small and build out if it makes sense. A timeline with over 20 slides might be hard for people to navigate. Reflect on the story you want to tell, which events are necessary, what do you leave out? Once you have a list of 5-10, you can start to create your timeline. While you're listing out your events, pay attention to whether these events can be organized into groups or categories. This isn't necessary, but can be a useful way to provide more information.

You may also want to start thinking more about your content: What would you like to say in your description of each one? What media (photo, video, etc.) will you show for each one? It's useful to think about your content before you start making your TimelineJS.

## Step 3: Create Your Timeline

It's time to start using the TimelineJS tool! This [tutorial](https://youtu.be/Mu8NyRk_ja4), by EdTechTeacher, gives a nice overview of how to use TimelineJS. If you're new to TimelineJS, I'd recommend watching it before we go through the steps together.

### Return to Your Spreadsheet

In Step 1 of this tutorial, you should have created a copy of the TimelineJS spreadsheet. If you haven't done that, go ahead and do that now. Once you've copied the spreadsheet, the first thing you'll want to do is change the name of your spreadsheet, that way, it will be easier to find later. There's currently sample content in the spreadsheet, and soon we'll be changing it to our own content. First, however, there are a couple of things to know about working with the spreadsheet:

-   Do not change the headers in Row 1; these are key for turning your spreadsheet into a Timeline
-   Do not leave rows empty, as this will cause your timeline to break. It's fine to have some blank rows at the end - but make sure you don't skip any rows between your content!

### Add Your Title Slide

The title slide is the only slide that doesn't require a date. It will be located on the *second row of your spreadsheet.* Each row that is not the title row will represent a new slide in your timeline. You can replace the text currently in the second row with your title and description under the Headline and Text columns. As a note, your title row does not *have* to be on the second row of the spreadsheet. As long as you have designated it as the title under the Type column, that slide will show up first.

After you've added your title and description, you're ready to add media. Your media can be an image, video, social media post.  You can  view [a list of all media types TimelineJS accepts](https://timeline.knightlab.com/docs/media-types.html) on their website.
If you read the [StoryMapJS Tutorial](), you may notice that there is no option to upload media. If your media cannot be found online, you will need to upload it to Dropbox or Google Drive and make sure the image is shared publicly. More information on embedding media can be found below.

-   There are some media platforms - such as [flickr](https://www.flickr.com/), [imgur](https://imgur.com/), [YouTube](https://youtube.com/), and [Vimeo](https://www.vimeo.com/)- that integrate easily with TimelineJS. If you're using one of these platforms, you can simply enter the web URL for your media. *Example:* [https://www.flickr.com/photos/barnardcollege/38058641542/in/album-72157687854677831/ ](https://www.flickr.com/photos/barnardcollege/38058641542/in/album-72157687854677831/)
-   If you're using media hosted somewhere that doesn't automatically integrate with TimelineJS  (Dropbox, a museum collection, a personal website etc.) make sure that you are linking to the image  itself, not the page where it lives. **This is one of the most common mistakes with TimelineJS.** **Your URL should have a media extension in it, such as .jpg, .png, .gif, .mp4, or .wav.**
    - *Incorrect Link*: [https://www.metmuseum.org/art/collection/search/49186](https://www.metmuseum.org/art/collection/search/49186)
    - *Correct Link*: [https://images.metmuseum.org/CRDImages/as/original/DP205729_CRD.jpg](https://images.metmuseum.org/CRDImages/as/original/DP205729_CRD.jpg)
-   The media thumbnail cell is usually best left blank; it lets you add tiny images to your timeline but can be tricky to use.

  ***Additional Cells:** The last three cells give additional options for customization. We've already added the "type" information, and the "group" cell is only relevant for events slides. The background cell lets you change your slides background - you can use an image file, a [CSS color name](https://www.w3schools.com/cssref/css_colors.asp), or a [hex code](https://www.hexcolortool.com/).

<img src="/images/timelinejs/8-timeline.png" width="20%" alt="title, group and background cells">

You've finished your title slide! Now, let's move on to an event slide.

### Step 4 - Making an Event Slide

Making an event slide is very similar to making a Title slide, with one key difference: You'll need to add dates. Let's turn our attention to the next row (row 3), where there is a sample event slide:

<p align="center">
 <img align="center" width="60%" src="/images/timelinejs/9-timeline.png" alt="Date information cells: start year, month, date and time; end year, month, date and time; display date">
</p>

In this example, there is both a start date (November 1, 2011) and an end date (December 15, 2011), showing that an event occurred over a range of time.  However, the date can also just be a single date, month or year.

The date (or range of dates) will appear both on the top and bottom of the slide, as shown below. This slide was generated by the data in the example spreadsheet:

<p align="center">
 <img align="center" width="100%" src="/images/timelinejs/10-daterangexample.png" alt="slide where date range appears on the top and the bottom">
</p>
You can also add in a display date to override the date information that appears in the top portion of your slide. You might do this because you don't like the TimelineJS date format, or because there's some additional context you want to add. In the example below, I used "Spring 1903" as the display date to provide a bit more information to viewers.

Here's how this works: this spreadsheet,

<p align="center">
 <img align="center" width="60%" src="/images/timelinejs/11-timeline.png" alt="date cells with year as '1903' and display date as 'Spring 1903'">
</p>

will generate a slide that looks like this:

![Slide showing location of display date and date](/images/timelinejs/12-slidexampleagain.png)

Now that we've seen how dates work, **add dates for your first event slide, and then fill out the text and media cells the same way we did for the title slide.**

Next, we get to the additional cells:

-   For an event slide, leave the type blank.
-   For group, you can optionally add the name of a group to show up on the bottom of your timeline. For the Greek Games timeline, I added the groups hoop rolling and hurdles. To add a group, just type its name in the corresponding cells (shown in row 4 below).
-   Just as you did on the title slide, you can change the background of your event slide.

Completed event slide rows should look similar to rows 3 & 4 below (but with your own content, of course!)

### ![3 rows of timelinejs spreadsheet](/images/timelinejs/13-timeline.png)

Now that you know how to make event slides, you can **complete the rest of the slides on your timeline.** Here is a guide and two sample spreadsheets to help you out if you get stuck:

-   [TimelineJS Spreadsheet documentation](https://timeline.knightlab.com/docs/using-spreadsheets.html)
-   [Women in Computing Sample Spreadsheet](https://docs.google.com/spreadsheets/u/1/d/1xuY4upIooEeszZ_lCmeNx24eSFWe0rHe9ZdqH2xqVNk/pubhtml)
-   [A Photographic History of the Barnard Greek Games Spreadsheet](https://docs.google.com/spreadsheets/d/1JUEDu68qzv2STUsHIb7fpCA6UT49l54_0VoT7sfq-IU/edit?usp=sharing)

Once you've finished making your slides, you can add eras to your TimelineJS. If you don't have any eras you want to add, you can skip to Publishing & Previewing Your Timeline.

### Step 5 - Adding Eras (optional)

As a reminder, eras are colored bars representing spans of time across the bottom of your Timeline, like in this example:

![eras on bottom of timeline slide](/images/timelinejs/14-timeline.png)

Just like slides, you add an era to your TimelineJS by adding a row to your spreadsheet. Since eras don't show up as full slides, you only need to fill out a few of the cells: **add your start and end dates, give your era a name in the "headline" cell, and set "type" to "era."** All other cells can be left blank. Here are some completed era rows as an example:

![era rows showing filled out dates, headline and type - other cells are left blank](/images/timelinejs/15-timeline.png)

At last, you're done with your spreadsheet!

Publishing & Previewing Your Timeline

Now that you've finished your spreadsheet (the most difficult part!), it's time for TimelineJS to do its magic and turn your spreadsheet into a Timeline.

The easiest way to do this to **follow steps 2 through 4** on the  [Timeline website](https://timeline.knightlab.com/), in the Make A Timeline section.  We've already done the first step, creating a spreadsheet.  Screenshots of the steps are shown below for reference:

<p align="center">
 <img align="center" width="70%" src="/images/timelinejs/16-step2.png" alt="step2 from Timeline instructions - visit Timeline website for accessible version">

 <img align="center" width="70%" src="/images/timelinejs/17-step3.png" alt="step3 from Timeline instructions - visit Timeline website for accessible version">

 <img align="center" width="70%" src="/images/timelinejs/18-step4.png" alt="step 4 from Timeline instructions - visit Timeline website for accessible version">
</p>

Preview your TimelineJS, and see if you want to make any changes! You can edit your Timeline just by making changes in the spreadsheet - no need to republish!

Finally, you can also share your TimelineJS!

# Reflections:
- In what ways did the TimelineJS tool expand how you think about time-based narratives?
- In what ways were you constrained by the TimelineJS tool?
- How might this tool help you "think digitally" about your project or course?

# Resources:

## Examples of Successful Projects:
A full list of the examples used in this tutorial (as well as some other projects) is included below:
- [The View From Ginling](https://mct.barnard.edu/home/timeline)
- [Columbia University and the Slavery Timeline](https://slaveryexhibits.ctl.columbia.edu/timeline-narrative)
- [Taxi Driver Scene Analysis; Shot by Shot](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1B6r1s4HiDH3wRS59jtW-U1juyD351QqffC7u5xjaxP4&font=Default&lang=en&initial_zoom=2&height=750)
- [A Photographic History of Barnard's Greek Games](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1JUEDu68qzv2STUsHIb7fpCA6UT49l54_0VoT7sfq-IU&font=Georgia-Helvetica&lang=en&initial_zoom=1&height=650)
- [TimelineJS Examples Gallery](https://timeline.knightlab.com/#examples)
- [Holocaust Timeline](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ZUmudkku1flT4GeXdCAEs9TnVpVVSzYTqHPUzsVkuZA&font=Default&lang=en&timenav_position=top&initial_z)

## Syllabi/Assignments using this tool:
- [Gender, Sexuality and Space](https://commons.trincoll.edu/amst-gss/) (Trinity College)
- [View From Ginling](https://mct.barnard.edu/home/about) (Barnard College, Spring 2018)

## Other Guides & Tutorials:
- [How to Build a Timeline using TimelineJS](https://www.storybench.org/build-timelinejs-digital-storytelling-timeline-tool/): Shows an approach for starting with a large, open data-set
- [TimelineJS Documentation & Help](https://timeline.knightlab.com/docs/index.html): Includes guides for more advanced features, such as further customizing the look and feel of your Timeline using code

## Barnard Resources:
- Barnard faculty, staff, and students are free to reach out to the [DHC](https://digitalhumanities.barnard.edu/) or [IMATS](https://imats.barnard.edu/) for additional help!
