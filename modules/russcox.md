<!--
{
"name" : "russcox",
"version" : "0.1",
"title" : "Go, Open Source, Community",
"description" : "How I see the Go project as a whole and how I see the Go open source project evolving",
"homepage" : "http://blog.golang.org/open-source",
"canonicalSource" : "http://blog.golang.org/open-source",
"freshnessDate" : 2015-07-08,
"license" : "CC BY 3.0"
}
-->

<!-- @section -->

## Welcome

<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/embed/cPSfA1bhgVA?end=50" -->

Thank you all for traveling to Denver to be here, and thank you to everyone watching on video. If this is your first Gophercon, welcome. If you were here last year, welcome back. Thank you to the organizers for all the work it takes to make a conference like this happen. I am thrilled to be here and to be able to talk to all of you.

I am the tech lead for the Go project and the Go team at Google. I share that role with Rob Pike. In that role, I spend a lot of time thinking about the overall Go open source project, in particular the way it runs, what it means to be open source, and the interaction between contributors inside and outside Google. Today I want to share with you how I see the Go project as a whole and then based on that explain how I see the Go open source project evolving.

<!-- @section -->

## Why Go?

<!-- @asset, "contentType": "outlearn/video", "provider": "youtube", "url": "https://www.youtube.com/embed/cPSfA1bhgVA?start=50&end=204" -->

To get started, we have to go back to the beginning. Why did we start working on Go?

Go is an attempt to make programmers more productive. We wanted to improve the software development process at Google, but the problems Google has are not unique to Google.

There were two overarching goals.

The first goal is to make a better language to meet the challenges of scalable concurrency. By scalable concurrency I mean software that deals with many concerns simultaneously, such as coordinating a thousand back end servers by sending network traffic back and forth.

Today, that kind of software has a shorter name: we call it cloud software. It's fair to say that Go was designed for the cloud before clouds ran software.

The larger goal is to make a better environment to meet the challenges of scalable software development, software worked on and used by many people, with limited coordination between them, and maintained for years. At Google we have thousands of engineers writing and sharing their code with each other, trying to get their work done, reusing the work of others as much as possible, and working in a code base with a history dating back over ten years. Engineers often work on or at least look at code originally written by someone else, or that they wrote years ago, which often amounts to the same thing.

That situation inside Google has a lot in common with large scale, modern open source development as practiced on sites like GitHub. Because of this, Go is a great fit for open source projects, helping them accept and manage contributions from a large community over a long period of time.

I believe much of Go's success is explained by the fact that Go is a great fit for cloud software, Go is a great fit for open source projects, and, serendipitously, both of those are growing in popularity and importance in the software industry.

Other people have made similar observations. Here are two. Last year, on RedMonk.com, Donnie Berkholz wrote about “Go as the emerging language of cloud infrastructure,” observing that “[Go's] marquee projects ... are cloud-centric or otherwise made for dealing with distributed systems or transient environments.”

This year, on Texlution.com, the author wrote an article titled “Why Golang is doomed to succeed,” pointing out that this focus on large-scale development was possibly even better suited to open source than to Google itself: “This open source fitness is why I think you are about to see more and more Go around ...”
