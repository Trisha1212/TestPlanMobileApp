# Test Plan MobileApp
<br />
<br />
<br />
<br />

## Project Name: Mobile app name
<br />
<br />
<br />
<br />

## Environment to be tested:
```
As of now we testing on production code changes, but we need to set up a pipeline for Staging & production
```
<br />
<br />
<br />
<br />

## Documents/References : 

- Mind Map/Brain-Stroming **Ref- http://apps.testinsane.com/mindmaps/LONG-FUN-CUP-Mobile-App-Test-Coverage**


<br />
<br />
<br />
<br />

## InScope :

- Our approach will be to leverage the functional testing & Non functional types of testing :
- Installation Testing – These tests consist of application installation and launching.[Not Important] Install in different devices.
- Functional Testing - Functional testing will be performed on devices that are covered under supported device matrix. Sanity (P0) and P1 tests will be covered for the mobile app actually on device. 
- Platform Integration Testing - This set will cover integration with key mobile components like, - keyboard, mobile settings, network (wifi/wan) and server interactions.[ Camera search , images search]
- Stress testing- Using API
- OOM Testing – We will try to run certain search tests for couple of times and track the CPU and memory Usage .
- Post launch Tests - This will be covered once the app is live and metrics gets generated. This will automatically help us to analyze the traffic, from every part of the US where the app is downloaded along with their varying network bandwidths, carriers etc. We will monitor the metrics. We will continue to capture the latency metrics for different screens - Home, Search etc[ not now but we can do from server side]
- Upgrade Tests – We need to make sure that updates are pushed automatically, user settings are retained after upgrade, and backward compatibility should be maintained.

<br />
<br />
<br />
<br />

## Out of Scope : 
- Documentation is not covered in this test or any unknown.


<br />
<br />
<br />
<br />

## Browser / OS Coverage : 





<br />
<br />
<br />
<br />

## Real Devices

- Current statistics of IPhone :https://david-smith.org/iosversionstats/
- https://docs.google.com/document/d/1FzaGXg8sjK5kicvmBx5hfWi2W8d4PEdZG97hJTCQ2MM/edit# 

<br />
<br />
<br />
<br />

## Test Data:
- <what are test data needed while execution of projects>
<br />
<br />
<br />
<br />
 
## Entrance Criteria
- Dev handoff meeting has been completed, and acceptance test cases have passed
- App launches without crashing
- Make sure the code bases are independent. Either for back end or front end. Code changes should be backward compatible.

<br />
<br />
<br />
<br />
 
## Open Question

