# CS305 Project One

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Aretemis Financial is a financial planning institution who needs a security consulting group to sort out their security. We specifically needed to do manual and static testing to determine what vulnerabilities may be present in the code presented.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

Being able to point out and fix vulnerabilities when finding them is key to being a good security researcher. Had they programmed securely from the beginning, some of these vulnerabilities would not have been there to be fixed. Without this security, there is always the possibility of criminals breaking into the system they have and stealing or holding data hostage. This is obviously bad and we should always prioritize security when possible.

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of assessing vulnerabilities like this was definitely the manual review. Having to think outside the box to find vulnerabilities in the code can be difficult, as there are many ways to break code that might not always be obvious.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

While I did not change any of the code directly, pointing out the vulnerabilities for the programmers to change later will definitely increase security. I used both the static testing and manual review to assess vulnerabilities, and I would use both when possible. They both have their own place and niches, and would determine which to use based on the situation.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After every change, I must always check my own code to see if I had introduced a new vulnerability or not. Additionally, after every new dependency added, another static test will be necessary to see if that new dependency added any new vulnerabilities as well.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The Maven dependency Check plugin was incredibly useful to use in future assignments. This along with any similar dependency check programs for other languages and platforms will be key to creating secure code.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

The manual review and mitigation plan are the two portions of this I would show to a future employer. I feel like my work on those sections show off what I've learned and are some of my strongest sections in this project. It shows that I've learned and applied everything I had learned up to this point in the class.
