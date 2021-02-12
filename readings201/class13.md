# Class 12 Local storage #

## The history of storage ##
- Before HTML5, application data had to be stored in cookies, included in every server request.
- Cookies were used for persistent local storage of small amounts of data.

## Downsides of cookies ##
- slowing down your web application by needlessly transmitting the same data over and over
- sending data unencrypted over the internet.
- they are limited to about 4 KB of data — enough to slow down your application.

## what is HTML Web Storage ## 
- web applications can store data locally within the user's browser.
- Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.
- the storage limit is far larger (at least 5MB) and information is never transferred to the server.

## HTML Web Storage Objects ##
- window.localStorage - stores data with no expiration date
- window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

  * The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.
  * The sessionStorage object is equal to the localStorage object, except that it stores the data for only one session. The data is deleted when the user closes the specific browser tab.



