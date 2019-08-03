# Awesome AWS S3 - Security, Tools and Intel

Collection of tools, techniques and useful links concerning security and exposed AWS S3 Buckets

# Tools

* [Grayhat Warfare](http://buckets.grayhatwarfare.com/) - A free tool that lists open s3 buckets and helps you search for interesting files
* [Slurp](https://github.com/hehnope/slurp) - Evaluate the security of S3 buckets
* [AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) - AWSBucketDump is a tool to quickly enumerate AWS S3 buckets to look for loot
* [S3Scanner](https://github.com/sa7mon/S3Scanner) - Scan for open AWS S3 buckets and dump the contents - By sa7mon
* [s3enum](https://github.com/koenrh/s3enum) - Fast Amazon S3 bucket enumeration tool for pentesters
* [s3-buckets-finder](https://github.com/gwen001/s3-buckets-finder) - PHP tool to brute force Amazon S3 bucket - By gwen001
* [s3-buckets-finder](https://github.com/gold1029/s3-buckets-finder)  - PHP tool to brute force Amazon S3 bucket - By gold1029
* [Sandcastle](https://github.com/0xSearches/sandcastle) - a Python script for AWS S3 bucket enumeration, formerly known as bucketCrawler
* [mubrute](https://github.com/GeneralTesler/mubrute) - The tool uses the response code returned by s3.amazonaws.com to determine if a bucket exists and its list permissions
* [PyLazyS3](https://github.com/Den1al/PyLazyS3) - Enumerate AWS S3 buckets using different permutations
* [RoboBucketeer](https://github.com/we45/RoboBucketeer) - Robot Framework Library for Buckteer - S3 Buckets & Subdomain Enumeration
* [s3-inspector](https://github.com/kromtech/s3-inspector) - Tool to check AWS S3 bucket permissions
* [inSp3ctor](https://github.com/brianwarehime/inSp3ctor) - AWS S3 Bucket/Object Finder
* [bucketkicker](https://github.com/craighays/bucketkicker) - A tool to quickly enumerate AWS S3 buckets verify whether or not they exist and to look for loot
* [s3recon](https://github.com/clarketm/s3recon) - Amazon S3 bucket finder and crawler
* [s3finder](https://github.com/magisterquis/s3finder) - Can search using a wordlist or by monitoring the certstream network for domain names from certificate transparency logs
* [kicks3](https://github.com/abuvanth/kicks3) - S3 bucket finder from html,js and bucket misconfiguration testing tool
* [bucket_finder]https://github.com/mattweidner/bucket_finder) - DigiNinja's bucket_finder utility - By mattweidner
* [Bucket_Finder](https://github.com/hazana/Bucket_Finder) - Leaky Buckets - By hazana
* [haka_toni_bucket_finder](https://github.com/jjvmak/haka_toni_bucket_finder) - Yet another S3 Bucket finder (_No official description provided_)
* [s3-open-bucket-finder](https://github.com/siddharth2395/s3-open-bucket-finder) - Yet another S3 Bucket finder (_No official description provided_)
* [s3scanner](https://github.com/miguelmota/s3scanner) - Scan for open public S3 buckets - By miguelmota
* [bucket-scraper](https://github.com/Rorkien/bucket-scraper) - Command-line application for scraping, indexing and downloading of Amazon S3 buckets
* [bucket-hunter](https://github.com/samuelcardillo/bucket-hunter) - Amazon AWS Exposed Bucket Hunter - Security research
* [bucket-stream](https://github.com/eth0izzle/bucket-stream) - Find interesting Amazon S3 Buckets by watching certificate transparency logs
* [goGetBucket](https://github.com/glen-mac/goGetBucket) - A penetration testing tool to enumerate and analyse Amazon S3 Buckets owned by a domain
* [bucket_finder](https://github.com/FishermansEnemy/bucket_finder) - Trawl Amazon S3 buckets for interesting files

# General Purpose Tools

* [CloudScraper](https://github.com/jordanpotti/CloudScraper) - CloudScraper: Tool to enumerate targets in search of cloud resources. S3 Buckets, Azure Blobs, Digital Ocean Storage Space
* [CloudStorageFinder](https://github.com/digininja/CloudStorageFinder) - A collection of tools to find data that has been made public in cloud storage systems such as S3 Buckets and Digital Ocean Spaces
* [exif-scraper](https://github.com/downpat/exif-scraper) - Grab photos from an S3 bucket and store their EXIF data in a database
* [mlb-dfs-scrapers](https://github.com/kykosic/mlb-dfs-scrapers) - Web scraping library for dumping MLB stats in S3 bucket csv files

# Techniques

* [enum_wayback](https://github.com/mubix/stuff/blob/master/metasploit/enum_wayback.rb) - Metasploit module that pulls and parses the URLs stored by Archive.org for the purpose of replaying during a web assessment. Finding unlinked and old pages.

# Articles

* [List of AWS S3 Leaks](https://github.com/nagwww/s3-leaks)
* [How to search for Open Amazon s3 Buckets and their contents](https://medium.com/@grayhatwarfare/how-to-search-for-open-amazon-s3-buckets-and-their-contents-https-buckets-grayhatwarfare-com-577b7b437e01)
* [There's a Hole in 1,951 Amazon S3 Buckets](https://blog.rapid7.com/2013/03/27/open-s3-buckets/)
* [Amazon S3 Bucket Public Access Considerations](https://aws.amazon.com/pt/articles/amazon-s3-bucket-public-access-considerations/)
* [Analysing Amazon's Buckets](https://digi.ninja/blog/analysing_amazons_buckets.php)
* [Unsecured Public Information in Amazon S3 Buckets - Are Your Buckets Leaking Data?](https://www.rapid7.com/resources/amazon-s3-bucket-misconfiguration/)
* [Exposed S3 bucket CloudTrail logs — Another way to compromise security](https://www.cloudmanagementinsider.com/exposed-s3-bucket-cloudtrail-logs/)
* [Fantastic! Public S3 Buckets and How to Find Them](https://auth0.com/blog/fantastic-public-s3-buckets-and-how-to-find-them/)

# Videos

* [How do I find out which S3 buckets allow access from the Internet?](https://www.youtube.com/watch?v=xHK_A_lscoA)
* [Securing and Protecting Against Exposed S3 Buckets](https://youtu.be/UIN-je82K3A)
* [Effective S3 Bucket Management to Prevent and Mitigate Data Exposure](https://youtu.be/4tp3pOeKefc)
* [The Bucket List: Experiences Operating S3 Honeypots](https://youtu.be/k7-wCcS2HFU)
