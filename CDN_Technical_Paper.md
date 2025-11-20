# Content Delivery Networks (CDNs)

## Introduction

A Content Delivery Network (CDN) is a globally distributed network of servers that improves the speed and efficiency of delivering digital content to users. Instead of depending on a single origin server, a CDN stores cached versions of files such as web pages, scripts, images, and videos across multiple edge servers located in different regions. When a user accesses content, the CDN selects the nearest server, which reduces latency and speeds up loading. CDNs are widely used in modern web applications to manage heavy traffic, ensure faster performance, increase reliability, and enhance security. They help businesses scale globally by making websites and apps accessible quickly from different parts of the world.

![CDN] (/home/balajyothi/CDN.webp)

## How CDNs Work
1. A user requests a file such as an image, CSS file, or video.

2. The CDN routes the request to the closest edge server based on the user’s location.

3. If the requested file is already cached in the edge server, it is delivered immediately.

4. If the file is not cached, the CDN fetches it from the origin server, sends it to the user, and stores a copy for future requests.

5. The CDN continually updates cached content based on rules set by the website or application.

## Benefits of CDNs

* Faster content delivery regardless of the user’s geographic location

* Reduced load on the origin server due to caching

* Better handling of sudden traffic spikes without downtime

* Higher website and application availability

* Improved performance for large media content such as HD videos and images

* Enhanced security features such as DDoS protection, traffic filtering, and secure data transfer

* Lower overall network congestion and bandwidth cost

## Common Use Cases

* Video and audio streaming services

* E-commerce websites with global customer bases

* Image optimization and delivery for media-heavy platforms

* Software downloads, updates, and patches

* Static asset delivery such as HTML, CSS, images, and JavaScript

* API response caching for faster app performance

## Popular CDN Providers

* Cloudflare

* Akamai

* Amazon CloudFront

* Google Cloud CDN

* Fastly

## References

https://www.cloudflare.com/learning/cdn/what-is-a-cdn

https://www.youtube.com/watch?v=RI9np1LWzqw

https://www.geeksforgeeks.org/system-design/what-is-content-delivery-networkcdn-in-system-design/
