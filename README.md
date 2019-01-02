## Senior Python Software Developer Code Test

Hello 👋!

Thank you for applying to Pricesearcher!

As part of your application process we would like you to complete a short
technical challenge to assist in our evaluation of your application.

Your solution, as well as more complex ideas, improvements
and suggestions will be discussed further at interview stage should your
application progress.

## Task

Your task is to write a web crawler that will extract all the URLs from a website so that
they could later be scraped for product data.

Without using a sitemap your application should start at the root of your favourite medium to large e-commerce
website and generate a unique list of all the URLs on the site. Your application should respect
any directives specified in the robots.txt file and make no more than 2 requests per second
to the site.

The output of your application should be a file containing each URL your application found
on its own line. For example:

```
https://www.example.com
https://www.example.com/product/123
https://www.example.com/page/about-us
[...]
```

For context this task is a simplified representation of a similar problem we face where we
crawl thousands of sites and extract product data from them. Some of these sites have sitemaps
that we use as the basis for our product data extraction and for those that don't we generate one.
You should keep in mind when developing your application how effectively it would scale to handle
multiples sites of varying sizes and complexities and be prepared to discuss any limitations in your approach
or ideas for further improvements that could be made at interview stage.

## Implementation

You are free to implement either task using whatever technologies, frameworks, libraries etc you
feel appropriate although as this is a primarily Python focussed role it would be nice to see
that used.

There is no time limit on how long you can spend on the task but around 2 to 3
hours is probably a good guide. As mentioned above any further improvements or
ideas you have can be discussed in the interview.

Your submission will be judged on the overall quality of the solution with
various factors such as the following considered:

- Presentation
- Performance
- Simplicity
- Readability
- Reliability
- Scalability
- Extensibility
- Some other words that end in 'ility'

## Submission

Your work should be submitted as a Git repository. Hosted on a Git hosting website
such as Github/Bitbucket or as a zip archive. If hosted publicly, please don't
mention the interview in the repo or code, unless you feel comfortable making it
public you're interviewing with us.

You should document how to run your submission and if it relies on any
external dependencies, what those are and how to set them up.

For bonus points, include your favourite Gif. This will not affect your
application, unless it is _really_ great.

![good luck](good_luck.gif)

Good luck!
