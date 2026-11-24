# Traffic-Coordinator
Ever sat in traffic and wondered why it suddenly clears up for no reason?  Most of the time it's one stretch of road that can't handle what's being pushed into it. That's the idea behind our Urban Traffic Signal Coordinator.
Here's what it does, in simple terms:

🛣️ You give it a map of roads and how many vehicles each one can handle.
🔍 It works out how much traffic the whole network can really carry.
🚦 It points to the exact roads holding everything back.
🗣️ Then it explains the fix in plain English, like "give Road X more green time," so a traffic officer can act on it without needing to know any maths.

Behind the scenes it uses a classic algorithm called Maximum Flow. But the goal was never to show off the algorithm. It was to answer a question every city faces every day: where does adding capacity actually help?

It isn't perfect. It looks at vehicles moved, not how long each person waits, and it works with fixed road capacities rather than live traffic. Real-time sensor data and a live map are the next steps we'd love to try.
