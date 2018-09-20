# How can good software be recognized?
(Points taken from Ib Havn)

### Designed Well
– High Cohesion
– Loose Coupling
– Independent modules
– Clear Interfaces
– Little Redundancy
– Layered design
– Designed for Test
– Extensible
– Portable

### Maintainable
“What makes the difference between working code and great code is
maintainability” - David Rachamim

“You don’t really know how good someone’s code is until you try to change it” – Kristopher Johnson

– Well documented
– Code is readable – stick to coding and naming standards
– Code is simple – KISS Keep it simple stupid!
– Testable
– Dependency injection
– Encapsulation
– No “gold plating”
– Only optimised if needed
– Automated tests

### It works
“Beautiful readable , testable, maintainable code that fails to meet the
customer needs is still a failure” - codingdave

- As specified by customer
– It solves the intended problems
– Users wants to use it
– It’s stable

## Testing

### Black box testing
– System Tests
– Acceptance Tests
### Test Driven Development (TDD)
### White box testing
– Unit Tests
– ZOMBIES

ZOMBIES Spelled out:
– Z – Zero
– O – One
– M – Many (or More complex)
– B – Boundary Behaviors
– I – Interface definition
– E – Exercise Exceptional behavior
– S – Simple Scenarios, Simple Solutions

http://blog.wingman-sw.com/archives/677#more-677

Use TDD together with ZOMBIES! :)

"Do The Simplest Thing That Could Possible Work." - Kent Beck

# Developing software...

Personally I think the best thing to do is first write down your items/stories and then translate these stories into something that you can write a Behaviour Driven Development test for. It is like adding an extra layer of refinement when you closely couple the business needs to TDD and make sure that TDD is focused on covering the desired specifications.

“As a user-role(1) want a feature(2) that I get business value/benefit(3).”

Items/Stories must never include design ideas –only describe wanted functionality!!

I think code should approach readability and abstraction. I think in any case that something can be descriped as one logical functionality it should be divided so. This will provide seggregation and the next person to read your code will be able to quickly disguish what belongs together and will be able to read on a more abstract level about what you are trying to do.
