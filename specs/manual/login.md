---
testspace:
---

# Login
* Given the user is already registered to Site Scan Manager

## User navigates to Site Scan
* Given the user opens a 'Chrome' instance.
* When the user enters 'https://staging.stscn.net/projects' in the address bar
* And the user hits enter
* Then the Site Scan Login page should open

## User logs in
* Given the user is in the 'Login' page
* When the user inputs 'the correct email address' in the 'email field'
* And the user inputs 'the correct password' in the 'password field'
* And the user clicks 'the Login button'
* Then the user should be redirected to the Home page

## User signs out
* Given the user is already logged in to Manager
* And the user is on any page where the Organization icon is visible
* When the user clicks 'the Organization icon'
* And the user clicks 'Sign Out'
* Then the user should be redirected to the Login page.

## Just testing image links
* Given I followed the instructions
* When I execute this test
* Then an image should be visible somewhere in this test case.\
  ![](https://knowpathology.com.au/app/uploads/2018/07/Happy-Test-Screen-01.png)
* And emojis? :+1: :cactus: :mushroom: :ram: :octocat: :squirrel: :space_invader:

---
* Close browser
