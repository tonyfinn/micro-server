# REST client plugin for Microserver

This plugin provides two REST Clients

1. NIORestClient - which is a non-blocking REST client using NIO
2. AsyncRestClient - which is asyncrhonous, but makes use of threads

The NIORestClient is available as  Spring bean. AsyncRestClient can simply be instantiated via the new keyword.