# SpringCache
A enhanced version for spring-cache.We Both Know, the spring-cache don't support TL/TTI/Eviction policy/XXX feature during its writers think this feature is not support by all the cache implementations. But,mostly we use the remote cache (like redis or memcached) in our code and this cache implementations all support this feature. So, i write a new spring cache this supports the support TL/TTI/Eviction policy/XXX feature and this springCache's usage and configuration is similar to original spring cache. 
