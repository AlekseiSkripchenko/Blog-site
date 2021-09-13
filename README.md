# Blog site.
This blog site created by using EJS templating.

![HomePage](https://i.ibb.co/4JHScCK/main-img.png)
---
### Main functions of the web site are:
- `Write` a post: 

![ComposePage](https://i.ibb.co/R7KC6xB/compose.png)
 
- `Publish` your post:

![Posts](https://i.ibb.co/rsHC9MP/home-page-with-posts.png)

- You can also reach a specific post using `Read More` button or `localhost:3000/posts/day1` in lower or upper case. Even with "kebab" case.

Thanks to [`lodash`](https://lodash.com/) npm!
```javascript
var _ = require('lodash');
const topic = _.lowerCase(req.params.topic);
```
---
### Currently I'm working on implementing `MongoDB` to store all the data.
Updates are coming very soon!
