# What Is Code Quality? And How to Improve Code Quality ?
Code quality defines code that is good (high quality) — and code that is bad (low quality).

This — quality, good, bad — is all subjective. Different teams may use different definitions, based on context. Code that is considered high quality may mean one thing for an automotive developer. And it may mean another for a web application developer.

For that reason, we explain what is code quality, how to improve code quality, and how code quality tools can help.

## Why Code Quality Matters
The code quality is important, as it impacts the overall software quality. And quality impacts how safe, secure, and reliable your codebase is.

High quality is critical for many development teams today. And it's especially important for those developing safety-critical systems.

## Learn How Code Quality Impacts Software Quality

#### Code Quality Analysis: Good Code vs. Bad Code
Good code is high quality. And it’s clean code. It stands the test of time. Bad code is low quality. It won’t last long.

Essentially, code that is considered good:

Does what it should.
Follows a consistent style.
It is easy to understand.
Has been well-documented.
It can be tested.

### Testing Isn’t Enough
Programmers aren’t perfect. Manual code reviews and testing will never find every error in the code.

A study on “Software Defect Origins and Removal Methods” found that individual programmers are less than 50% efficient at finding bugs in their own software.  And most forms of testing are only 35% efficient. This makes it difficult to determine quality.

### Coding Errors Lead to Risk
The quality of code in programming is important. When code is low quality, it might introduce safety or security risks. If software fails — due to a security violation or safety flaw — the results can be catastrophic or fatal.

### Quality Is Everyone’s Responsibility
Quality is everyone’s job. The developer. The tester. The manager. High quality should be the goal throughout the development process.

## How to Measure Code Quality?
There’s no one way to measure the quality of your code. What you measure may be different from what other development team measures.

### Key Code Quality Aspects to Measure
Here are five of the key traits to measure for higher quality.

#### Reliability
Reliability measures the probability that a system will run without failure over a specific period of operation. It relates to the number of defects and availability of the software.

Number of defects can be measured by running a static analysis tool. Software availability can be measured using the mean time between failures (MTBF). Low defect counts are especially important for developing a reliable codebase.

#### Maintainability
Maintainability measures how easily software can be maintained. It relates to the size, consistency, structure, and complexity of the codebase. And ensuring maintainable source code relies on a number of factors, such as testability and understandability.

You can’t use a single metric to ensure maintainability. Some metrics you may consider to improve maintainability are the number of stylistic warnings and Halstead complexity measures. Both automation and human reviewers are essential for developing maintainable codebases.

#### Testability
Testability measures how well the software supports testing efforts. It relies on how well you can control, observe, isolate, and automate testing, among other factors.

Testability can be measured based on how many test cases you need to find potential faults in the system. Size and complexity of the software can impact testability. So, applying methods at the code level — such as cyclomatic complexity — can help you improve the testability of the component.

#### Portability
Portability measures how usable the same software is in different environments. It relates to platform independency.

There isn’t a specific measure of portability. But there are several ways you can ensure portable code. It’s important to regularly test code on different platforms, rather than waiting until the end of development. It’s also a good idea to set your compiler warning levels as high as possible — and use at least two compilers. Enforcing a coding standard also helps with portability.

#### Reusability
Reusability measures whether existing assets — such as code — can be used again. Assets are more easily reused if they have characteristics such as modularity or loose coupling.

Reusability can be measured by the number of interdependencies. Running a static analyzer can help you identify these interdependencies.

Which Code Quality Metrics to Use
There are several metrics you can use to quantify the quality of your code.

### Defect Metrics
The number of defects — and severity of those defects — are important metrics of overall quality.

This includes:

Identification of the stage in which the defect originates.
Number of open defect reports.
Time to identify and correct defects.
Defect density (e.g., number of defects per lines of code).
Complexity Metrics
Complexity metrics can help in measuring quality.

Cyclomatic complexity measures of the number of linearly independent paths through a program’s source code.

Another way to understand quality is by calculating Halstead complexity measures. These measure:

Program vocabulary
Program length
Calculated program length
Volume
Difficulty
Effort


#### How to Improve Code Quality
Measuring quality helps you understand where you’re at. After you’ve measured, you can take steps to improve overall quality.

Here are four ways you can improve the quality of your code:

1. Use a coding standard.

2. Analyze code — before code reviews.

3. Follow code review best practices.

4. Refactor legacy code (when necessary)

How to Improve Code Quality: A Closer Look
1. Use a Coding Standard
Using a coding standard is one of the best ways to ensure high quality code.

A coding standard makes sure everyone uses the right style. It improves consistency and readability of the codebase. This is key for lower complexity and higher quality.

#### How to Do It
The best way to use a coding standard is to:

Train your developers
Help them to comply with it
You can do this by using a static code analyzer.

2. Analyze Code — Before Code Reviews
Quality should be a priority from the very start of development. There isn’t always the luxury of time as development progresses. That’s why it’s important to analyze code before code reviews begin. And it’s best to analyze code as soon as it’s written.

In DevOps, code analysis takes place during the create phase. Static analyzers can be run over code as soon as it’s written. This creates an automated feedback loop, so developers can improve code before it goes to the code review phase.

After all, the earlier you find errors, the faster, easier, and cheaper they are to resolve.

#### How to Do It
The best way to improve quality is by analyzing code automatically. By running a static analyzer over code early and often, you’ll make sure the code that gets to the code review phase is the highest quality possible. Plus, you can use static analyzers (such as Helix QAC and Klocwork) to monitor key quality metrics.

3. Follow Code Review Best Practices
Manual code reviews are still important for verifying the intent of the code. When code reviews are done well, they improve overall software quality.

#### How to Do It
The best way to do code reviews is to follow best practices and take advantage of automated tools. 

4. Refactor Legacy Code (When Necessary)
One way to improve the quality of an existing codebase is through refactoring. Refactoring legacy code can help you clean up your codebase and lower its complexity.

#### How to Do It
The best way to improve a legacy codebase is to do it gradually. Here are eight tips for improving legacy code (without compromising your software). 

#### Get Started With Code Quality Analysis
Analyzing and measuring quality can be tricky, as quality can be subjective. You can use some metrics to objectively evaluate code, including cyclomatic complexity. And there are several ways you can lower complexity and improve quality.

Quality coding might take more time and effort on the first pass. But by introducing quality early on, you’ll lower the cost of maintenance and bug fixes in the long-term. And you’ll reduce your technical debt.

#### Choosing the Right Code Quality Tools
Using the right code quality tools, including static analyzers, is key. 

Static analyzers — such as Helix QAC and Klocwork — make it easy to ensure that your code is high quality. You'll improve quality by:

Applying coding standards.
Analyzing code automatically.
Following coding best practices.
Refactoring legacy code.
Plus, you'll be able to monitor the quality of your codebase over time, using metrics like cyclomatic complexity. 
