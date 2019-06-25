# [channel_lock](https://github.com/aaruel/channel_lock)

##### Role: Creator

---

`channel_lock` is an Elixir library that makes it possible to create multiple keyable "channels" to feed tasks through. Each channel is asynchronous to each other, but the channel itself acts as a synchronous FIFO queue, executing each task at the front of the queue, then the next when finished, etc.
