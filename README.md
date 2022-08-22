A website that contains some of websites or catagories .. and each websites contains some of the posts. Anyone can create any website, delefe it, and add posts within these websites. And if someone subscribes to one of these websites, he will get an notification to his e-mail when a post is created within that website and contains the content of the new post.




Endpoint to create a "post" for a "particular website" 
>Done

Endpoint to make a user subscribe to a "particular website" with all the tiny validations included in it.
>Done

No duplicate stories should get sent to subscribers.

>I fixed this problem by that the user can not subscribe to the site twice
So he will get an email every time a post is published on the site he subscribes to

Use of queues to schedule sending in background.
>I used queue in order not to cause problems to the server and to send emails in the background
If you send the email without using the queue, the site will not be able to send emails to a large number of users and it will take a lot of time


