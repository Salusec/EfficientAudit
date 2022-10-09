# What you need to know before auditing


1. Record all contents belonging to the contract public API. Even private/internal sensitive functions should be recorded.

2. Learn the development of some large contract projects. Not only do you need to read their code, but you also need to understand how they test, deploy, and upgrade.

3. The premise of contract optimization is correctness and security. Complex optimization operations often lead to vulnerabilities

4. Name your functions and systems succinctly. You are not fighting alone, which will greatly help others understand your code.

5. Clean up old comments, unused functions, etc. Keep your code clean. Because this will make us very confused in the audit process.

6. You can save countless key vulnerabilities through simple unit testing. In addition, tests let us know the expected behavior. If no public function is called in the test, that is where we aim.

7. Auditing a constantly changing project will bring us great difficulties, because we need to repeatedly read all the code to re-establish the project model. Therefore, it is better to have a locked version when you submit an audit.

8. Don't make wheels yourself. It is 2022. You should not write your ERC20 from scratch. The same applies to other ERCs, governance, access control, etc. Use a known security library. More security, smaller audit scope, you will save money.

9. When you submit the audit, please ensure that the project is compiled and passed the test. This is a basic requirement. The first thing we do before auditing is to build and run tests. When it failed, it was too disappointing.


# We need smooth communication during audit.
We will have many things we don't understand, and we need your help. We will have a dedicated pre-sales engineer to communicate with you. We may need to:

(1) Code document

Don't assume that we will know your code, or that we have understood the algorithm/data structure you are writing. We need documentation and time to understand it. Therefore, a large number of documents are ready for us to start mining on the first day.

(2) Notes/Instructions

You can't imagine saving auditors countless hours simply by stating how you intend to deal with crazy, obscure low-level compilation math that multiplies two numbers. Describe your technology roadmap and future development plan as much as possible. This helps us understand the project you are building and the expansion risks you will face in the future, as well as what attacks your project is more likely to suffer.

(3) Code walkthrough

Especially at the beginning of the audit, we need to know what you showed? What do you emphasize?


Finally, smart contract audit/penetration testing is a security oriented adversarial way of thinking for best effort code review. With this in mind, do not assume that we will always find every vulnerability, and once the audit is completed, your code is perfect. Even after our report you managed to solve all the problems. It means that security incidents may still occur after the audit. So you need to assume that you can be hacked, buy insurance, set up contract monitoring facilities, buffers, and make recovery plans.

Do not place all hopes of ensuring safety on audit! Instead, let's keep communicating and build trust, so we can help you in the long run.
