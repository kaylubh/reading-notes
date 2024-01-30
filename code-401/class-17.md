# Web Scraping

## Notes

- Playwright automates web browsing for testing or scraping
- Beautiful Soup extracts content from a HTML or XML files
- Some websites may actively deter or block scraping

## Reading Questions

1. **What are the key differences between scraping static and dynamic websites?**

    A static website has all the content for a page rendered on load. A dynamic website renders content after a page has loaded.

1. **Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.**

    - Review a websites `robot.txt` file
    - Crawl a page slower
    - Use a headless browser like Playwright

1. **What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.**

    Playwright is a headless browser which automates the rendering and navigation of websites using a browser. It assists in web scraping by providing a browser session which can be automated to handle tasks like clicking on buttons on a page. It would be very useful in scraping content from pages that have buttons to be clicked or forms to be filled in before reaching the content you are trying to scrape on a dynamic page.

1. **Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.**

    Xpath provides a standard syntax to select specific elements from the DOM with a query expression. This is helpful in web scraping to find particular content on a page or specify where to interact with a dynamic webpage when using automation.

## Things I want to know more about

- How to web scrape ethically

## References

- [Scraping Ant: Scrape a Dynamic Website with Python](https://scrapingant.com/blog/scrape-dynamic-website-with-python)
- [Wikipedia: Web scraping](https://en.wikipedia.org/wiki/Web_scraping)
- [ScrapeHero: How to Scrape Websites Without Getting Blocked](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)
- [devhints.io: Xpath cheatsheet](https://devhints.io/xpath)
