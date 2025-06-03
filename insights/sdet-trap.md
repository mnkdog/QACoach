# The SDET trap: Why separating test automation from development might be slowing you down


A common pattern I've observed: organisations creating separate SDET roles solely to write automated tests for code the developers wrote.


While well-intentioned, this approach creates several problems:
- Knowledge handoffs that slow down delivery
- Another quality silo rather than shared ownership
- Test code that's often less maintainable than production code
- Developers designing code without testability in mind
- Delayed feedback on quality issues

The more effective model I've seen embraces "you write it, you test it, you support it" where:
- Developers write tests for their own code
- QA professionals serve as coaches on testing strategy and risk analysis
- Test infrastructure and frameworks enable developer testing
- Quality becomes a shared responsibility from day one
- Feedback loops tighten dramatically

The business benefits? Faster delivery, more maintainable test suites, and developers who think about quality from the start rather than considering it "someone else's job."

SDETs can still have a critical role - building the test infrastructure and frameworks that make developer testing efficient, not taking over the testing itself.

Has your organisation fallen into the SDET trap?