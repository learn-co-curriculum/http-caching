# HTTP Caching

So far we have looked at how to retrieve an already calculated value.  We have seen how we can retrieve values in ruby instead of reperforming the calculation.  We have also seen how we can retrieve previously returned values in from a database, without running the database query.

With HTTP caching, we see how we can return a value of a previously run web request, without running that web request.

### Learn about HTTP Caching

First learn about HTTP caching by reading through the following document.

* [HTTP Caching](https://www.mnot.net/cache_docs/)

The document dicusses the benefits of caching, caching with expirations, and conditional caching (under the section labeled "Validators and Validation"). 

### Learn how to implement HTTP caching in rails 

Now that we understand some of the benefits of 

Now, take a look at the following railscast on how to implement HTTP caching in rails.  

* [Rails Caching](https://www.youtube.com/watch?v=8iCPR9BqlNA)

The railscast has an excellent explanation about etags and how they relate to caching.  Then it explains how we can influence how the etag is generated by using the `fresh_when` method in rails.  It also talks about making use of conditional caching with the `last_modified` method in rails.  Finally, it talks about how to make use of the max-age response by utilizing the `max_age` method.

You can learn more about etags and caching with rails through the following resource: 
 
* [Caching via RailsGuides](http://guides.rubyonrails.org/caching_with_rails.html#conditional-get-support)


<p class='util--hide'>View <a href='https://learn.co/lessons/http-caching'>HTTP Caching</a> on Learn.co and start learning to code for free.</p>
