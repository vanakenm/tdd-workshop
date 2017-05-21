## TDD

Image from Meetup

---

## Why test?

---

## Why automate tests?

* Laziness
* Writing tests is funnier than running them
* Consistency
* Avoid side effects
* Productivity

---

## Why automate tests?

Most of the time, the new feature you are working on will work...
... it will break something else

---

## Also...

It put you directly in the shoes of the person using the code, instead of writing it.

---

## Some definitions

---

### Unit tests vs Integration tests

---

### TDD vs Test First

---

### TDD vs BDD

---

## Principle

Use known input and output value to validate that the code is doing what it should.

* Initial values
* Method under test
* Assertion!

---

## Unit Test 101

---

### Simple start

* Expect (good) results
* "Happy case"

---

### Expecting the unexpected

* Expect an exception
* People make mistakes

---

### Errors vs Failures

---

### Assertions

No assertions means your test is:

"Does this code fail in a spectacular way" - not a really interesting question

---

## A bigger example

Devise - the kind of software we depend on

git@github.com:plataformatec/devise.git
17sec for 2171 assertion

---

## Lifecycle

---

### A "simple" chart

From https://twitter.com/sarahmei/status/635132440827158528 @sarahmei
https://pbs.twimg.com/media/CNBxluNU8AAFQJR.png

---

### TDD

* Write the test
* Run (it fails!)
* Write the minimal amount of code needed to make the test green
* Repeat

---

### Why?

* Force you to think about how to use your code
* Prevent you to write any code you don't need

---

### "Red, Green, Refactor"

http://imgur.com/acmyARH

---

### Test as bug fixing

---

## Let's get practical

LIVE CODE TIME!

---

## Some confessions

* I don't aim for 100% test coverage
* Most of my prototypes are untested

---

## From the trenches

* Manual (scripted!) testing can be very efficient
* Test costs - creation & maintenance
* UI are notoriously hard to test (ex: change a button "exit" to a menu - the user is fine, the test is broken)
  - remember, the user is drunk (well that's UX, but anyway)

---

## Tests in the way

If you want to have & maintain tests:

* They should break the build
* They should run fast
- Tests should be part of the review (we reject PR without tests)

It's still a team effort & decision - make it part of your "DoD"

---

## Final words

As a small story, the last colleague coming in decided to start adding tests - http://www.codingconfessional.com/comments/rmcCFmS7begkRN59Olwn6w

---

## A first step

* A single test is better than no test
* Start where it hurts:
  - code that change a lot
  - code that breaks a lot
  - code easy to test
  - last bug

---

## About me

I'm Martin, I've been creating bugs in HealthCare to Finance & in one person company to multinationals since 15 years
I'm a coach at LeWagon
I'm currently CTO at BLSQ - BTW we're hiring a product owner right now

---

# THANKS!
