<img src="./static/drover-logo.svg" width="200">

# Test Automation

Drover is a VC-backed, growth-stage marketplace company offering monthly, all-in car subscriptions to customers who want to experience car ownership as it should be: digital, flexible and at a fair, transparent price. For some more detail, check out our press coverage in TechCrunch, Forbes or CityAM.

We want to build ever more extraordinary digital experiences for our users and we need your help: come on board and join our 20-strong engineering team spread across London and Lisbon busy changing the automotive landscape.

## Assignment
### What You Should Know

This is the website we are going test against: https://staging-fe.drover-test.com/

This is our "pre-production" environment and before we ship anything to production we do extensive testing on this environment. Currently, we only operate inside of UK so during the your tests, make sure you are using a UK phone number and postcode.

### The Use Case

Drover's most important flow is the "Booking" flow. So you want to make sure that at least the basic flow is working properly.

#### Step-by-step
* Visit the Drover's (staging environment) home page.
* Click on the blue button "Find your car".
* Pick a car.
* On the checkout page, click on the blue button "Continue".
* Sign up.
* Click "Next" on Subscription length.
* Click "Next" on Additional options. Select to use your own insurance.
* Select a date & time you would like the care to be delivered.
* Click on the blue button "Continue".
* Fill your insurance history.
* We will ask you for your driver license data. You can use any number (E.g MORGA657054SM9IJ) and for the picture, use any file on your computer and click on "Continue".
* Based on the data your on the step before, you might see a warning saying that you won't be able to use Drover's ensurance and you need to use your own, just proceed.
* For Payment informationm use this test UK creditcard `4000 0082 6000 0000`. Everything else you can fill with anything as long as it is "valid".
* If you get to the page "Please complete your Credit Kudos affordability check" that's it. :)

## What Do We Expect From You?

* As you noticed, during the `step-by-step` flow we didn't mentioned any validation checks. You will be the judge of what you think it's important to check during the user flow.
* You can use the technology you think it's going to be the best. At Drover we have CI/CD in place so during the process of deciding the right technologies to automate this use case keep that in mind.
* Your test suite is expected to grow over time and also to be maintained by others so overall organization and documentation is highly appreacited.

------

## Questions?

If you have any problems or questions please reach out to us at techleads@joindrover.com
