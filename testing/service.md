---
title: Service
description: Requirements for testing an Module service
has_children: false
nav_order: 2
parent: Testing
---

# Service

A Visual Studio MSTest Test project must be used to test a service. The test project should be named following the convention {service-project}.Test, eg. ``RCL.MWF.Subscription.Core.Test``.

A Unit Test must be developed for each service provided by the module. The unit test should use suitable parameters for the test and assert that the actual outcome meet the requirements for the expected outcomes.

