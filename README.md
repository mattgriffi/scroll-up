This is a tiny (13 line) program. It will send a scroll-up event to the focused window every 0.6 seconds.

A friend of mine wanted a copy of our chat logs. Unfortunately, the chat client that we use to communicate does not make these logs readily available, and the only way to see past messages is to scroll up, which triggers the client to load more past messages. It takes approximately 0.6 seconds to load more messages, hence the wait. Getting the entirety of our chat logs would take several hours of scrolling, which I will not be doing by hand.

## Requirements ##

pyautogui