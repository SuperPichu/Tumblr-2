Once completed, please transfer into a wiki format and add pictures. When fully refined, maybe add homemade gifs showing how the UI would work

# 0.0 BLAHBLAH DEFINITION
	- Blahblah is a social media application with a focus on blogging that's visually appealing. 
	
# 0.1 BLAHBLAH INTENDED USER EXPERIENCE
	- Blahblah will not only allow users to share their thoughts and creations, but also to carefully curate what content they see and in what content they want to see it in. 
	- This should help people with anxiety and burnout reel back on the emotional overload that social media has doubtlessly put us all through and put a little bit more control in users' hands regarding what content they choose to expose themselves to.
	- Moreover, giving users more control over the contexts in which they see content should encourage users to make things fit for each specific instance they occupy rather than getting overwhelmed by getting a firehose of everything all the time and just choosing to consume it rather than tangibly contribute to the online space.

# 0.2 REGISTRATION AND LOGIN
	- People can see posts individually but can't browse any of the instances without an account. The default URL will direct them to a registration screen. 
	- At the registration screen, users can enter an email address and a password. Once it is confirmed that there isn't another blog associated with 
	- Once signed up, users will be teleported to their new blog and given a short tutorial on how to customize their blog, if they so wish. Users can skip the tutorial and the exit button will be highlighted if they are either done customizing or don't wish to do it at all.
	- After that, the user will be automatically directed to the Home Instance. The "instance" button will then be highlighted so users would be invited to explore other instances.

# 1. DASHBOARD DEFINITION
	- The dashboard is the collection of posts that the user browses as their primary form of ingesting that sweet sweet milk that we call content. A dashboard is basically the user's posts and all of the posts made by the blogs they follow.
    
# 1.2 DASHBOARD HOME BAR
	- At the very top of the dashboard is an icon representing the instances a person is currently in which, if clicked, then teleports the user to a long bar with icons and folders containing all of the instances a user has already joined. The folders can have their own colors so users can visually organize them. If it gets too long, the user can tap and swipe right within this bar to access all the other ones.
   	 - On the second-to-last of the dashboard is the post bar, displaying the buttons that a person can click to format a post to a specific format (text, picture video, code, etc). 
   	 - As a user scrolls down, the site infiniscrolls to keep up with the user's scrolling and provide them with a reverse chronological order to all the posts. 
   	 - In the bottom-right corner is a button that allows the user to instantly teleport to the top of the page again if they wish to do something else. 

# 2. POST DEFINITION
   	 - A post contains media and/or text that a user uploads to the website. A blog can post 100 posts per day and the limit resets at 00:00 UTC time, but because this is a very high limit, most people shouldn't reach it. 
	 - Blogs can add things to posts like commentary, pictures, audio clips, etc.

# 2.1 POST BAR
   	 - The post bar is the bar from whence all posts of all kinds flow. 
   	 - There are seven types of posts: text, photo, (quote?), (link?), (chat?) ~~code~~, audio, video
     	   > text: Exactly what it says on the tin. Bloggers can edit text with traditional markup like bold, italics, underline, strikethrough, indents, etc. and they have a character limit of 2000 characters
	   	>>> a text break in the form of a 'read more' divider can hide the content of text posts until the user clicks on the button marking the divider that says 'read more' which teleports them to the blog page and the expanded post stored on it if the post is quite long / the writer wants to be courteous to the reader's scrolling experience. A text post's character limit of 2000 can be expanded to 5000 with the user of a 'read more' divider.
	> photo: A post containing a still image or a gif. A user can post up to eight still pictures or gifs on a single photo post as long as they are sized correctly. The golden ratio for a non-grid photo post is 500x750 and gridded photo sets are in total, 540 px wide and 810 px tall. 
       	> quote: A uniquely formatted text post that changes the font and size of the text and limits it to 300 characters. Every quote post must include a source at the bottom, be it from a book, a person, etc.
        > link: A post which formats an external link with a thumbnail, a headline, a description of the article or site being linked, and a button that opens a new window that allows you to visit the link without ctrl+c and ctrl+v.
		>>> (link had a relatively important function that allowed people to place thumbnails and descriptions to links in a way that text didn't do well on its own)
        > code: this allows users to format their code for developers and hobbyists to plug into their own editor. There is a 500 character limit on code lines and if you want to post more, you have to fit it under a "read more" divider so that the dashboard remains clean.
		>>> (chat is maybe the most wholly useless kind of post; the feel of chat can just be replicated by imitating greentext in a text post)
    - photo allows for gif
	> audio: people can post mp3 files of up to eight minutes that can feature a little thumbnail and a title on the audio player itself so people can get a good sense of what they're listening to. 
	> video eats bandwidth like crazy. a video _embedder_ so people can repost tiktoks and youtube is good but limit ORIGINAL videos to at most 1 minute.

# 2.2 POST FUNCTION
	- A post exists to do what drugs of all kinds do at burning man -- it gets passed around and enjoyed. 
	- Users can interact with posts in all of the following ways:
		> Reblogging (I think a good subtle way to encourage users to generate unique content is by labeling a reblog as a "pass," like you're passing a note in class around)
		> Commenting (instead of the twitter model creating a brand new post every time someone comments on someone else's post, this just displays the blog that created the original post, the post itself, the blog commenting on the post, and then the comment right under the link to the blog so that it's always clear who is doing the talking.
	- If a post needs workshopping, a user can save it as a draft until it's ready to post.
	- A post can also be marked as NSFW (18+)

# 3. BLOG DEFINITION
	- A blog is a dashboard housing the user's posts. It also exists to tell people more about the user attached to the blog. 
	- A blog can also be marked as NSFW (18+) this serves to act as a flag for any posts within it.

# 3.1 BLOG FUNCTION
	- Unlike a dashboard, a blog's appearance can be customized right down to the smallest detail. 
	- The default layout of a blog looks exactly like a smaller version of a dashboard with the user's profile picture floating in the upper lefthand corner, but with the home instance background color looking significantly paler. 
	- If a user clicks on their own blog, they can go to the "customize" function and choose between two levels of customization: 
		> Basic: Baby's first blog customizer. Add a picture background, change the color of the scroll bar and blog borders, add a little 'about me' page link right below the user profile, what the fuck ever. 
		> Advanced: This is where, if they so choose, users can go full myspace/geocities wackery with their blogs. We're talking butterfly cursor, music player, an animated banner up at the top that looks like one of those headline reels on CNN. As long as the in-browser editor can handle the code, then it should display. 
	- A blog can include "pages" that essentially take them away from the dashboard housing the user's posts and take them to a stationary page containing whatever they want it to contain like a widget or a single text file with a bunch of links. 
	- A user can also use the "queue" function on their blog to create a backlog of posts that they will automatically send out posts on a user's blog either at a fixed time each day/week/whathaveyou or schedule them at certain dates in the future. For ex. buttfuck69 may write a post declaring that he will devour the moon at 11:56 PM on a Tuesday two months from now and then _schedule_ a follow up post that just says "yum" two minutes after the time he stated so that when the lunar eclipse that NASA predicted comes around, people can have a good laugh at buttfuck eating the moon. 

# 4. INSTANCE DEFINITION
	- There is a stream of posts collected from the blogs that a user follows and organized into a dashboard. The blogs that a user follows and the posts organized into a dashboard come together to create an instance. 
	- The beta will provide users with a premade folder of little icons to clearly mark which instance is which (ex. a user can give an instance dedicated to gardening a cute flower icon and give an instance dedicated to studying for their compsci degree a little illustrated computer icon)
	- At the very top of the dashboard of an instance is a bar with four icons: home, instances, explore, and profile. 
	- If clicked, the user is teleported to a page displaying the instances as a long bar with icons and folders containing all of the instances a user has joined. The home instance is fixed at the absolute left of the bar. Users can create folders to click and drag icons into to better organize. The folders can have their own colors so users can visually organize them. If the bar containing these icons and folders gets too long, the user can tap and swipe right within this bar to access all the other ones.

# 4.1 INSTANCE FUNCTION
	- An instance basically serves to collect posts marked "private" and assign them to a certain dashboard. Each instance has a unique GUID that private posts are marked with, which keeps the post within that instance and not just floating around wherever it wants to go. 

# 4.2. THE HOME INSTANCE
	- All public posts are assigned to the home instance, which has its own default GUID. Whereas GUIDs for private instances are randomly and uniquely generated, the home GUID is fixed and cannot be replicated in the GUID generator. 
	- The home instance is the only instance that is marked with a little house icon and is separated from the rest of the instances. This is on purpose. 
	- The home instance also has a unique hex color background to differentiate it from other instances.

# 4.3. BROWSING INSTANCES
	- An instance is essentially like a discord server in that you have a collection of unique users posting on a unique dashboard.
	- Users can habitate as many instances as they'd like and they are allowed to create their own to better curate their user experience. 
	- Whoever creates the instance first chooses its background color. At the moment, there are no plans to make instances customizable and once a color has been chosen, it cannot be changed since it would involve giving instances a whole user hierarchy.
	- When a user hovers their cursor or first taps on the link to a new instance, a box should roll down and display a user-input description of the instance and a small preview of the content within the instance (2 - 4 trending or recent posts). 
	- Instances have three different levels of privacy, much like discord servers. They can 1) be joined by anyone who clicks on them and requests to join, 2) users can send a request to join the instance, or 3) an instance can only be accessed through a unique invite. 

# 5. USER DEFINITION
	- A user is the information about the person running a blog that helps connects their login information to their blog and the instances they occupy. 

# 5.1 USER FUNCTION
	- A user is basically a little nugget of info in a database tying login information and current instances occupied by a user to a blog.
	- In theory, this allows less information to be fixed within a database (like profile pictures) and so more customization can be done on a blog through the client (we would actually want to do this as much backend as possible, makes third party clients easier, which people want).

# 5.2 NECESSARY USER INFORMATION
	- A user must have a verified email address and/or a phone number along with a password in order to browse. 
	- Users must provide a birthdate.
	- Once a user gives this info to the database, they can then choose a username which they can change at any given moment. 
	- If they are losers and cowards, they can just autogenerate a username. (XKCD Password Generator) 
	
# 5.3 UNNECESSARY USER INFORMATION
	- Preferred name, pronouns, country of origin, caard/treelink page, etc.
	- A user can choose whether or not they'd like to publicly display all of the instances they're in. 

