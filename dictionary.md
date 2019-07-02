# Dictionary

#### Accessibility

Basically, this is the ability of a website to be used by people with disabilities, including visually impaired visitors using screen readers, hearing impaired visitors using no sound, colour blind people, or those with other disabilities. A website with low accessibility is basically going to be impossible for those with disabilities to use. Accessibility is particularly important for sites providing information to those with disabilities \(healthcare sites, government sites, etc.\), though it is an important aspect to consider when designing any site.



#### AJAX

Stands for Asynchronous JavaScript and XML. AJAX is typically used for creating dynamic web applications and allows for asynchronous data retrieval without having to reload the page a visitor is on. The JavaScript on a given page handles most of the basic functions of the application, making it perform more like a desktop program instead of a web-based one.

```javascript
  $.ajax({
    type:"GET",
    url:"https://api.meetup.com/2/cities",
    success: function(data) {
      $('.text').text(JSON.stringify(data));
    },
    dataType: 'jsonp',
  });
```



#### API - Application Programming Interface

An application-programming interface \(API\) is a set of programming  instructions and standards for accessing a Web-based software  application or **Web tool**. A software company releases  its API to the public so that other software developers can design  products that are powered by its service.

```http
GET /v1/locations/search?access_token=ACCESS_TOKEN&lat=40.7127&lng=74.0059
```

