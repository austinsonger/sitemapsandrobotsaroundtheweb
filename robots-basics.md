# Robots.txt Basics


| Definitions |                                                              |
| :---------- | ------------------------------------------------------------ |
| Crawler     | A crawler is a service or agent that crawls websites. Generally speaking, a crawler automatically and recursively accesses known URLs of a host that exposes content which can be accessed with standard web-browsers. As new URLs are found (through various means, such as from links on existing, crawled pages or from Sitemap files), these are also crawled in the same way. |
| User-agent  | A means of identifying a specific crawler or set of crawlers. |
| Directives  | The list of applicable guidelines for a crawler or group of crawlers set forth in the robots.txt file. |
| URL         | Uniform Resource Locators as defined in [RFC 1738](http://www.ietf.org/rfc/rfc1738.txt). |
|             |                                                              |



## Applicability

The guidelines set forth in this document are followed by all automated crawlers at Google. When an agent accesses URLs on behalf of a user (for example, for translation, manually subscribed feeds, malware analysis), these guidelines do not need to apply.

## File location and range of validity

The robots.txt file must be in the top-level directory of the host, accessible through the appropriate protocol and port number. Generally accepted protocols for robots.txt are all [URI-based](https://en.wikipedia.org/wiki/Uniform_Resource_Identifier), and for Google Search specifically (for example, crawling of websites) are "http" and "https". On http and https, the robots.txt file is fetched using a HTTP non-conditional GET request.

Google-specific: Google also accepts and follows robots.txt files for FTP sites. FTP-based robots.txt files are accessed via the FTP protocol, using an anonymous login.

The directives listed in the robots.txt file apply only to the host, protocol and port number where the file is hosted.





















### Good Resources

- [Robots.txt Generator](https://en.ryte.com/free-tools/robots-txt-generator/)
