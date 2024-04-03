# What is structured data
- Helps google better understand the context of your pages
- Structured data is mark up language
- Google uses structured data that it finds on the web to understand the content of the page, as well as to gather information about the web and the world in general. 

# Primary source of structured data
- Schema.org is the organization that creates the standardized language and rules used for structured data.
- Schema.org is accepted and understood by google

# What is JSON-LD?
- JSON-LD is a script that can be placed within a webpage to communicate structured data to search engines.
- Googles preferred format, simple to use

# 3 ways to implement structured data
- Work with a developer 
- Use a plugin
- Add it manually

# Basic steps to add structured data to a page
1. In the head HTML of your webpage, add a script element to JSON-LD
2. Inside that script element tell google you're using Schema.org structured data.
3. Based on the type of content you're describing, tell Google which kind of structured data you're using.
4. Add all the required and recommended properties to give Google more information about the content being described.

```
    // example
    <script type="application/ld+json">
    {
      "@context": "https://schema.org/",
      "@type": "Recipe",
      "name": "Party Coffee Cake",
      "author": {
        "@type": "Person",
        "name": "Mary Stone"
      },
      "datePublished": "2018-03-10",
      "description": "This coffee cake is awesome and perfect for parties.",
      "prepTime": "PT20M"
    }
    </script>
``` 

# Test your structured data
- Make sure to test your page by using Google's Rich Results Test and Structured Data testing tool. 
- https://developers.google.com/search/docs/appearance/structured-data

