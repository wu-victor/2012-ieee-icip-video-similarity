# 2012 IEEE ICIP Conference Paper

Efficient Real-time Similarity Detection for Video Caching and Streaming

https://ieeexplore.ieee.org/document/6467343

## Abstract

We present an enterprise-level Internet video cache and streaming system that generalizes “cache hits” to videos that are at least similar, human perception-wise. When a user requests a video not in our cache, our system starts streaming the video from the Internet, and forwards it to the user. We efficiently extract feature vectors from the incoming byte stream, comparing them to feature vectors of cached videos, all in real time. After a short period, we may decide that we have a similar video (but that is not byte-wise identical). We then stop the Internet-side download, and continue streaming to the user using the similar video instead, saving valuable resources. Our system makes similarity decisions with rates of incorrectness approaching zero, after only 30 seconds of Internet-side streaming.
