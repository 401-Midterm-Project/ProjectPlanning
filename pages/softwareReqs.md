# Software Requirements

## [Home](../README.md)

---

## SCOPE IN/OUT

### IN - What will our project do?

* The web app will provide all users information about local daycares that they might have an interest in.

* The web app will allow a user to be distinguished between a parent and a daycare provider when logging in/creating a user account.

* The web app will allow users to create a username and access different parts of the application depending on what type of user they are (parent vs provider).

* The web app will show the **parent user**s information about the different daycares, what they might offer/not offer and allow them to search by the different daycare amenities.

* The web app will allow daycare providers the ability to add their daycare to the app so that **parent user**s can then search for the daycare.

### OUT - What will our project NOT do?

* Our app will not offer an application process for different daycares.

* Our app will not offer an option for the user to review different daycares.

---

## Functional Requirements

* As a **daycare owner**, I want to create an account so I can login & manage my business' location/contact info.
* As a **daycare owner**, I'd like to publicly display my location on the site.
* As a **daycare owner**, I'd like to add/remove amenities that my location has.
* As a **daycare owner**, I need to be able to add my license info to verify my business as a legal daycare.
* As a **parent user** I want to be able to create an account.
* As a **parent user**, I want the site to remember me.
* As a **parent user**, I would like to be able to save my searches.
* As a **parent user**, I'd like to see contact info for the daycares.
* As a **parent user**, I'd like to be able to see a daycare's availability.
* As a **daycare owner**, I'd like to be able to update my location's availability.

---

## Data Flow

* User creates an account as either a **PARENT** or **DAYCARE PROVIDER**.
* After account is created user will just have to sign in.

### PARENT

* Is able to search for a daycare and have list shown to them by what amenities they are looking for.
* List will show them information about each daycare (summary, contact info, price, etc).
* Able to save their search so they can reference it whenever they want to.

### DAYCARE PROVIDER

* Is able to fill out a form to submit their daycare to the application.
* They can add all the amenities the daycare provides so that the **parent user** will be able to see them.

### NON-USER

* Will be able to see a list all of all the daycares and information about each and sort, but not save search.

* App will show a general WELCOME PAGE and what the app is/does. App will also show an ABOUT US page.

---

## Non-Functional Requirements

1) Security - the security on the site would be defined by the roles so that the parent and the daycare can only add/modify their own information.
2) Testability - we will be able to test the routes of our site through Swagger and that the migrations are logging/saving our data as we had anticipated.

---
