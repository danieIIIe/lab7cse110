Danielle Sylliaasen

**1.** I would fit my automated tests in my Recipe project development pipeline within a GitHub action that runs whenever code is pushed. This is because we want to check **everytime** that the new changes pass the tests before they are pushed out. If they fail, then we know we have some issues. So, the most appropriate place to put the automated tests is within a GitHub action.

**2.** No, I would not use an end to end test to check if a function is returning the correct output as a unit test would be more favorable.

**3.** Navigation mode analyzes a page right after it loads while snapshot mode analyzes a page in its current state.

**4.** Based on the Lighthouse results, the CSE 110 shop site can be improved by **1)** properly sizing images to potentially save 864KiB. **2)** reduce unused Javascript to potentially save 66KiB. **3)** preconnecting to the required origins, fakestoreapi.com, to potentially save 60ms.
