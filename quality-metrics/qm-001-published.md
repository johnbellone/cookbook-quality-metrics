---
SMQM: 001
Author: Nathen Harvey <nharvey@chef.io>
Status: Accepted
License: Apache 2.0
---

# Published to the Supermarket

* The cookbook is published to the Supermarket
* The cookbook is not deprecated
* The cookbook is not up for adoption

Deprecated or adoptable cookbooks should be used with extreme caution.

### Verification

This is pseudocode

    it 'is published to the supermarket' do
      expect((cookbook.deprecated? && cookbook.up_for_adoption?)).to be false
    end

### Points

* Positive Points:  1
* Negative Points: 100 if deprecated, 25 if up for adoption

One point will be awarded if the quality metric is met.

One hundred points will be deducted if the cookbook has been deprecated.  Twenty five points will be deducted if the cookbook is up for adoption.
