# **Milestone Project One**

***

## **Overview**

***


I decided to design my project around the suggested theme given in the example brief for the User Centric Frontend Development project: a website for a band. However, instead of using the assets and band background information provided, I decided to design a website for another well-known band. While preparing and looking for inspiration for this project, I looked at the current websites for many bands, from many different genres. During this research stage, I noticed that in spite of the fact that ‘Pink Floyd’ is a huge name in the music industry, with shows inspired by their music still being performed to this day, they seem to have an outdated website. For this reason, I thought that it would be an interesting project to design a new website for their band. As they have a huge catalogue of music, a logo, a unique sound, and identifiable artwork and imagery, it would not be a struggle to find appropriate and useful content that could be used for the site.

My website can be found at the following URL: [https://beibhinn.github.io/milestone-project-one/](https://beibhinn.github.io/milestone-project-one/)

## **UX**

***

### **User Stories**

* As a new fan, I want to read information about the band and their performances, so that I can understand their history and what to expect from a concert.

* As a current fan, I want to listen to the band’s music, so that I can support the band and keep up-to-date with new music.

* As a prospective fan, I want to be able to access the band’s back catalogue, so that I can discover other songs I enjoy.

* As an event organiser, I want to listen to the band’s catalogue, so that I can make an informed decision regarding whether the band has the sound I am looking for for an event I am organising.

* As a current fan, I want to watch the band’s music videos, so that I can get the full auditory and visual experience for a song.

* As a new fan, I want to watch music videos, so that I can better understand the imagery associated with Pink Floyd.

* As a fan, I want to be able to see photos of the band, so I can see what the members looked like back when they first started out, as well as now.

* As a fan, I want to be able to find a list of upcoming tour dates, so that I can see if the band is performing near me in the near future.

* As a fan, I want to be able to find where tickets for the band’s concerts are on sale, so that I can purchase a ticket and attend a concert.

* As a business user, I want to be able to see a list of dates and events the band will be performing at, so that I can estimate the band’s availability before contacting their representatives with a booking enquiry.

* As an event organiser, I want to be able to contact the band and/or their representatives, so that I can make an enquiry about booking the band for an event. 

* As a fan, I want to be able to easily find links to the band’s other social media sites, so I can keep up-to-date with any new posts, information, music and videos.

The wireframes I created for this project can be viewed [here.](https://beibhinn.github.io/milestone-project-one/Project1-Mockup.pdf) 

## **Features**

***

### **Existing Features**

* Navbar: Allows all users to easily navigate to the different pages of the website, regardless of which page they are currently on.

* Home page: Fans and business users can find basic information on the band, as well as what to expect from their performances, in the ‘Who we are’ and ‘What we do’ sections.

* Music page: Allows fans to listen to 30 second samples of Pink Floyd’s music without logging in to spotify, simply by selecting a song. The user can also access full songs and the complete back catalogue once the user logs in.

* Videos Page: Fans can watch a selection of music videos directly on the site, as well as following a link to see more videos on Pink Floyd’s music channel.

* Photos: Users can visit this page in order to see a gallery of photos of the band.

* Tour Page: Event organisers/ business users can check the tour page for a list of confirmed tour dates, in order to determine whether the band may be available to book for an event. Fans may also visit this page to see if the band has a concert scheduled in their area. They will also find links where they can purchase tickets. (Please note: the band does not currently have any upcoming concerts, and so the events listed on this page will not actually feature Pink Floyd. The concerts listed are merely examples, to demonstrate how the tour dates will appear on the page).

* Contact Page: Allows business users/ concert organisers to enquire about booking the band for festivals or charity events, by filling out the ‘Contact Us’ form on this page. 

* Footer: Allows users to view copyright information, as well as accessing links to the band’s relevant social media pages.

### **Features Left to Implement**

* As the band and its members are not as active as they once were, I felt that a ‘news’ section was not an urgent feature that needed to be included in the initial website. However, it may be an interesting feature to add in the future, in particular if the band starts to release new music or announces new tour dates.

* It may be beneficial to include individual bios for each of the band members, including background information and information about their roles in the band.

* As the band have so many recognisable album covers, videos and graphics, fans of the band may like the option to purchase official band merchandise through the site.

## **Technologies Used**

***

* *HTML5:* HTML5 was used to create the structure of the website

* *CSS3:* CSS3 was used to style the website

* *Bootstrap 3.3.7:* [https://getbootstrap.com/docs/3.3/getting-started/](https://getbootstrap.com/docs/3.3/getting-started/) : This framework was used to help create a stylish and well-structured website, while also ensuring that the site would be compatible on mobile devices, using the Mobile First Approach.

* *JQuery: *[https://jquery.com/](https://jquery.com/) : A JQuery script was used in this project for the collapsable menu on mobile devices.

* *Font Awesome: *[https://fontawesome.com/](https://fontawesome.com/) : Font Awesome was used to add icons to the site, such as the social media icons in the footer. 

## **Testing**

***

HTML was copied and pasted into [https://validator.w3.org/#validate_by_input](https://validator.w3.org/#validate_by_input) to determine validity. One notable warning was for the contact.html page, which highlighted that the ‘date’ input type may not be supported in all browsers, and that use of a polyfill should be considered.

Css was copied and pasted into [https://jigsaw.w3.org/css-validator/#validate_by_input](https://jigsaw.w3.org/css-validator/#validate_by_input) to determine validity.

1. Home page: 

    1. Go to the home page: index.html.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Pink Floyd’ logo.

    3. Read through the information provided, to verify that it is readable.

    4. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

2. Music: 

    1. Go to the ‘Music’ page.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Music’ link. 

    3. Click on some songs, to ensure that a 30 second clip plays, and that a prompt appears encouraging the user to sign in to spotify to listen to complete tracks.

    4. Scroll along the page and ensure that the iframes are the correct height, to display all songs on each album. 

    5. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

3. Videos:

    1. Go to the ‘Videos’ page.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Videos’ link. 

    3. Click on a video to ensure that it plays correctly.

    4. Click on the link to Pink Floyd’s YouTube channel underneath the videos, to verify it takes the user to the correct page.

    5. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

4. Photos: 

    1. Go to the ‘Photos’ page.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Photos’ link. 

    3. Scroll along the page to ensure each photo is displayed, and that they appear in columns of equal width. 

    4. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

5. Tour: 

    1. Go to the ‘Tour’ page.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Tour’ link. 

    3. Hover over each line of the ‘Upcoming Dates’ table, to ensure that they highlight in a different colour. 

    4. Click each link to purchase tickets, ensuring that no link is broken. 

    5. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

6. Contact: 

    1. Go to the ‘Contact’ page.

    2. Verify that the navbar is functioning correctly by navigating away from the page using the relevant links in the navbar, and back using the ‘Contact’ link. 

    3. Try to submit the empty form without inputting any information, to verify that an error message appears advising that some fields are required.

    4. Try to submit the form with an invalid input in the ‘email’ box. Verify that the form will not submit, and that an error message appears advising the user to add a valid email.

    5. Try to submit the form with valid information and verify that no errors appear.

    6. Click each social media link in the footer, to ensure they work correctly and that they bring the user to the correct page in a new tab. 

The project was tested and works across all major browsers, including Google Chrome, Internet Explorer, Firefox, and Safari. 

The website was tested for various screen-sizes, using chrome developer tools.This ensures that on smaller screens content takes up the full width of the screen, and is stacked, with content spreading out, sharing the screen space, and scaling upwards for larger screens.

Where possible, I also tested the website on mobile devices themselves. One downside to the chrome developer tool method of testing, meant that some issues might not be noticed immediately. In my case, everything seemed to be working correctly when viewed in the developer tools, however there was an issue with scrolling on apple devices with touch screens. I sent a link to my site to various people for testing, and it was only when it was tested on an actual iPhone that the problem was brought to my attention and fixed. 

An interesting issue I came across was that when the background-attachment attribute of ‘Hammers.gif’ on the homepage was set to ‘fixed’, this would zoom in and scale strangely on iPhones. When I researched this issue it seemed to be an issue with Apple, and the only solution I could find was to set the background-attachment attribute to ‘scroll’ for small devices.		

## **Deployment**

***

The process used to deploy my code was very simple. 

1. On GitHub, I went to the repository for the project.

2. Then I clicked into ‘Settings’ for the repository.

3. I then scrolled down to the ‘GitHub Pages’ section of the settings.

4. I selected ‘master branch’ from the ‘source’ dropdown menu.

5. Finally, I clicked save. 

6. From that point on, whenever I pushed to ‘master’, the live website would be updates.

My website can be found at the following URL: [https://beibhinn.github.io/milestone-project-one/](https://beibhinn.github.io/milestone-project-one/)

## **Credits**

***


### **Content**

The text for the "About us" and “What we do” sections on the homepage were taken from the PInk Floyd Wikipedia page, and subsequently edited.  https://en.wikipedia.org/wiki/Pink_Floyd

### **Media**

***Music:*** All music was found on Pink’s Floyd’s spotify page, and a widget was provided for each album. The clips of the songs are streamed using Spotify’s service, and the band will receive royalties for songs streamed on this platform. 

***Images:*** All images were obtained through google Images, using the search term ‘Pink Floyd’. Link locations provided for each of the images below. The rights to the images belong to the original creator, and no copyright infringement is intended. 

[https://78.media.tumblr.com/345e958c8421a9190eb324892b12c59a/tumblr_o2h8hwgACx1v8nha6o1_500.gif](https://78.media.tumblr.com/345e958c8421a9190eb324892b12c59a/tumblr_o2h8hwgACx1v8nha6o1_500.gif)

[https://upload.wikimedia.org/wikipedia/en/d/d6/Pink_Floyd_-_all_members.jpg](https://upload.wikimedia.org/wikipedia/en/d/d6/Pink_Floyd_-_all_members.jpg)

[https://i.imgur.com/rQEl9iA.jpg](https://i.imgur.com/rQEl9iA.jpg)

[https://steamuserimages-a.akamaihd.net/ugc/882980616387674235/42C714A7E69BBEED5A9A9ABFB0F0DA89A560399E/?interpolation=lanczos-none&output-format=jpeg&output-quality=95&fit=inside%7C637%3A358&composite-to=*,*%7C637%3A358&background-color=black](https://steamuserimages-a.akamaihd.net/ugc/882980616387674235/42C714A7E69BBEED5A9A9ABFB0F0DA89A560399E/?interpolation=lanczos-none&output-format=jpeg&output-quality=95&fit=inside%7C637%3A358&composite-to=*,*%7C637%3A358&background-color=black) (edited)

[http://ichef.bbci.co.uk/images/ic/960x540/p01bqhlb.jpg](http://ichef.bbci.co.uk/images/ic/960x540/p01bqhlb.jpg)

[https://pm1.narvii.com/6944/7df1a981870afff719a7b988a24c61942bf1633cr1-900-900v2_hq.jpg](https://pm1.narvii.com/6944/7df1a981870afff719a7b988a24c61942bf1633cr1-900-900v2_hq.jpg)

[https://www.starsend.org/graphics/pinkfloyd02.jpg](https://www.starsend.org/graphics/pinkfloyd02.jpg)

[https://i.pinimg.com/originals/a8/3c/c2/a83cc213913de585c06ba00693df842e.jpg](https://i.pinimg.com/originals/a8/3c/c2/a83cc213913de585c06ba00693df842e.jpg)

[https://www.rollingstone.com/wp-content/uploads/2018/06/rs-11423-floyd-624-1371495488.jpg?crop=900:600&width=440](https://www.rollingstone.com/wp-content/uploads/2018/06/rs-11423-floyd-624-1371495488.jpg?crop=900:600&width=440)

[https://i.imgur.com/FKtmeYU.jpg](https://i.imgur.com/FKtmeYU.jpg)

[https://i.redditmedia.com/2CEy1U2cpXy3_Ap-rkQN_IOkm3BOjr1ZlfnaALcTL8w.jpg?w=320&s=e5da0616fc097a1f2935adaf8bb480b3](https://i.redditmedia.com/2CEy1U2cpXy3_Ap-rkQN_IOkm3BOjr1ZlfnaALcTL8w.jpg?w=320&s=e5da0616fc097a1f2935adaf8bb480b3)

[https://ksassets.timeincuk.net/wp/uploads/sites/55/2014/07/2014PinkFloyd01PR200514-2.jpg](https://ksassets.timeincuk.net/wp/uploads/sites/55/2014/07/2014PinkFloyd01PR200514-2.jpg)

[https://news.ievenn.com/wp-content/uploads/2018/09/38682570_401.jpg](https://news.ievenn.com/wp-content/uploads/2018/09/38682570_401.jpg)

[http://78.media.tumblr.com/d1c5dbadea2fa1cd0cbefa048717dad7/tumblr_msswtuBlVO1rggk7po1_1280.jpg](http://78.media.tumblr.com/d1c5dbadea2fa1cd0cbefa048717dad7/tumblr_msswtuBlVO1rggk7po1_1280.jpg)

[https://cdn.mos.cms.futurecdn.net/5r5xffE6LxqXyAna6wu9VP-320-80.jpg](https://cdn.mos.cms.futurecdn.net/5r5xffE6LxqXyAna6wu9VP-320-80.jpg)

[http://www.designcurial.com/Uploads/NewsArticle/5813552/main.jpg](http://www.designcurial.com/Uploads/NewsArticle/5813552/main.jpg)

[https://pbs.twimg.com/media/DXwI4yvXUAA3Koa.jpg:large](https://pbs.twimg.com/media/DXwI4yvXUAA3Koa.jpg:large)

[https://lastfm-img2.akamaized.net/i/u/ar0/5b20b6db2b74ef98b5bd170b4de7f75d.jpg](https://lastfm-img2.akamaized.net/i/u/ar0/5b20b6db2b74ef98b5bd170b4de7f75d.jpg)

[https://llcdn.listelist.com/listeliststatic/2018/06/08170358/pink-floyd-1.jpg](https://llcdn.listelist.com/listeliststatic/2018/06/08170358/pink-floyd-1.jpg)

[https://llcdn.listelist.com/listeliststatic/2018/06/08170358/pink-floyd-1.jpg](https://llcdn.listelist.com/listeliststatic/2018/06/08170358/pink-floyd-1.jpg)

[https://direct.rhapsody.com/imageserver/images/Art.69132/356x237.jpg](https://direct.rhapsody.com/imageserver/images/Art.69132/356x237.jpg)

[https://3m84r11gpx1j11puas2g5wfl-wpengine.netdna-ssl.com/wp-content/uploads/2017/09/PinkFloydHouseholdObjtects.jpg](https://3m84r11gpx1j11puas2g5wfl-wpengine.netdna-ssl.com/wp-content/uploads/2017/09/PinkFloydHouseholdObjtects.jpg)

[http://image.iheart.com/images/rovi/1080/0001/428/MI0001428642.jpg](http://image.iheart.com/images/rovi/1080/0001/428/MI0001428642.jpg)

[https://i0.wp.com/get.wallpapers8k.com/wallpapers/5/f/a/72935.jpg?w=760](https://i0.wp.com/get.wallpapers8k.com/wallpapers/5/f/a/72935.jpg?w=760)

***Videos:*** All videos were taken from the Pink Floyd YouTube channel. 

*Learning to Fly-*    
-Artist: Pink Floyd
-Writers: David Gilmour, Anthony Moore, Bob Ezrin, Jon Carin
-Licensed to YouTube by: Pink Floyd (on behalf of PLG UK Catalog); União Brasileira de Compositores, Pink Floyd Music Publishers, CMRRA, UBEM, ASCAP, and 18 music rights societies 

*High Hopes-*         
-Artist: Pink Floyd
-Writers: Polly Samson, David Gilmour
-Licensed to YouTube by: Pink Floyd (on behalf of Pink Floyd Music Ltd.(2016)); UBEM, Pink Floyd Music Publishers, and 14 music rights societies

*Marooned-*       
-Artist: Pink Floyd
-Writers: Richard Wright, David Gilmour
-Licensed to YouTube by: Pink Floyd (on behalf of Pink Floyd Music Ltd.(2016)); UBEM, and 12 music rights societies

*Another Brick In The Wall, Part 2-* 
-Artist: Pink Floyd
-Writers: Roger Waters
-Licensed to YouTube by: Pink Floyd (on behalf of Pink Floyd Music Ltd.(2016)); BMG Rights Management, ARESA, Abramus Digital, UMPI, CMRRA, and 10 music rights societies

*Louder Than Words-*
-Artist: Pink Floyd
-Writers: David Gilmour, Polly Samson
-Licensed to YouTube by: SME, WMG (on behalf of Columbia); Pink Floyd Music Publishers, UBEM, and 10 music rights societies

*Comfortably Numb-* 
-Artist: Pink Floyd
-Writers: David Gilmour, Roger Waters
-Licensed to YouTube by: Pink Floyd (on behalf of EMI Records); Pink Floyd Music Publishers, ARESA, UBEM, BMG Rights Management, CMRRA, Abramus Digital, UMPI, and 10 music rights societies

*Grantchester Meadows-*
-Artist: Pink Floyd
-Writers: Roger Waters
-Label: Harvest Records

*Shine On You Crazy Diamond-*
-Artist: Pink Floyd
-Writers: Richard Wright, David Gilmour, Roger Waters
-Licensed to YouTube by: Pink Floyd Music Publishers, BMG Rights Management, UMPI, and 5 music rights societies

*Welcome To The Machine-* 
-Artist: Pink Floyd
-Writers: Roger Waters
-Label: Harvest (UK), Columbia/CBS (US)

*Take It Back-*
-Artist: Pink Floyd
-Writers: David Gilmour, Bob Ezrin, Polly Samson, Nick Laird-Clowes
-Label: EMI (UK), Columbia (US)

*Point Me At The Sky-*
-Artist: Pink Floyd
-Writers: David Gilmour, Roger Waters
-Label: Columbia (EMI) (UK), Capitol Records (Canada)

*The Final Cut-* 
-Artist: Pink Floyd
-Writers: Roger Waters
 -Label: Harvest Records (UK), Capitol Records (US)


### **Acknowledgements **

I received inspiration for this project from the official [Pink Floyd website,](http://www.pinkfloyd.com/) as well as from the [Queen website](http://www.queenonline.com/), and [the Police website.](https://www.thepolice.com/)

