-Header and footer had div element tags with classes "header" and "footer". It is more semantic to use header and footer tags.
-nav tags were used for the link navigation bar at the top of screen.
-The title is now called "Horiseon" since that is the name of the company.
-All image elements now include an "alt" describing the image.
-Since the marketing meeting image is used in one instance, an ID was assigned to it. The "hero" css class was changed to an id.
-Main and aside tags were used to specify the area where the main contents and side information are contained, respectively.
-Section tags were used in the containers with information pertaining to a specific single topic. 
-An ID was assigned to the "search-engine-optimization" div element so the link in the header functions properly.

-For css, any time there were classes with the same body contents, these classes were consolidated, since the same class can be used in multiple instances.
    For example, there were 3 different "benefit" div classes that had the exact same contents. A class name was chosen that is universal to the three benefits,
    and the same common contents were used in the class body. 
-The h2 in the "content" class div had a unique h2. Same for the footer h2. 
    allows us to declare:
        when h2 is used within the class "contents", use xyz styling. If used in footer, use abc styling. If used anywhere else use default styling. 
-Created classes specific to main and aside images and text so that if anything is added the developer can just create a new class, rather than using nesting.
-Ensured h1>h2>h3 in font size.


