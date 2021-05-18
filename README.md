# covid-tracker-india


[![Run scrapers](https://github.com/simonw/disaster-scrapers/workflows/Run%20scrapers/badge.svg)](https://github.com/simonw/disaster-scrapers/actions?query=workflow%3A%22Run+scrapers%22)


A key goal of this screen scraping mechanism is to allow changes to the underlying data sources to be tracked over time. This is achieved using git, via the GitHub API. Each scraper pulls down data from a source (an API or a website) and reformats that data into a sanitized JSON format. That JSON is then written to the git repository. If the data has changed since the last time the scraper ran, those changes will be captured by git and made available in the commit log.


Inspired by https://github.com/simonw
