Hi Randi! 

The basic steps I took in creating this quick rails API were as follows:

1. created a quick Apps scaffold to jump into the pagination aspect quickly and efficiently, I also like how scaffold will shoot some basic testing our way.

2. Jumped into the pagination aspect in my render json formatting, which is rendered in the /apps.json endpoint. pagination can be called on it by using the query selecter "?page=" - simply put a number after the equal sign for which page you'd like to navigate to. my .paginate method in the index method of the apps controller comes from the will_paginate gem. 

3. I also threw a quick edit in the seed file afterwards, so it would be easier for you to seed the db for testing purposes. 

4. I really wasn't 100% sure on how to deal with the range, so I'd love to hear back on that from you guys. Thank you!

Mike
