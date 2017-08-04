# ReactiveUI

ReactiveUI is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming which is a paradigm that allows you to express the idea around a feature in one readable place, abstract mutable state away from your user interfaces and improve improve the testability of your application.

It is the father of the extremely popular <a href="https://github.com/ReactiveCocoa/">ReactiveCocoa</a> framework. Internally the maintainers debate whether ReactiveUI is or is not a framework, as at its core the project is essentially a bunch of extension methods for the <a href="https://dotnetfoundation.org/reactive-extensions-for-net">Reactive Extensions</a>.

We believe that code is communication between people, that also happens to run on a computer. If you optimise for humans, then over a long time your project will end up better. Software should be understandable by other people; that is super important. We believe that only <a href="https://www.youtube.com/watch?v=5DZ8nC0ENdg" target="_blank">the power of the Reactive Extensions allows you to express the idea around a feature in one readable place</a>.

Let’s say you have a text field, and whenever the user types something into it, you want to make a network request which searches for that query. Your designer has requested that this search query automatically execute as the user is typing but your operation team wants guarantees that only one network request is ever in transit and no more frequently than roughly once per second whilst the user is typing.</p>

<img src="https://reactiveui.net/docs/search-autocomplete.gif" />

## How would you usually implement this?

Most modern programming today is basically imperative, meaning it models the traditional fetch-execute cycle of a CPU. Perform an instruction, fetch the next one. Perform that one, and so on. For decades, programmers have had to mould their brains to fit the paradigm of the CPU. It's been like this since the early 1980s.

When we rely on hoping that the behavior that emerges from a program is correct, and that reliance is based on nothing more than a programmer's correctness, then we can easily find ourselves in a sticky situation. We can try and mitigate the costs of imperative programming with things like unit tests or integration tests, but why mitigate the costs when there's a better way?

## There is a better way

Long ago, when computer programming first came to be, machines had to be programmed quite manually. If the technician entered the correct sequence of machine codes in the correct order, then the resulting program behavior would satisfy the business requirements.  Instead of telling a computer how to do its job, which error-prone and relies too heavily on the infallibility of the programmer, why don't we just tell it what it's job is and let it figure the rest out?

ReactiveUI is inspired by the paradigm of Functional Reactive Programming, which allows you to model user input as a function that changes over time. This is super cool because it allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place whilst improving application testability. Reactive programming can look scary and complex at first glance, but the best way to describe reactive programming is to think of a spreadsheet:

<img src="https://reactiveui.net/docs/frp-excel.gif" />


<ul>
    <li>Three cells, A, B, and C.</li>
    <li>C is defined as the sum of A and B.</li>
    <li>Whenever A or B changes, C reacts to update itself.</li>
</ul>

<p>That's reactive programming: changes propagate throughout a system automatically. Welcome to the peanut butter and jelly of programming paradigms.</p>

<iframe width="100%" height="480" src="https://www.youtube.com/embed/DYEbUF4xs1Q" frameborder="0" allowfullscreen></iframe>

# Project Details

* [Website](https://www.reactiveui.net)
* [Source](https://github.com/reactiveui/reactiveui)
* License: [MS-PL](https://github.com/reactiveui/reactiveui/blob/master/LICENSE)
* [NuGet](https://www.nuget.org/packages/reactiveui)
* [Project Leads](https://github.com/reactiveui/reactiveui/#core-team)

# Quicklinks

* [Slack](https://reactiveui.net/slack)
* [Meetup](https://reactiveui.net/meetup)
* [Contribute](https://reactiveui.net/contribute)
* [Documentation](https://reactiveui.net/docs)
* [StackOverflow](https://reactiveui.net/stack-overflow)