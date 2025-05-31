## Clip: 01:13 - 03:10

Hey everybody, And welcome back to the episode, adventures in angular. This week, on the panel, we have Subra nishrah, hello, we also have Sunny youssef, it's me again. devchat.tv I don't have my own jingle.
Today, we have a special guest he can Micheal Vladky, hey hey how's it going?,I say your name is wrong. I don't know even myself. So it's good. Don't worry, Charles say everybody's name wrong. I do I just make it up as I go. Story my life. We got you on. Why don't you fist just remind people who you're before jumping...
My name is Micheal V... I am a trainer and consultant. I have a small company with high expertise in Angular and reactive programming with a lot of performance or audits. This is a framework and technology. basically run a lot of performance audit on shops and other stuff that really need that. And on top of that pretty last, I guess coming up two years. I have a lot of focus in particular, in Angular.

## Clip: 03:10 - 05:10

I do just want to give us kind of high level view on what push pipe is and how would we change detection on ... and the stuff like that. or the blog.
We can do that. I would tick also the whole conversation what this is in angular way, change detection. We will instantly throwing to pathways to pull and push based on architecture. With knowledge that tool in mind, let's get started and let's discuss how angular change detection is running by pull based .
I try to break it down.. and interrupt...
triggering and every rendering on Angular. This is maybe the stuff some people may know.
We have application ref or application ref services. These services are connected to the root component, the root component, most upper componet of component maintain and contains the whole application ... call.. run not run you tick the change detection on whole app
everything will leave in child component if there's a change or not. So in Angular, we can run change detection in two different ways. You can say my change detection is a default way of doing that.
Whenever your whole application has the default change detection, it will rerender everything, it will rerender all components that leaves, lists no change.
