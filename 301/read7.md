# REST

## How I explained REST to my brother

**Who is Roy Fielding?**

He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.

**Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?**

Because they weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.

**What is the HTTP protocol that Fielding and his friends created?**

HTTP—this protocol Fielding and his friends created—is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

**What does a GET do?**

GET, can be applied to many different nouns. Some verbs are more specific than others and apply only to a small set of nouns. For instance, I can't "drive" a cup and I can't "drink" a car. But some verbs are almost universal like GET, PUT, and DELETE.

**What does a POST do?**

If one system needs to add something to another system, it would use an HTTP verb of POST. If a system wants to replace something in another system, it uses an HTTP verb of PUT, or, to do a partial update, it'll hopefully use PATCH

**What does PUT do?**

Each of the systems would retrieve information from each other using a simple HTTP GET. If one system needs to add something to another system, it would use an HTTP verb of POST. If a system wants to replace something in another system, it uses an HTTP verb of PUT, or, to do a partial update, it'll hopefully use PATCH

**What does PATCH do?**

If a system wants to replace something in another system, it uses an HTTP verb of PUT, or, to do a partial update, it'll hopefully use PATCH.

Reference [**How I explained REST to my brother**](https://gist.github.com/brookr/5977550)

---

Reference [**Geocoding API**](https://locationiq.com/)

Reference [**Weather Bit API**](https://www.weatherbit.io/)

Reference [**Yelp API Docs**](https://www.yelp.com/developers/documentation/v3/business_search)

Reference [**The Movie DB API Docs**](https://developers.themoviedb.org/3/getting-started/introduction)

**Did you get your API keys?**

Yes

---

## Things I want to know more about

---
