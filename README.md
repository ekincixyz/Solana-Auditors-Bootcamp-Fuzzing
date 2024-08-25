![Solana Auditors Bootcamp](https://github.com/Solana-Auditors-Bootcamp/.github/blob/main/.banner/Solana%20Auditors%20Bootcamp.png?raw=true)

# Fuzzing with Trident

This is your Task 1 in the Solana Auditors Bootcamp.During the Lesson 3 in the Bootcamp you were introduced into Fuzzing with Trident. The goal of this week's task is to familiarize you with fuzz testing of Solana programs written using the Anchor Framework.

## Task details

This week's task involves writing fuzz tests for an open-source Solana project using the Trident Fuzz Testing Framework. Fuzz testing is a technique where you automatically generate a wide range of random inputs to test your program and catch edge cases or potential security vulnerabilities that might not be covered by typical unit or integration tests.

**The details:**
1. **Select a Project:** Choose an open-source Solana project on which you want to perform fuzz testing. This could be a project you're familiar with or any public project available on GitHub.

2. **Integrate Trident:** Set up the Trident framework within the chosen project. This involves initializing Trident and configuring it appropriately.

3. **Identify Critical Functions:** Identify key functions or processes within the Solana program that are critical to its operation. These are the functions where fuzz testing will be most beneficial.

4. **Write Fuzz Tests:** Implement fuzz tests for the identified functions. The goal is to generate a variety of random inputs to test the program's response to unexpected, invalid, or even valid inputs.

5. **Run and Analyze:** Run the fuzz tests using Trident, and analyze the results. Identify any crashes, panics, or unexpected behaviors that indicate vulnerabilities or bugs.

6. **Document Your Findings:** Provide a report detailing the fuzz testing process, for example in form of short README.md and the project you were fuzzing, it is also important to include the CrashFile/s if any!

## Submission Process

> [!important]
> Within the `project-fuzzing` folder include the project you were fuzzing with the short README.md detailing the found crashes or anything you think is important. Do not forget to also inlcude the Fuzz Tests within the folder!

## Deadline

# TBD

The deadline for this task is Wednesday, May 15th, at 23:59 UTC.


## Hints and Useful Links

- [Lesson 3 Materials](https://github.com/Ackee-Blockchain/Solana-Auditors-Bootcamp/tree/master/Lesson-3)
- [Trident Documentation](https://ackee.xyz/trident/docs/latest/)
- [Trident Examples](https://ackee.xyz/trident/docs/latest/fuzzing/extra/examples/)
- [Youtube Lesson](https://youtu.be/5JRVnxGW8kc?si=bx3dnq7kGQV7_uYk)


-----

### Need help?
If you have any questions feel free to reach out to us at [Discord](https://discord.gg/z3JVuZyFnp).
