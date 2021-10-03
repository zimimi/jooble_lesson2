# URL

http://djangodevops.azurewebsites.net/read

## Resources and Actions

All interface returns are in html format.

    URL                           HTTP         Operation
    /read                         GET          Get a collection of posts.
    /read?id=$value               GET          Show post by id. Example: /read_posts?id=2
    /read?n=$value                GET          Show last n posts. Example: /read_posts?n=3
    /create                       GET          Create post.
    /delete/$id                   GET          Delete post number $id
    /update/$id                   GET          Update post number $id

API created by Dima
Readme created by Dennis
