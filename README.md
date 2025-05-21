# Website Content Monitoring

URLs, XPath / CSS selectors and tools for website content monitoring

## Websites and Elements to Monitor

1. Current default Node.js version on AWS Elastic Beanstalk
   - URL: https://docs.aws.amazon.com/elasticbeanstalk/latest/platforms/platform-history-nodejs.html
   - XPath: `//table//tbody/tr[1]//p[starts-with(normalize-space(), 'Default version:')]`

## Website Content Monitoring Services

1. Wachete (supports XPath selectors) https://www.wachete.com/
2. PageCrawl.io (supports CSS and XPath selectors) https://pagecrawl.io/
